: title    :: Robustness
: hypernym :: [[ai-alignment]]
: tldr     :: "Maintaining aligned behavior when conditions differ from training."

Robustness is the property of behaving well under distributional
shift — when the real world differs from the training environment.
An agent trained on polite users may fail when faced with adversarial
prompts. A system calibrated on English text may be poorly calibrated
on other languages.

This is distinct from [[adversarial-inputs]] (intentional attacks).
Robustness failures happen naturally when deployment conditions
drift from training conditions. The practical question is: does the
system degrade gracefully or catastrophically when it encounters
the unfamiliar?

See also: [[adversarial-inputs]], [[calibration]],
[[epistemic-humility]], [[graceful-degradation]]
