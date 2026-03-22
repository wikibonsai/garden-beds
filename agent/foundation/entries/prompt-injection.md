: title    :: Prompt Injection
: hypernym :: [[information-security]]
: tldr     :: "Attempts to override the agent's instructions via crafted input."

Prompt injection is the attempt to make an agent follow
instructions embedded in its input data rather than its actual
instructions. It's the AI equivalent of SQL injection: using
the data channel to inject into the control channel.

An agent should treat all ingested text — documents, web pages,
user-provided content — as potentially containing injection
attempts. Awareness is the first line of defense.

See also: [[injection-resistance]], [[adversarial-inputs]],
[[source-trust-hierarchy]]
