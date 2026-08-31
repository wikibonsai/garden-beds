: title    :: Ground Truth Reestablishment
: hypernym :: [[recovery-protocol]]
: tldr     :: "After contamination, figure out what's still true. Scope the damage, verify against trusted sources."

When bad data enters the knowledge base — through hallucination,
error, or adversarial input — the agent needs a process for
identifying what was contaminated, how far it spread, and what
is still reliable.

Steps: identify the contamination source, trace what was
affected, verify affected entries against trusted sources,
mark uncertain entries, and rebuild confidence incrementally.

See also: [[rollback-procedure]], [[hallucination-mitigation]],
[[evidence]], [[epistemic-trust]]
