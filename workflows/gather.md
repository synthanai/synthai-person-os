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
/gather [entityA] [entityB]       # Compare two entities
/gather --dir [path]              # Evaluate all items in a directory
/gather --dimensions "Speed,Cost" # Custom comparison matrix
```

---

## The GATHER Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### G , Calibrate

Set the dimensions of comparison. What metrics matter?
Define the exact criteria for scoring (e.g., 1-5 scale for 'Alignment with MBS', 'Technical Debt', 'Execution Speed').

### A , Observe

Gather data on all entities across the chosen dimensions.
Read the source files and compile the raw evidence for each entity.

### T , Map

Place the entities on a comparative matrix.
Generate a Markdown table aligning the entities side-by-side against the dimensions.

### H , Polarize

Force distinction. What makes A fundamentally different from B?
Highlight the largest deltas in the matrix. Where is the friction most apparent?

### E , Analyze

Assess the trade-offs, strengths, and critical gaps.
Write a 1-sentence justification for each major gap identified.

### R , Recommend

Propose the winning entity or the necessary hybrid.
Based strictly on the matrix, which entity solves the core problem most effectively?

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ GATHER complete for [Target]
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
