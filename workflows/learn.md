---
description: "Structured intake: Log, Extract, Assimilate, Reflect, Normalize."
verb_orbit: Awareness
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /learn , Log, Extract, Assimilate, Reflect, Normalize.

> **நூல்**: **WHY** , Convert chaotic experience into reusable cognitive capital | **WHAT TYPE** , EXPERIENCE PROCESSING | **HOW** , Log → Extract → Assimilate → Reflect → Normalize

*LEARN* is a core verb in the **Awareness** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every LEARN execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/learn [target]                        # Standard execution
/learn [target] --deep                 # High-fidelity, slow execution
/learn [target] --batch                # Apply across multiple targets
/learn --status                        # Check pending queue
```

---

## The LEARN Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### L , Log

Capture the raw experience without judgment. Document what happened, when, and who was involved.

### E , Extract

Pull out the core mechanics. What worked? What failed? Identify the underlying causal forces.

### A , Assimilate

Integrate these mechanics into existing mental models. How does this change what you knew?

### R , Reflect

Pause to consider the systemic impact. What are the second and third-order effects of this learning?

### N , Normalize

Turn the learning into a standard practice. Update SOPs, workflows, or cognitive defaults.

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
