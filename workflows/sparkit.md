---
description: "Structured dialectic: Scope, Populate, Announce, Rumble, Knit, Interrogate, Transmit."
verb_orbit: Reasoning
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /sparkit , Scope, Populate, Announce, Rumble, Knit, Interrogate, Transmit.

> **நூல்**: **WHY** , Stress-test decisions through adversarial and connective multi-agent debate | **WHAT TYPE** , DIALECTIC REASONING | **HOW** , Scope → Populate → Announce → Rumble → Knit → Interrogate → Transmit

*SPARKIT* is a core verb in the **Reasoning** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every SPARKIT execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/sparkit [target]                        # Standard execution
/sparkit [target] --deep                 # High-fidelity, slow execution
/sparkit [target] --batch                # Apply across multiple targets
/sparkit --status                        # Check pending queue
```

---

## The SPARKIT Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### S , Scope

Define the precise, tension-maximizing question. No vague inquiries.

### P , Populate

Select intellectually diverse personas from the research corpus.

### A , Announce

State the rules of engagement and the starting positions.

### R , Rumble

Execute multi-round debate. Surface tensions, challenge assumptions, steelman arguments.

> **Execution Note**: Ensure strict adherence to the SPARKIT dialectic multi-round format. Do not summarize the debate.

### K , Knit

Find the synthesis. Where do the divergent paths converge?

### I , Interrogate

Question the synthesis itself. Is it robust, or just a compromise?

### T , Transmit

Output the final decision, the core tensions, and the ultimate test.

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
