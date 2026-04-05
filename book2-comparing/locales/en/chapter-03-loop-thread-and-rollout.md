# Chapter 3: Heartbeat, threads, rollouts, and bridges

This chapter drills into continuity. Claude Code bets on the query loop as the heartbeat. Every round is responsible for sequencing tool calls, merging outputs, compacting context, and preparing the next iteration. The design pressure is on “how does each loop hand off safely?”—so the harness pours attention into runtime scheduling, interrupts, and precise permission checks around every call.

Codex spreads continuity across threads, rollouts, and explicit state bridges. Rather than one central loop, it composes smaller subhistories that are persisted, linked, and recovered through structured state artifacts. The emphasis is on reducible, inspectable units—rollout logs, persistent thread state, and bridges between fragments—rather than trust that a single loop can keep everything coherent.

Both systems center continuity, but Claude Code keeps it inside a flexible main loop while Codex distributes it across typed state machines. Teams that dread long conversations slipping away may gravitate toward Claude Code’s heartbeat; teams that need durable, inspectable thread state may prefer Codex’s explicit bridges.
