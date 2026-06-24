---
description: "Pattern alignment: Group, Align, Track, Harmonize, Evaluate, Resolve."
verb_orbit: Reasoning
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /compare , Group, Align, Track, Harmonize, Evaluate, Resolve.

> **நூல்**: **WHY** , Resolve structural drift by aligning disparate artifacts | **WHAT TYPE** , STRUCTURAL ALIGNMENT | **HOW** , Group → Align → Track → Harmonize → Evaluate → Resolve

*COMPARE* is a core verb in the **Reasoning** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every COMPARE execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/compare [file1] [file2]          # Check drift between two files
/compare --baseline [file]        # Compare current state against a baseline
/compare --enforce                # Automatically apply harmonization
```

---

## The COMPARE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### C , Group

Bring the divergent artifacts together.
Load the files into the working context buffer.

### O , Align

Set them against the canonical standard (e.g., MBS, CORE, Quality Mandate).
What is the "Ground Truth" they are supposed to follow?

### M , Track

Identify exactly where the drift occurred.
Generate a `diff` or a semantic variance report. List the exact line numbers and concepts that drifted.

### P , Harmonize

Adjust the structures to match the standard without losing their unique value.
Rewrite the divergent sections. Standardize the vocabulary (e.g., replace em-dashes with commas).

### A , Evaluate

Check if the harmonization broke any local dependencies.
Run a validation check. Did renaming a concept break a link elsewhere?

### R , Resolve

Finalize the alignment and commit the changes.
```bash
git add [files]
git commit -m "COMPARE: Harmonized drift against canonical baseline"
```

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ COMPARE complete for [Target]
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
