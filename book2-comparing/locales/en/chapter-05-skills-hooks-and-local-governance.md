# Chapter 5: Skills, hooks, and local governance

Claude Code keeps local governance close to the runtime. `CLAUDE.md`, memory, and skills form a living rule book that follows the loop. Every workspace, directory, and context can bring its own checklist. The harness ingests those local rules on the fly, creating a sense of “things you remember to do here” that blends with the runtime control plane.

Codex, on the other hand, encodes local governance as structured fragments—skills, hooks, instructions, and event handlers. Each hook is a typed extension point. Local experience is not left implicit; it is scaffolded through explicit fragments that declare scope, priority, and inheritance. The system knows which local rule applies because the rule arrived as a describable object.

The comparison clarifies a trade-off: Claude Code’s approach feels closer to an operational shift with sticky notes; Codex’s feels closer to a regulated bureaucracy with policy documents. Both can host hooks and skills, but they differ in how local knowledge is surfaced, documented, and enforced.
