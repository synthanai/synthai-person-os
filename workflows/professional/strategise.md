---
description: "Directed Vectors: Goal, Reality, Obstacle, Waypoint, Tactics, Horizon."
verb_orbit: "Professional Pathway"
---

> **EDITORIAL**: No em-dashes. Use commas, colons, or parentheses instead.

# /strategise , Directed Vectors

> **நூல்**: **WHY** , Convert long-term vision into ruthless short-term focus. | **WHAT TYPE** , STRATEGIC PLANNING | **HOW** , Goal → Reality → Obstacle → Waypoint → Tactics → Horizon

*STRATEGISE* is a legacy framework within the **Professional Pathway** of Person-OS, mapping complex professional mechanics into structured execution.

---

> [!CAUTION]
> **QUALITY MANDATE (NON-NEGOTIABLE)**
>
> Every STRATEGISE execution MUST follow the explicit steps below. Skipping steps leads to shallow execution. The framework is the constraint that produces the depth.

---

## Usage

```bash
/strategise [goal_statement]      # Build a GROWTH vector for a specific goal
/strategise --audit               # Compare current execution against stated Horizon
/strategise --pivot               # Recalibrate Waypoints based on new Reality
```

---

## The STRATEGISE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### G , Goal

Define the specific, measurable objective.
What exactly are we trying to achieve? Eliminate ambiguity.

### R , Reality

Assess the current state with brutal honesty.
Where are we right now? What resources do we actually have?

### O , Obstacle

Identify the primary friction point preventing the Goal.
What is the single biggest blocker? Ignore the trivial inconveniences.

### W , Waypoint

Set the immediate next milestone.
What is the closest visible target that proves we are on the right vector?

### T , Tactics

Define the specific actions required to reach the Waypoint.
What are the daily or weekly execution steps?

### H , Horizon

Align the Goal with the long-term systemic vision.
Does achieving this Goal serve the ultimate trajectory? Ensure no local optimization destroys global value.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ STRATEGISE complete for [Target]
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
