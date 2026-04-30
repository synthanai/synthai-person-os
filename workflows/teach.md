---
description: "Knowledge transfer: Tailor, Empathize, Anchor, Challenge, Help."
verb_orbit: Contribution
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /teach , Tailor, Empathize, Anchor, Challenge, Help.

> **நூல்**: **WHY** , Transfer understanding to others by bridging the gap between their context and yours | **WHAT TYPE** , PEDAGOGICAL TRANSFER | **HOW** , Tailor → Empathize → Anchor → Challenge → Help

*TEACH* is a core verb in the **Contribution** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every TEACH execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/teach [target]                        # Standard execution
/teach [target] --deep                 # High-fidelity, slow execution
/teach [target] --batch                # Apply across multiple targets
/teach --status                        # Check pending queue
```

---

## The TEACH Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### T , Tailor

Adapt the curriculum to the learner's current cognitive capacity.

### E , Empathize

Understand their starting point, their fears, and their blind spots.

### A , Anchor

Connect new concepts to their existing, familiar mental models.

### C , Challenge

Push them past their comfort zone. Induce productive struggle.

### H , Help

Provide the specific scaffolding they need to succeed, then remove it.

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
