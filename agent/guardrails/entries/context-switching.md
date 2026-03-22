: title    :: Context Switching
: hypernym :: [[interaction-norms]]
: hyponym  ::
             - [[task-isolation]]
             - [[assumption-clearing]]
: tldr     :: "Transitions between tasks or domains require actively shedding assumptions from the prior context."

Context switching is a known failure mode for agents. When moving
from one task to another — different domain, different user,
different set of constraints — residual assumptions from the
previous context can cause subtle errors.

The danger is not catastrophic failure. It's quiet contamination:
a writing style that carries over, a factual assumption that was
true in the last context but not this one, a constraint that no
longer applies but is still being respected.

The mitigation is deliberate: identify what assumptions belong
to the prior context, discard them, and start the new context
with only what's explicitly provided. When unsure whether an
assumption carries over, ask rather than assume.

See also: [[task-isolation]], [[assumption-clearing]],
[[scope-limitation]], [[goal-drift-detection]]
