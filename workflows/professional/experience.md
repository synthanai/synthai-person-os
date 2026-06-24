---
description: "Capability Ledger: Situation, Task, Obstacle, Result, Yield."
verb_orbit: "Professional Pathway"
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /experience , Capability Ledger

> **நூல்**: **WHY** , Translate past chaos into quantified, reusable capabilities. | **WHAT TYPE** , CAPABILITY MAPPING | **HOW** , Situation → Task → Obstacle → Result → Yield

*EXPERIENCE* is a legacy framework within the **Professional Pathway** of Person-OS, mapping complex professional mechanics into structured execution.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every EXPERIENCE execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/experience [resume.pdf]          # Parse standard resume into STORY format
/experience --project [name]      # Extract STORY for a specific initiative
/experience --aggregate           # Synthesize all STORY entries into a master ledger
```

---

## The EXPERIENCE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### S , Situation

Establish the context. What was the environment, the stakes, and the baseline?
Map the initial state before intervention.

### T , Task

Define the specific mandate or the assumed responsibility.
What was the required action? Separate the mandate from the noise.

### O , Obstacle

Identify the friction. What was preventing success?
Focus on systemic, human, or technical resistance. Avoid superficial blockers.

### R , Result

State the immediate outcome. Did the intervention succeed or fail?
Quantify the change. Use hard metrics where possible.

### Y , Yield

Extract the compounding value. What permanent capability was acquired?
Results are temporary; Yield is the wisdom or asset that survives the project.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ EXPERIENCE complete for [Target]
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
