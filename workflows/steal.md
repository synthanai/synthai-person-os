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
/steal [target]                        # Standard execution
/steal [target] --deep                 # High-fidelity, slow execution
/steal [target] --batch                # Apply across multiple targets
/steal --status                        # Check pending queue
```

---

## The STEAL Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### S , Scan

Survey the external landscape for relevant signals, avoiding echo chambers. Cast a wide net across diverse domains.

> **Execution Note**: Utilize external scraping and headless browsers when required. Avoid hallucination.

### T , Translate

Convert raw signal into SYNTHAI cognitive vocabulary (MBS, ARC, MINE). Refine the terminology.

### E , Evaluate

Assess relevance, credibility, and novelty. Check schema compliance and domain coverage.

### A , Abstract

Extract transferable patterns from specific instances. Document NOOL (Intent, Abstraction, Chain) and actionable signals.

### L , Leverage

Apply patterns to the current SYNTHAI context. Route backlog candidates and update the intelligence index.

---

## Output Report

Provide a structured report upon completion:

```
✅ {verb.upper()} complete for [Target]
📄 Artifacts generated: [List paths]
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
