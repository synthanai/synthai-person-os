---
description: "Identity Foundation: Calling, Origin, Reason, Endurance."
verb_orbit: "Professional Pathway"
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /profile , Identity Foundation

> **நூல்**: **WHY** , Anchor your professional execution in an unshakeable core identity. | **WHAT TYPE** , IDENTITY EXTRACTION | **HOW** , Calling → Origin → Reason → Endurance

*PROFILE* is a legacy framework within the **Professional Pathway** of Person-OS, mapping complex professional mechanics into structured execution.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every PROFILE execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/profile [person_name]            # Extract full CORE profile
/profile --deep                   # High-fidelity narrative extraction
/profile --json                   # Output as structured data for agent ingestion
```

---

## The PROFILE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### C , Calling

Define the ultimate ambition. What is the gravitational pull of your work?
Extract the primary driver that transcends job titles.

```bash
# Example extraction filter
grep -i "purpose\|mission\|calling" source_interviews.md
```

### O , Origin

Map the foundational experiences that shaped the worldview.
Identify the "Scar Moments" and early victories that forged the current operational style.

### R , Reason

Articulate the logical framework. Why this path, and why now?
Deconstruct the rational justification for the current trajectory.

### E , Endurance

Identify the fuel source. What sustains execution when motivation fails?
Determine the boundaries, the non-negotiables, and the structural resilience.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ PROFILE complete for [Target]
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
