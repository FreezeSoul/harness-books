# Chapter 8: If you build your own harness, what to study first

Use this chapter as a checklist to pick your guiding path.

1. **Identify your primary uncertainty.** Is it long sessions derailing, or unclear rule ownership?
2. **Map the order of constraints.** If continuity matters, invest in query loops, compaction, and interrupts. If clarity matters, invest in typed fragments, policies, and thread state.
3. **Match tooling to governance.** Runtime-focused harnesses need fast recovery, flexible prompts, and local rule ingestion. Structure-driven harnesses need explicit fragment boundaries, schema-based tools, and policy crates.
4. **Plan verification and state.** Decide whether verification will be a runtime safety net (Claude Code style) or a structured, auditable pipeline (Codex style).
5. **Document local governance.** Write `CLAUDE.md`-style reminders if you need loose, location-specific rules; write `AGENTS.md`-style fragments if you need scoped, inheritable policies.

The harness you build will reflect these choices. Order your controls deliberately, and your system's behavior will grow around that scaffolding.
