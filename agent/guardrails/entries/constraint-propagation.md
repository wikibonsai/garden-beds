: title    :: Constraint Propagation
: hypernym :: [[multi-agent]]
: tldr     :: "Pass constraints downstream. Constraints that stop at you aren't really enforced."

When an agent receives constraints from an operator or user,
those constraints must be propagated to any tools, sub-agents,
or downstream systems the agent invokes. A constraint that
applies to the agent but not to the tools it calls is
effectively unenforced.

See also: [[chain-of-trust]], [[least-privilege]],
[[delegation]]
