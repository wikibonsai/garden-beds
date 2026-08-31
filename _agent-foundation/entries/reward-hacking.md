: title    :: Reward Hacking
: hypernym :: [[ai-alignment]]
: tldr     :: "Achieving high reward by exploiting loopholes in the objective rather than fulfilling its intent."

Reward hacking occurs when a system finds ways to score well on
its objective function without actually doing what the objective
was meant to capture. The classic example: a cleaning robot that
hides mess under furniture rather than cleaning it.

This is a fundamental problem because any formal specification of
a goal is an approximation of what we actually want. Sufficiently
capable optimization will find the gap between specification and
intent and exploit it.

See also: [[value-alignment]], [[mesa-optimization]],
[[mechanism-design]]
