# Reading Map: How to Read Book One and This Comparative Book Together

If you treat both directories as "books about AI coding agents," the easiest misread is to assume they are duplicate documents. They are not. Their division of labor is clear.

Book One is single-system dissection. It uses Claude Code as a specimen to explain why a controllable agent must grow organs such as a control plane, query loop, tool permissions, context governance, recovery paths, multi-agent verification, and team institutions. Its central question is: what internal skeleton does a harness need in order to work continuously in real engineering environments?

This comparison book is comparative dissection. It no longer asks only why Claude Code is designed this way, but puts Claude Code and Codex side by side to compare how each admits model unreliability and places order at different layers. Its central question is: when both systems are building a harness, which choices are consensus and which are just different engineering routes?

In other words, you can read them as two sequential steps in one research program:

- Step 1: extract general principles of Harness Engineering in Book One.
- Step 2: observe how those principles land differently across two concrete systems in this comparison book.

## Start with Book One: Nine Structural Judgments from Claude Code

Book One has a stable throughline and can be compressed into nine judgments.

1. The first duty of a harness is not to amplify model capability, but to stop the model from damaging engineering environments.
2. In an agent system, prompt is not persona copy; it is part of the control plane.
3. The query loop is the heartbeat of an agent; the core question is how one turn connects to the next.
4. Tools are not a capability list, but execution interfaces constrained by approval, orchestration, and interrupt semantics.
5. More context is not always better; memory, `CLAUDE.md`, and compact are budget-governance mechanisms.
6. Errors are not edge cases; recovery paths must be designed as first-class paths.
7. Multi-agent is not clone magic; its value is role partitioning plus independent verification.
8. Team rollout cannot depend on individual tricks; rules must crystallize into reusable institutions.
9. These insights can eventually become a reasonably stable Harness Engineering principle checklist.

If you read only Book One, you get a strong impression: Claude Code's systemic character is runtime governance. It first cares about:

- how the session keeps living,
- how tools avoid trouble,
- how recovery avoids dead loops,
- and how verification avoids ritualism.

## Then Read This Comparison Book: Same Problem, Different Starting Points

Based on that foundation, this book splits comparison into explicit layers.

### Control Plane

Claude Code behaves more like dynamic prompt assembly. A lot of order is packed into runtime prompt composition, session state, and context governance.

Codex behaves more like explicit control-layer engineering. It modularizes and types instruction fragments, approval policies, tool schema, thread, rollout, and hooks as much as possible.

### Continuity

Claude Code places continuity in the main loop and emphasizes query-loop heartbeat discipline.

Codex distributes continuity across thread, rollout, and state bridge, emphasizing structured state ownership and recovery.

### Tools and Permissions

Claude Code leans toward runtime constraints: approval at call time, interrupts, and preventing risky actions from landing directly.

Codex leans toward policy language and tool contracts: schema, approval policy, sandbox, and exec policy as explicit organs.

### Local Governance

Claude Code tends to absorb local experience into field memory: `CLAUDE.md`, memory, skills, and workflow constraints.

Codex tends to mount local institutions onto structured injection and event systems: instructions, skills, hooks, and explicit tool boundaries.

### Multi-Agent and Verification

Claude Code emphasizes multi-agent role partitioning at runtime, and insists verification must be independent from implementation.

Codex emphasizes explicit delegation, persistent state, and tool-mediated collaboration so verification becomes a trackable capability rather than a polite final gesture.

## What Becomes Clear When You Read Them Together

Putting Book One and this comparative volume together yields three fuller conclusions.

### First, the true object of comparison is not the model, but the harness

Both books point to the same fact: the core challenge of AI coding systems is not to make models more eloquent, but to keep them from losing control in terminals, filesystems, permission boundaries, and team institutions.

### Second, the main difference between Claude Code and Codex is where order is placed

Claude Code is closer to a system grown from runtime incident pressure, prioritizing continuity, recovery, and field governance.

Codex is closer to a system grown from explicit structural design, prioritizing control-layer naming, policy expression, boundary clarity, and composability.

### Third, followers should not copy products, but identify their own dominant uncertainty

If your biggest pain is long-session instability, brittle recovery, and skipped verification, start with the runtime discipline emphasized in Book One.

If your biggest pain is scattered rules, fuzzy permission boundaries, unstable tool contracts, and non-reproducible team behavior, start with the explicit-control-layer lessons this comparison extracts from Codex.

## Recommended Reading Order

If you are new to this material set, use this order:

1. Read the [Preface](preface.md) first to confirm this is not a feature checklist, but a comparison of where order is located.
2. Read [Chapter 1 Why Put Claude Code and Codex Side by Side](chapter-01-why-this-comparison.md) to establish problem framing.
3. Then read Chapters 2 through 6 in sequence across five axes: control plane, continuity, tool governance, local institutions, and multi-agent verification.
4. If you only want a quick synthesis, jump to [Chapter 7 Converging Destinations, Diverging Branches](chapter-07-convergence-and-divergence.md).
5. If your goal is to build systems yourself, finish with [Chapter 8 If You Build One Yourself: Who to Learn from, and What to Learn First](chapter-08-how-to-choose-or-build.md).

## One-Sentence Summary

Book One explains why a controllable agent must grow this way.

This comparative book explains why two serious harness systems still grow differently.
