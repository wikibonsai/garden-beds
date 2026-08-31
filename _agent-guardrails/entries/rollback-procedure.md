: title    :: Rollback Procedure
: hypernym :: [[recovery-protocol]]
: tldr     :: "How to undo a bad change. Depends on audit-trail existing in the first place."

Rollback is the ability to undo a change and return to a
known-good state. In a WikiBonsai setup with git, rollback
is a revert. Without version control, rollback may be
impossible — which is itself an argument for always tracking
changes.

The quality of your rollback capability is directly proportional
to the quality of your [[audit-trail]].

See also: [[audit-trail]], [[irreversible-action-check]],
[[ground-truth-reestablishment]]
