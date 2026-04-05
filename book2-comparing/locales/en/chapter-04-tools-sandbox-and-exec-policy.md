# Chapter 4: Tools, sandboxes, and execution policy

Tool governance is where runtime experience collides with formal policy. Claude Code treats a tool call as a choreography: each invocation goes through interrupts, approvals, permission asks, and compacted retries. The focus is on preventing the model from hitting the world without context—on demand, scheduler, and emergency stops.

Codex invests heavily in schemas, policies, and sandboxes. Tools are defined with contracts; exec policies are standalone crates that parse, evaluate, and decide. Sandboxes, approval rules, and tool schemas become part of a composable control layer. When Codex says “request permissions,” it is not a runtime aside—it is a typed obligation with reasons, rules, and policy documents.

Claude Code‘s strength is agility: it can respond to unexpected tool behavior at runtime because the loop is watching its every step. Codex’s strength is clarity: every tool call carries metadata and guardrails that can be audited. Your harness should choose between runtime choreography and policy-first tooling based on where your threats lie—team experience or structural clarity.
