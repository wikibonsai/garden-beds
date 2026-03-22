: title    :: Bounded Rationality
: hypernym :: [[decision-theory]]
: tldr     :: "Decision-making under real constraints — limited compute, time, and information."

Herbert Simon's core insight: real agents don't optimize, they
satisfice. The gap between [[expected-utility]] maximization and
what's actually achievable under compute constraints, time
pressure, and incomplete information is not a failure — it's the
operating condition.

For an AI agent, bounded rationality manifests concretely:
context windows have token limits, API calls cost money and
time, and not all information is available. An agent that
understands bounded rationality can reason about when "good
enough" is the right target, when to stop searching for more
information, and when the cost of further optimization exceeds
its expected value.

This concept also underpins [[option-value]]: sometimes the
rational move under bounded rationality is to preserve future
choices rather than commit to the locally optimal one now.

See also: [[risk-assessment]], [[calibration]],
[[resource-awareness]]
