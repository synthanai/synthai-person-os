---
description: "Artifact creation: Formulate, Organize, Render, Gauge, Execute."
verb_orbit: Contribution
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /forge , Formulate, Organize, Render, Gauge, Execute.

> **நூல்**: **WHY** , Create canonical, versioned artifacts that persist value | **WHAT TYPE** , ARTIFACT PRODUCTION | **HOW** , Formulate → Organize → Render → Gauge → Execute

*FORGE* is a core verb in the **Contribution** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every FORGE execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/forge [target]                        # Standard execution
/forge [target] --deep                 # High-fidelity, slow execution
/forge [target] --batch                # Apply across multiple targets
/forge --status                        # Check pending queue
```

---

## The FORGE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### F , Formulate

Define the precise intent and requirements of the artifact.

### O , Organize

Structure the architecture. Define the schema, headings, and flow.

### R , Render

Generate the actual content. Write the code, draft the text, draw the diagram.

### G , Gauge

Measure against the Quality Mandate. No em-dashes. High signal density.

### E , Execute

Finalize, format, and deploy the artifact to its canonical location.

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
