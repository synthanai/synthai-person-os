---
description: "Comparative analysis: Calibrate, Observe, Map, Polarize, Analyze, Recommend, Extract."
verb_orbit: Reasoning
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /gather , Calibrate, Observe, Map, Polarize, Analyze, Recommend, Extract.

> **நூல்**: **WHY** , Evaluate multiple entities horizontally to find the definitive path | **WHAT TYPE** , HORIZONTAL EVALUATION | **HOW** , Calibrate → Observe → Map → Polarize → Analyze → Recommend → Extract

*GATHER* is a core verb in the **Reasoning** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every GATHER execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/gather [target]                        # Standard execution
/gather [target] --deep                 # High-fidelity, slow execution
/gather [target] --batch                # Apply across multiple targets
/gather --status                        # Check pending queue
```

---

## The GATHER Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### G , Calibrate

Set the dimensions of comparison. What metrics matter?

### A , Observe

Gather data on all entities across the chosen dimensions.

### T , Map

Place the entities on a comparative matrix.

### H , Polarize

Force distinction. What makes A fundamentally different from B?

### E , Analyze

Assess the trade-offs, strengths, and critical gaps.

### R , Recommend

Propose the winning entity or the necessary hybrid.

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
