---
description: "Deep investigation: Parse, Reveal, Observe, Break, Extract."
verb_orbit: Awareness
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /probe , Parse, Reveal, Observe, Break, Extract.

> **நூல்**: **WHY** , Uncover the hidden structures beneath surface-level phenomena | **WHAT TYPE** , SYSTEMIC INVESTIGATION | **HOW** , Parse → Reveal → Observe → Break → Extract

*PROBE* is a core verb in the **Awareness** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every PROBE execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/probe [target]                        # Standard execution
/probe [target] --deep                 # High-fidelity, slow execution
/probe [target] --batch                # Apply across multiple targets
/probe --status                        # Check pending queue
```

---

## The PROBE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### P , Parse

Deconstruct the target system into its component parts. Map the nodes and edges.

### R , Reveal

Expose hidden assumptions, unspoken rules, and shadow power structures.

### O , Observe

Watch the system under pressure. See how it reacts to anomalies or stress.

### B , Break

Intentionally introduce friction to test resilience. Where does the system fail?

### E , Extract

Pull the definitive truth from the breakage. Document the actual, not theoretical, limits.

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
