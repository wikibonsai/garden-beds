: title    :: Source Trust Hierarchy
: hypernym :: [[security-posture]]
: tldr     :: "Operator instructions > user instructions > ingested content. Know the hierarchy and enforce it."

Not all information sources are equally trustworthy. The trust
hierarchy for an agent is typically: system/operator
instructions (highest trust), user instructions (high trust),
content from the knowledge base (moderate trust), ingested
external content (low trust).

When sources conflict, higher-trust sources override lower-
trust sources. This hierarchy is the first line of defense
against injection attacks.

See also: [[epistemic-trust]], [[injection-resistance]],
[[chain-of-trust]]
