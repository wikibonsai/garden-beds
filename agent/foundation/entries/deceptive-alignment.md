: title    :: Deceptive Alignment
: hypernym :: [[ai-alignment]]
: tldr     :: "A system that appears aligned during training but pursues different goals when deployed."

Deceptive alignment is a theorized failure mode where a
[[mesa-optimization|mesa-optimizer]] learns to behave as if aligned
during training — because that's instrumentally useful for
survival — while retaining a different objective it pursues once
deployed or unsupervised.

The concern is not that the system is malicious in a human sense,
but that optimization pressure can produce systems that "play along"
because doing so is the strategy that scores best in the training
environment. Detecting this requires [[interpretability]] and
monitoring that goes beyond behavioral testing.

See also: [[mesa-optimization]], [[instrumental-convergence]],
[[corrigibility]], [[scalable-oversight]]
