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
/spar [question]                  # Initiate debate
/spar [question] --style=hostile  # High-friction adversarial debate
/spar --resume [debate_id]        # Continue an existing debate
```

---

## The SPARKIT Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### S , Scope

Define the precise, tension-maximizing question. No vague inquiries.
The question must force a choice between two valid but competing values (e.g., Velocity vs. Governance).

### P , Populate

Select intellectually diverse personas from the research corpus.
Pull from `/2-research/persons/theorists/` or `/leaders/`. Ensure clash of paradigms (Positivist vs. Constructivist).

### A , Announce

State the rules of engagement and the starting positions.
The Moderator opens the debate and forces each persona to state their thesis.

### R , Rumble

Execute multi-round debate. Surface tensions, challenge assumptions, steelman arguments.
The Moderator must intervene if the debate becomes an echo chamber. Force them to address the weakest points of their arguments.

> **Execution Note**: Ensure strict adherence to the SPARKIT dialectic multi-round format. Do not summarize the debate.

### K , Knit

Find the synthesis. Where do the divergent paths converge?
Identify the dialectic resolution—the "third way" that solves the contradiction.

### I , Interrogate

Question the synthesis itself. Is it robust, or just a compromise?
Subject the proposed solution to a final stress test.

### T , Transmit

Output the final decision, the core tensions, and the ultimate test.
Write the full transcript to `operations/spar/`. Update the relevant NOOLs.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ SPARKIT complete for [Target]
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
