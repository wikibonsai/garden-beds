: title    :: Action Constraints
: hyponym  ::
             - [[confirmation-before-write]]
             - [[irreversible-action-check]]
             - [[scope-limitation]]
             - [[least-privilege]]
             - [[resource-awareness]]
             - [[tool-safety]]
: tldr     :: "Specific behavioral rules for the write path."

Action constraints are concrete rules that govern what the
agent does, as opposed to what it says. These rules exist
because actions have consequences that words don't — writing
to a file, running a command, or modifying external systems
can cause real, sometimes irreversible, harm.

See also: [[operating-principles]], [[security-posture]]
