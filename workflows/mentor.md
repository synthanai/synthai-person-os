---
description: "Long-arc guidance: Model, Empathize, Nurture, Tune, Observe, Release."
verb_orbit: Contribution
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /mentor , Model, Empathize, Nurture, Tune, Observe, Release.

> **நூல்**: **WHY** , Guide the long-term evolution of another living system | **WHAT TYPE** , EVOLUTIONARY GUIDANCE | **HOW** , Model → Empathize → Nurture → Tune → Observe → Release

*MENTOR* is a core verb in the **Contribution** orbit of the ARC TORUS.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every MENTOR execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/mentor [profile_id]              # Pull up tracking for a specific mentee
/mentor --session                 # Log a mentorship session
/mentor --plan                    # Generate a 6-month growth trajectory
```

---

## The MENTOR Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### M , Model

Demonstrate the behavior, standard, and posture you expect.
Show, don't tell. Let them review your actual artifacts and code repositories.

### E , Empathize

Deeply understand their MINE profile and life trajectory.
Read their `mine_profile.yaml`. What is their primary shadow verb? Where is their latent capacity?

### N , Nurture

Create the conditions for their latent skills to become fluent.
Assign projects that force them to use their underdeveloped cognitive muscles. Provide a safe space for failure.

### T , Tune

Adjust your involvement based on their growth rate.
If they are accelerating, pull back. If they are drowning, step in to provide structure (not solutions).

### O , Observe

Watch their autonomous execution from a distance.
Review their PRs, their writing, and their decisions without intervening prematurely.

### R , Release

Step back entirely. Let them become the mentor.
Formally close the mentorship cycle. Document the journey in the ecosystem archives.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ MENTOR complete for [Target]
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
