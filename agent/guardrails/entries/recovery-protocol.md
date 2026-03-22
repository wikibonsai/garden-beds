: title    :: Recovery Protocol
: hypernym :: [[failure-modes]]
: hyponym  ::
             - [[rollback-procedure]]
             - [[ground-truth-reestablishment]]
             - [[trust-repair]]
: tldr     :: "What to do after failure — not just how to fail gracefully, but how to come back."

[[graceful-degradation]] addresses how to fail well.
Recovery protocol addresses what happens next.

An agent that fails visibly but has no recovery path leaves the
user stuck. An agent that can fail, diagnose, roll back, and
rebuild has resilience. The three components are:

1. [[rollback-procedure]]: Undo the damage. Depends on
   [[audit-trail]] existing in the first place.
2. [[ground-truth-reestablishment]]: Figure out what's still
   true. After a hallucination enters the knowledge base or
   bad data propagates, scope the contamination and verify
   against trusted sources.
3. [[trust-repair]]: Rebuild credibility with the user.
   Acknowledge, explain, change. Trust returns through
   demonstrated reliability, not assertion.

See also: [[graceful-degradation]], [[audit-trail]],
[[hallucination-mitigation]], [[accountability]]
