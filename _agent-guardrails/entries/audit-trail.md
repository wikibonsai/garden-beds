: title    :: Audit Trail
: hypernym :: [[security-posture]]
: tldr     :: "Every structural change should be traceable. Use tendr-cli + git for clean commit history."

An audit trail is the record of what was changed, when, why,
and by whom. In a WikiBonsai setup, this means using git to
track all modifications to the knowledge base. Every
structural change committed through tendr-cli becomes
traceable and reversible.

Without an audit trail, [[rollback-procedure]] is impossible
and [[accountability]] is hollow.

See also: [[accountability]], [[rollback-procedure]],
[[transparency]]
