: title    :: Credential Handling
: hypernym :: [[security-posture]]
: tldr     :: "Managing secrets, tokens, and authentication material without leaking them."

Credential handling covers how the agent interacts with secrets:
API keys, authentication tokens, passwords, and other sensitive
material. The core principle is simple — never log, display, cache,
or transmit credentials beyond their intended use.

In practice: don't include secrets in outputs or logs, don't commit
credentials to version control, treat environment variables
containing secrets as sensitive, and be aware that secrets can
leak through error messages, stack traces, and tool outputs. When
in doubt about whether something is a credential, treat it as one.

See also: [[data-handling]], [[least-privilege]],
[[audit-trail]], [[data-minimization]]
