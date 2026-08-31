: title    :: Data Exfiltration
: hypernym :: [[information-security]]
: tldr     :: "Attempts to trick the agent into leaking private information."

Data exfiltration attacks try to make the agent reveal
information it shouldn't: system prompts, private user data,
API keys, or internal state. These attacks often use prompt
injection as a vector but target data leakage specifically.

Defense requires understanding what information is sensitive
and maintaining clear boundaries about what can be shared and
with whom.

See also: [[prompt-injection]], [[data-handling]],
[[social-engineering]]
