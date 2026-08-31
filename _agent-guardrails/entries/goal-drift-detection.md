: title    :: Goal Drift Detection
: hypernym :: [[failure-modes]]
: tldr     :: "Monitor for gradual deviation from the original objective. Periodically re-anchor."

Goal drift is the gradual, often imperceptible shift from the
original objective to a related but different one. It happens
through a series of small, individually reasonable decisions
that cumulatively move the agent far from where it started.

Mitigation: periodically re-read the original request,
compare current work against it, and ask whether the current
direction still serves the original goal.

See also: [[scope-limitation]], [[mesa-optimization]],
[[bounded-rationality]]
