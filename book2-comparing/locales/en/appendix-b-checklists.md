# Appendix B: Checklist for identifying your harness alignment

Use this checklist to spot whether your team feels closer to Claude Code or Codex and to guide your design decisions.

1. **Control placement**
   - If you rely on dynamic prompt assembly and runtime intervention, lean Claude Code.
   - If you prefer typed fragments, policy crates, and serialized instructions, lean Codex.
2. **Continuity**
   - Do you depend on a single query loop to carry the session heartbeat? Claude Code.
   - Do you manage threads, rollouts, and state bridges explicitly? Codex.
3. **Tool governance**
   - Do tools choreography run through interrupts, permission asks, and runtime sandboxes? Claude Code.
   - Are tools defined with schemas and governed by exec policies? Codex.
4. **Local governance**
   - Are local rules ingested as context (CLAUDE.md, memory, skills)? Claude Code.
   - Are they scoped fragments with inheritance (AGENTS.md)? Codex.
5. **Verification and delegation**
   - Is verification a runtime safety net, and delegation expressed through independent agents? Claude Code.
   - Is verification a persistent, auditable pipeline that traces state and delegations? Codex.

Answer the items that matter most for your team; the majority of answers points to the harness architecture you should make explicit.
