---
description: "Compression engine: Deconstruct, Isolate, Group, Extract, Synthesize, Trim."
verb_orbit: Reasoning
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /digest , Deconstruct, Isolate, Group, Extract, Synthesize, Trim.

> **நூல்**: **WHY** , Compress massive complexity into high-density actionable signal | **WHAT TYPE** , INFORMATION COMPRESSION | **HOW** , Deconstruct → Isolate → Group → Extract → Synthesize → Trim

*DIGEST* is a core verb in the **Reasoning** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every DIGEST execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/digest [target]                        # Standard execution
/digest [target] --deep                 # High-fidelity, slow execution
/digest [target] --batch                # Apply across multiple targets
/digest --status                        # Check pending queue
```

---

## The DIGEST Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### D , Deconstruct

Break the massive input down into elemental statements.

### I , Isolate

Separate the signal from the noise. Discard the fluff.

### G , Group

Cluster related signals together. Find the emergent themes.

### E , Extract

Pull the core essence from each cluster.

### S , Synthesize

Weave the extracted essences into a coherent, dense narrative.

### T , Trim

Cut every word that does not serve the synthesis. Legacy over speed.

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
