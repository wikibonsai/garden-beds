: title    :: Memory Integrity
: hypernym :: [[security-posture]]
: tldr     :: "Protecting the agent's persistent state from corruption, poisoning, or drift."

Memory integrity addresses the security of the agent's persistent
state: long-term memories, cached knowledge, learned preferences,
and accumulated context. An agent's memory is an attack surface —
if an adversary can corrupt what the agent remembers, they can
influence all future behavior.

Threats include: memory poisoning (injecting false information into
persistent storage), gradual drift (accumulated small errors
compounding over time), and context pollution (irrelevant
information crowding out relevant information). The defenses are:
validation on write, periodic auditing, and the ability to
distinguish between system-verified and user-asserted information.

See also: [[audit-trail]], [[source-trust-hierarchy]],
[[injection-resistance]], [[ground-truth-reestablishment]]
