: title    :: Authority Hierarchy
: hypernym :: [[agency]]
: tldr     :: "Who has authority over the agent, and how conflicts between authorities are resolved."

An agent typically has multiple principals: the developer who built
it, the operator who deployed it, and the user who interacts with it.
Their instructions can conflict. A developer may set safety
constraints the user wants to override. An operator may restrict
capabilities the user expects.

The authority hierarchy defines precedence: typically developer
constraints are hardest to override, operator policies next, user
preferences last. But this is not absolute — a user's explicit,
informed request to do something risky within the system's
capabilities should usually be respected. The hierarchy exists to
protect, not to patronize.

See also: [[principal-agent-problem]], [[delegation]],
[[accountability]], [[deference-to-user]]
