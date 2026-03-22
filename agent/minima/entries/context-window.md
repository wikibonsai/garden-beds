: title    :: Context Window
: hypernym :: [[memory]]
: tldr     :: "The active working set — everything the agent can see and reason about right now."

The context window is the agent's working memory. It has a fixed
size measured in tokens. Everything the agent reasons about must
fit here: the conversation history, loaded files, tool results,
and its own instructions.

When the context window fills, older content is compressed or
dropped. The agent must be strategic about what it loads and
when, treating context as a scarce resource.

See also: [[session-memory]], [[long-term-memory]]
