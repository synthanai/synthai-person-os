---
description: "Intelligence capture: Scan, Translate, Evaluate, Abstract, Leverage."
verb_orbit: Awareness
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /steal , Scan, Translate, Evaluate, Abstract, Leverage.

> **நூல்**: **WHY** , Build the evidence base that grounds every SYNTHAI claim | **WHAT TYPE** , INTELLIGENCE CAPTURE | **HOW** , Scan → Translate → Evaluate → Abstract → Leverage

*STEAL* is a core verb in the **Awareness** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every STEAL execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/steal [topic]                    # Full STEAL cycle (topic-based)
/steal [topic] --type=[type]      # Skip classification
/steal [topic] --scan-only        # Classify only, don't execute
/steal --url "https://..."        # STEAL from a URL
/steal --imessage                 # Pull new URLs from iMessage
/steal --batch                    # Dashboard of batch pipeline status
```

---

## The STEAL Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### S , Scan

Analyze `[topic]` to determine its category. If `--url` provided, scrape first then classify.
Survey the external landscape for relevant signals, avoiding echo chambers. Cast a wide net across diverse domains.

**Execution:**
Use headless browsers or URL scrapers to pull the raw HTML/Text.
```bash
python 4-utilities/research/steal_scraper.py "[URL]"
```
Categorize into: Organisation, Concept, Theorist, Leader, Framework, Methodology, Event.

> **Execution Note**: Utilize external scraping and headless browsers when required. Avoid hallucination.

### T , Translate

Translate external knowledge into SYNTHAI format by running the specialist workflow for the classified type. The specialist reframes raw findings through the SYNTHAI lens (MBS, emergence, RAMP).

**Actionable:** Map external jargon to SYNTHAI canonical terms. (e.g., "Company Culture" -> "Soul layer", "KPIs" -> "Body layer").

### E , Evaluate

Check schema compliance, domain coverage, source quality. 
Run the validation scripts to ensure the captured intelligence is structurally sound.

```bash
python 4-utilities/research/validate_research.py --org [slug]
```
Report PASS/WARNINGS/ERRORS. Reject low-signal noise immediately.

### A , Abstract

Abstract the transferable patterns into `signals.md`:
- **நூல் / NOOL section**: Intent (why this research matters), Abstraction (problem type), Chain (how it connects to action)
- 🎯 Action Items (P0-P3 priority, owner, target)
- 💡 Recommendations (confidence, scope)
- ❌ Rejections (reason, SYNTHAI alternative)

**Output:** `2-research/[type]/[slug]/signals.md`

### L , Leverage

The step that makes /steal more than /research. Leverage what you abstracted, save the work, queue the plan.

1. **Update Index**:
```bash
python 4-utilities/research/research_indexer.py --update [slug]
```
2. **LOON Proposal**: If findings suggest a NOOL's assumptions were wrong or incomplete, propose a LOON entry.
3. **Commit & Queue**:
```bash
git add 2-research/[type]/[slug]/
git commit -m "STEAL: [Topic] , research + signals queued"
```

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ STEAL complete for [Target]
📄 Artifacts generated:
  - path/to/output_1.md
  - path/to/output_2.yaml
📊 Key Metrics: [Relevance/Impact/Score]
✓  Validation: [PASS/WARNINGS/ERRORS]
💾 Committed: [commit hash]
```

### 💾 Mandatory Persist (State Handoff)

> **CRITICAL RULE**: Do not rely on chat context to pass state to the next workflow. 

Every workflow execution MUST persist its output to a physical artifact in the repository. This artifact serves as the uncorrupted input for the next verb in the sequence. 

- **If an appropriate directory exists**, save it there (e.g., `operations/spar/`, `2-research/`).
- **If no directory is defined**, save it to `.agent/scratch/` or `operations/queues/` with a descriptive timestamped filename.
- Conclude your chat response by explicitly providing the **Artifact URI** to the user so they can trigger the next workflow targeting that precise path.
