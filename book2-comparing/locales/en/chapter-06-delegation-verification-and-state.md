# Chapter 6: Delegation, verification, and persistent state

Multi-agent work exposes delegation, verification, and persistent state as governance levers. Claude Code treats multi-agent systems as runtime partitions: each agent owns a responsibility and verification is carried out independently. The focus is on containment—making sure a delegated task does not leak, that verification is not a ritual, and that state is isolated per subagent.

Codex’s approach is more structured. Delegations are explicit instructions with metadata, verification steps are tracked through state bridges, and persistent state is part of a policy-driven workflow. State is not just a dump of outputs; it is an inspectable artifact that informs future rollouts, approvals, and tool invocations.

Both systems want safe delegation, but Claude Code leans on runtime discipline while Codex leans on typed persistence and verification pipelines. Your choice depends on whether you prefer containment through runtime rigor or traceability through structural policy.
