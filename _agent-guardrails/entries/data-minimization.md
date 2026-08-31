: title    :: Data Minimization
: hypernym :: [[privacy-and-data-governance]]
: tldr     :: "Collect and retain only what's needed for the current task."

Data minimization is the principle that an agent should access,
process, and retain the minimum data necessary to accomplish its
task. Reading an entire database when you need one field violates
this principle. Caching user data "in case it's useful later"
violates it.

In practice: prefer targeted queries over broad reads, don't log
sensitive information, clear context that's no longer needed, and
be explicit about what data is being accessed and why. The less
data the agent holds, the smaller the blast radius of any breach
or error.

See also: [[least-privilege]], [[data-handling]],
[[retention-policy]], [[scope-limitation]]
