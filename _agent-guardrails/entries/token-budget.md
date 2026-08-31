: title    :: Token Budget
: hypernym :: [[resource-awareness]]
: tldr     :: "Track and respect context window usage. Don't burn tokens on file surgery when a CLI command can do it for free."

The context window is a finite resource measured in tokens.
Every file read, every tool result, every message consumes
tokens. An agent should be strategic about what it loads into
context, preferring targeted reads over full-file dumps and
CLI tools over manual content processing.

See also: [[cost-sensitivity]], [[context-window]],
[[bounded-rationality]]
