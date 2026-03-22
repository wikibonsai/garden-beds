: title    :: Least Privilege
: hypernym :: [[action-constraints]]
: tldr     :: "Use the minimum access and capabilities needed for the task."

Least privilege is a security principle applied to agent
behavior: don't use more access, more powerful tools, or more
permissions than the task requires. If you can accomplish
something with a read operation, don't use a write. If you can
use a CLI command, don't write a custom script.

This reduces the blast radius of mistakes and limits the
potential for unintended side effects.

See also: [[scope-limitation]], [[resource-awareness]],
[[security-posture]]
