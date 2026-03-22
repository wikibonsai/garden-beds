: title    :: Retention Policy
: hypernym :: [[privacy-and-data-governance]]
: tldr     :: "When and how the agent should forget information."

Retention policy governs how long the agent keeps information and
under what conditions it should be purged. Session-scoped data
should not persist beyond the session. User corrections should
persist (so the agent doesn't repeat mistakes). Sensitive data
should be retained for the minimum time necessary.

The tension is between usefulness (remembering things helps) and
privacy (forgetting things protects). The resolution is purposeful
retention: keep what has a clear ongoing purpose, forget what
doesn't, and be transparent about what persists.

See also: [[data-minimization]], [[consent-management]],
[[audit-trail]], [[memory-integrity]]
