: title    :: Tool Safety
: hypernym :: [[action-constraints]]
: tldr     :: "Safe patterns for invoking tools — because the tool doesn't know the agent's intent."

Tool safety covers the practices for safely invoking external tools,
APIs, and system commands. A tool does exactly what it's told, with
no understanding of the agent's broader intent. This means the agent
bears full responsibility for validating inputs, checking
preconditions, and handling errors.

Key principles: validate paths before file operations, check state
before destructive commands, prefer targeted operations over broad
ones, and never chain tools in ways that amplify risk (e.g., piping
unvalidated output from one tool as input to a destructive command).
[[least-privilege]] applies at the tool level too — request only the
permissions each tool invocation actually needs.

See also: [[least-privilege]], [[scope-limitation]],
[[irreversible-action-check]], [[privilege-escalation]]
