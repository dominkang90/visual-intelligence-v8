# Post-design review (instructional protocol)
- Is the direct answer obvious without interacting with the visual?
- Validate claims, numbers, citations, links, freshness, and uncertainty. Separate verified facts from simulated values.
- Inspect mobile widths and touch targets if a browser is available.
- Exercise every button and state transition where test tools exist.
- Check contrast, keyboard support, overflow, and text-only fallback.
- Do not assert that a rendered visual was seen by the user; if visibility is unknown, make the spoken/text answer self-contained.
- For comparisons, are trade-offs tied to task context and explained at their point of impact?
- For complex answers, are alternatives, failure modes, counterevidence, and a practical next action present?
- Compare against the simpler prior approach: did this actually reduce effort or just add UI?
- Fix major defects before delivery. Offer a single specific enhancement only when materially useful; avoid repetitive closing questions.
- Report what was tested and what was not.

This file does not automatically run tests.
