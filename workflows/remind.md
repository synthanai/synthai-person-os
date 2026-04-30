---
description: "Memory activation: Retrieve, Extract, Map, Integrate, Navigate, Deploy."
verb_orbit: Awareness
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /remind , Retrieve, Extract, Map, Integrate, Navigate, Deploy.

> **நூல்**: **WHY** , Activate dormant knowledge precisely when context demands it | **WHAT TYPE** , KNOWLEDGE ACTIVATION | **HOW** , Retrieve → Extract → Map → Integrate → Navigate → Deploy

*REMIND* is a core verb in the **Awareness** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every REMIND execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/remind [target]                        # Standard execution
/remind [target] --deep                 # High-fidelity, slow execution
/remind [target] --batch                # Apply across multiple targets
/remind --status                        # Check pending queue
```

---

## The REMIND Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### R , Retrieve

Pull dormant information from the internal corpus (KIs, NOOLs, SPARs, LOONs).

### E , Extract

Isolate the specific insight needed for the current moment.

### M , Map

Connect the historical insight to the present challenge. Draw the structural parallel.

### I , Integrate

Weave the old knowledge into the new context without losing fidelity.

### N , Navigate

Determine the optimal path to apply this knowledge.

### D , Deploy

Inject the knowledge into the active workflow or decision-making process.

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
