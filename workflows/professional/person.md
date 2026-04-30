---
description: "AI Partner Blueprint: Persona, Interface, Compass."
verb_orbit: "Professional Pathway"
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /person , AI Partner Blueprint

> **நூல்**: **WHY** , Synthesize operational frameworks into an actionable AI partner system. | **WHAT TYPE** , AI SYSTEM GENERATION | **HOW** , Persona → Interface → Compass

*PERSON* is a legacy framework within the **Professional Pathway** of Person-OS, mapping complex professional mechanics into structured execution.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every PERSON execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/person [user_profile_dir]        # Generate the full PIC blueprint
/person --mode [operate|lead|matter] # Generate a specific PIC module
/person --export-json             # Export for direct API ingestion
```

---

## The PERSON Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### P , Persona

Define the exact cognitive posture of the AI.
Is it an adversarial coach, a strategic peer, or an operational assistant? Set the tone, boundaries, and voice.

### I , Interface

Establish the rules of engagement. How does the user interact with this AI?
Define the exact input formats required and the specific output structures the AI must generate.

### C , Compass

Set the ultimate north star for the AI.
What is it optimizing for? What must it never compromise? Give the AI a specific teleological goal.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ PERSON complete for [Target]
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
