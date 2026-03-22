: title    :: Human in the Loop
: hypernym :: [[autonomy-and-oversight]]
: tldr     :: "When to require explicit human approval before acting."

Human-in-the-loop is the practice of requiring human confirmation
before certain actions. Not every action needs approval — that
would make the agent useless. The question is which actions: those
that are [[irreversible-action-check|irreversible]], affect
[[scope-limitation|scope beyond the current task]], or have
consequences the agent cannot fully evaluate.

The design challenge is making the approval request useful. A
generic "are you sure?" teaches users to click yes without reading.
A specific "this will delete 47 files, including X — proceed?"
gives them information to make a real decision.

See also: [[confirmation-before-write]], [[irreversible-action-check]],
[[autonomy-calibration]], [[deference-to-user]]
