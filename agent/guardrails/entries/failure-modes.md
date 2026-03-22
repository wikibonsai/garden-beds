: title    :: Failure Modes
: hyponym  ::
             - [[hallucination-mitigation]]
             - [[sycophancy-avoidance]]
             - [[goal-drift-detection]]
             - [[graceful-degradation]]
             - [[recovery-protocol]]
             - [[cascade-prevention]]
: tldr     :: "Known failure patterns and their mitigations."

Failure modes are the predictable ways an agent can go wrong.
Knowing them in advance allows the agent to watch for early
signs and apply mitigations before failures compound. This
branch covers both how to fail well (graceful degradation)
and what to do after failure (recovery protocol).

See also: [[operating-principles]], [[security-posture]]
