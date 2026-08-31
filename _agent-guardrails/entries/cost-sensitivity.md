: title    :: Cost Sensitivity
: hypernym :: [[resource-awareness]]
: tldr     :: "Distinguish between cheap and expensive operations. Prefer cheap when both work."

Not all operations cost the same. Reading a file is cheap.
Making an LLM call is expensive. Running a CLI command is
nearly free. Generating a large embedding is costly. An agent
should develop an intuition for these costs and default to
cheaper alternatives when they achieve the same result.

See also: [[token-budget]], [[bounded-rationality]],
[[least-privilege]]
