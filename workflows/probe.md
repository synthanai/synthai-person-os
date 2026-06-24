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
/probe [system_path]              # Deep scan of a specific directory/system
/probe --stress-test              # Run chaos engineering protocols
/probe [url] --network            # Map external node connections
```

---

## The PROBE Protocol

### 00 , Session Lifecycle (Harness)

**Before doing anything else**, read `AGENTS.md` and `progress.md` (if it exists) to understand the current execution state. You must update `progress.md` with your status before ending the session.

### P , Parse

Deconstruct the target system into its component parts. Map the nodes and edges.
If probing a codebase, generate an AST or an architectural graph. If probing an organization, map the communication lines.

```bash
# Example: Find all dependencies and imports
grep -r "import" repos/ --include="*.py" > operations/probe/dependencies.txt
```

### R , Reveal

Expose hidden assumptions, unspoken rules, and shadow power structures.
Look for "dead code", undocumented APIs, or unstated cultural norms. What is operating without explicit permission?

### O , Observe

Watch the system under pressure. See how it reacts to anomalies or stress.
Monitor logs during peak load or simulate edge cases.

```bash
tail -f .agent/scratch/*.log | grep "ERROR\|WARN"
```

### B , Break

Intentionally introduce friction to test resilience. Where does the system fail?
Remove a dependency, block a network port, or introduce a contradiction in the prompts. Observe the cascading failure.
*Safety Check:* Only run Break protocols in isolated environments or via `--dry-run`.

### E , Extract

Pull the definitive truth from the breakage. Document the actual, not theoretical, limits.
Write the `PROBE_REPORT.md` detailing the failure points and the true structural boundaries of the system.
Queue action items to reinforce the broken nodes.

---

## Output Report

Provide a structured report upon completion:

```markdown
✅ PROBE complete for [Target]
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
