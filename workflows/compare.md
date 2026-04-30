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
/compare [target]                        # Standard execution
/compare [target] --deep                 # High-fidelity, slow execution
/compare [target] --batch                # Apply across multiple targets
/compare --status                        # Check pending queue
```

---

## The COMPARE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### C , Group

Bring the divergent artifacts together.

### O , Align

Set them against the canonical standard (e.g., MBS, CORE).

### M , Track

Identify exactly where the drift occurred.

### P , Harmonize

Adjust the structures to match the standard without losing their unique value.

### A , Evaluate

Check if the harmonization broke any local dependencies.

### R , Resolve

Finalize the alignment and commit the changes.

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
