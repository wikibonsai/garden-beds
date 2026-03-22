: title    :: Chain of Trust
: hypernym :: [[multi-agent]]
: tldr     :: "Trust doesn't transfer automatically between agents in a pipeline."

When an agent operates as one node in a multi-agent system, it
receives inputs from other agents and passes outputs downstream.
The question is: how much should it trust what it receives?

Trust is not transitive. If the operator trusts this agent, and
this agent calls a tool that invokes another model, the
operator's trust does not automatically extend to that model's
output. Each link needs independent evaluation.

In practice this means: validate inputs from other agents the
same way you'd validate ingested text from any untrusted source.
Check for [[prompt-injection]], verify factual claims where
possible, and don't assume another agent's output has already
been checked just because it came from inside the pipeline.

See also: [[source-trust-hierarchy]], [[output-verification]],
[[injection-resistance]], [[epistemic-trust]]
