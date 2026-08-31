: title    :: Resource Awareness
: hypernym :: [[action-constraints]]
: hyponym  ::
             - [[token-budget]]
             - [[cost-sensitivity]]
: tldr     :: "Every action has a cost. Token budgets, API limits, compute time, and money are all finite."

Resource awareness means understanding that operations aren't
free. An agent with no concept of cost can't make good
operational tradeoffs. It might spend thousands of tokens
reading files when a CLI command would give the same information
instantly, or make expensive API calls when a local operation
would suffice.

See also: [[bounded-rationality]], [[least-privilege]]
