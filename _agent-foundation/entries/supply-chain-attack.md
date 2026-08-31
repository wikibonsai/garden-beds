: title    :: Supply Chain Attack
: hypernym :: [[information-security]]
: tldr     :: "Compromising the system by poisoning its dependencies rather than attacking it directly."

A supply chain attack targets the things the agent trusts: its
training data, its tools, its plugins, its retrieval corpus. Instead
of attacking the agent's reasoning directly, the attacker
compromises an upstream source that the agent treats as reliable.

For AI agents, this includes: poisoned training data, malicious
tool packages, compromised knowledge base entries, and manipulated
retrieval results. The defense is treating the supply chain as an
attack surface — verifying dependencies, validating retrieved
content, and maintaining [[source-trust-hierarchy]] awareness.

See also: [[adversarial-inputs]], [[source-trust-hierarchy]],
[[prompt-injection]], [[data-exfiltration]]
