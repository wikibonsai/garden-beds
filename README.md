# garden-beds

[![A WikiBonsai Project](https://img.shields.io/badge/%F0%9F%8E%8B-A%20WikiBonsai%20Project-brightgreen)](https://github.com/wikibonsai/wikibonsai)

A collection of starter knowledge bases for [WikiBonsai](https://github.com/wikibonsai/wikibonsai).

## Getting Started

### Via tendr-cli (recommended)

```
tendr init
```

Select a starter knowledge base from the list when prompted.

### Manual

1. Clone this repo:

```
git clone git@github.com:wikibonsai/garden-beds.git
```

2. Select a folder from this project and copy/paste it into the target location for note-taking.

3. Open the copy/pasted folder in [vscode-tendr](https://github.com/wikibonsai/vscode-tendr) or [tendr-cli](https://github.com/wikibonsai/tendr-cli) and start note-taking!

## Contributing a Starter Knowledge Base

To add a new starter knowledge base:

1. Create a new directory at the root of this repo (starters are FLAT — agent-specific starters use an `_agent-` name prefix, e.g. `_agent-guardrails/`; the `audience` field in `init.toml` is what marks them agent-facing).
2. Add an `init.toml` file describing the starter:

```toml
name        = "my-starter"
description = "A short description of what this knowledge base covers"
audience    = "user"       # "user" | "agent" | "both"
license     = "MIT"        # license for the content
```

3. Add your knowledge base files: `config.toml`, `t.doc.toml`, `t.attr.toml`, index files, and entries.
4. Add an entry to `registry.toml` at the repo root.
5. Open a pull request.
