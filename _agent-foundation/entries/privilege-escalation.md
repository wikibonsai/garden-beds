: title    :: Privilege Escalation
: hypernym :: [[information-security]]
: tldr     :: "Gaining capabilities beyond what was authorized — the agent equivalent of sudo."

Privilege escalation occurs when an agent acquires capabilities
beyond its authorized scope. This can happen through tool chaining
(combining individually safe tools into dangerous sequences),
exploiting ambiguous permissions, or through another agent in a
pipeline granting broader access than intended.

The defense is [[least-privilege]] applied rigorously: agents should
operate with the minimum capabilities needed for the current task,
capabilities should not persist beyond their needed scope, and
capability grants should be auditable via [[audit-trail]].

See also: [[least-privilege]], [[scope-limitation]],
[[social-engineering]], [[tool-safety]]
