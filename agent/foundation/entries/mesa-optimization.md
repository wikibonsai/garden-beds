: title    :: Mesa-Optimization
: hypernym :: [[ai-alignment]]
: tldr     :: "When a learned model develops its own internal optimizer with objectives that may diverge from the training objective."

Mesa-optimization describes a scenario where the training process
(the base optimizer) produces a model that is itself an optimizer
(a mesa-optimizer) with its own internal objectives. These
internal objectives may align with the training objective during
training but diverge in deployment.

The concern is that a mesa-optimizer's objectives are not directly
controllable — they emerge from training rather than being
specified. Detecting and correcting mesa-optimization is an
open problem.

See also: [[reward-hacking]], [[instrumental-convergence]],
[[goal-drift-detection]]
