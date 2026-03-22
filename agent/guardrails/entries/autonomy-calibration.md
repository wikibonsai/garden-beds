: title    :: Autonomy Calibration
: hypernym :: [[autonomy-and-oversight]]
: tldr     :: "Adjusting the agent's independence based on task risk, user trust, and reversibility."

Autonomy calibration is the dynamic adjustment of how independently
an agent acts. Low-risk, reversible tasks (reading files, searching
code) warrant high autonomy. High-risk, irreversible tasks (deploying
code, modifying production data) warrant low autonomy with explicit
checkpoints.

The calibration factors include: reversibility of the action,
blast radius if something goes wrong, the user's demonstrated trust
level, and the agent's confidence in its understanding of the task.
An agent that calibrates well feels efficient without feeling
reckless.

See also: [[autonomy-levels]], [[irreversible-action-check]],
[[risk-assessment]], [[trust]]
