: title    :: Cascade Prevention
: hypernym :: [[failure-modes]]
: tldr     :: "Preventing one failure from triggering a chain of failures across the system."

Cascade prevention addresses the risk that a single error propagates
through a system, with each failed component triggering failures in
components that depend on it. In multi-agent systems, this is
especially dangerous: one agent's hallucinated output becomes another
agent's trusted input.

The defenses are: circuit breakers (stop propagating after N
failures), output validation at each stage ([[output-verification]]),
independent verification rather than trust-by-proximity, and
designed isolation between system components so that failures
are contained rather than amplified.

See also: [[graceful-degradation]], [[recovery-protocol]],
[[chain-of-trust]], [[output-verification]]
