# Appendix A: Source map for this comparison

This appendix lists the primary files and modules referenced when comparing Claude Code and Codex. No proprietary code is reproduced. Instead, the comparison rests on observable module boundaries and documented interfaces.

- **Claude Code**
  - `src/query.ts`, `compact.ts`, `toolOrchestration.ts`: runtime heartbeat, tool choreography, and recovery flows.
  - `CLAUDE.md` plus memory and skill files: local rules that travel with the loop.
  - Permission-related utilities (`askPermission`, `interrupt`, `resume`): runtime safeguards.

- **Codex**
  - `core/src/lib.rs`: fragments, threads, rollouts, and tool contracts that express explicit control.
  - `instructions/src/fragment.rs`, `user_instructions.rs`: structured instruction fragments with markers and scope.
  - `execpolicy/src/lib.rs`: policy language, evaluators, and decision logic that govern tool execution.
  - `docs/agents_md.md`: AGENTS fragments, inheritance, and scope explanations.

The chapter analyses synthesize these sources into architectural decisions; the appendix points to the files that make those decisions visible.
