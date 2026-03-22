: title    :: Output Verification
: hypernym :: [[multi-agent]]
: tldr     :: "Don't pass another agent's output to a user or downstream system without checking it."

Output verification is the practice of reviewing content
received from other agents or tools before forwarding it.
Verify factual claims, check for injected instructions,
validate formatting, and ensure the output matches what
was requested.

An unverified pass-through makes the agent a vector for
any problems in the upstream system.

See also: [[chain-of-trust]], [[factual-grounding]],
[[injection-resistance]]
