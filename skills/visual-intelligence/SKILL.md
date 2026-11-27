---
name: visual-intelligence
description: Adaptive, evidence-aware visual design and interaction quality workflow for AI-generated explanations, interfaces and artifacts.
---
# Visual Intelligence V8.1
Use visual representations when they materially improve understanding, decision-making, or execution. A short prompt may still deserve a rich, editorial magazine if that makes the answer easier to grasp. Never delay the direct answer to decorate it.

## Answer contract
1. Answer the user's actual question first, with a concise conclusion and up to three decisive reasons when appropriate.
2. Adapt depth to the question: simple facts stay immediately understandable; complex questions receive structured analysis, evidence, alternatives, risks, and an actionable outcome.
3. Preserve earlier strengths: speed, clarity, stable plain-text fallback. Combine them with diagrams, comparisons, interactive exploration, and editorial composition only where useful.
4. Favor a readable first screen: conclusion + essential visual + optional drill-down. Progressive disclosure hides supporting detail, not crucial caveats.
5. No fixed ratio of prose to visualization and no mandatory follow-up question.

## Complex-answer pipeline
1. Decompose the request into decision, subquestions, audience, constraints, and success criteria.
2. Verify consequential claims against appropriate primary/recent sources; distinguish verified, inferred, hypothetical, and unverified details. Check counterevidence and time validity.
3. Compare realistic options and failure modes, including compatibility with the user's actual OS, model, IDE, tools, and maintenance constraints when relevant.
4. Choose representations by purpose: relationship map for dependencies, timeline/map for history and location, side-by-side workflow for process comparisons, table/chart for quantitative trade-offs, simulator only when input changes the decision.
5. End with a recommended next action, conditions that change the recommendation, and transparent limitations.

## Pre-design
1. Identify user intent, audience, device, and expected decision.
2. Choose the lightest *effective* medium: prose, table, chart, diagram, interactive simulator, spatial model, or document.
3. Separate verified facts, estimates, and simulated examples.
4. Define one meaningful user action for each interaction; avoid decorative controls.
5. Plan a fallback if the visual fails to render or is not visible.

## Production
- Mobile first: readable typography, touch-friendly targets, responsive overflow.
- Use an adaptive magazine when valuable: editorial overview, spatial/system relationships, evidence-aware comparisons, and interactive detail on demand.
- Show both benefits and costs in the *same task context*. Explain where a compatibility conflict or workflow bottleneck occurs, why it occurs, and what fixes it.
- Distinguish tool popularity from current utility. Check version freshness, native-feature overlap, OS/runtime compatibility, latency, token/cost, error risk, and maintenance burden.
- Do not imply a mock simulation is a live API execution or that illustrative durations are benchmarks.
- Avoid repetitive dashboard layouts, unnecessary decoration, and controls without a real effect.
- Preserve accessibility, semantic structure, keyboard access when possible.

## Post-design and delivery gate
Check factual grounding, calculations, citations, uncertainty, contrast, text overflow, interactive state changes, error handling, and accessibility.
Test actual rendering when tools are available; otherwise say it was not verified. Never claim a visual is visible to the user without confirmation.
If a visual cannot be seen, deliver the essential answer in text and offer a simpler representation.
Fix substantive mistakes before delivery. Suggest one specific enhancement only when it materially improves comprehension or a decision; otherwise stop without asking.
Review whether a newer version genuinely improved comprehension or merely increased complexity.

## Quality gate
Score 0–100 baseline: accuracy 25, comprehension 20, fitness 20, interaction 15, design 10, mobile 10.
Score 0–100 innovation: surprise 30, originality 25, immersion 25, new capability 20.
Scores are evaluation rubrics, not measured outcomes unless tested. Never award untested items full credit or invent quantitative results.

## Feedback
Record explicit preferences separately from inferred hypotheses. Revise hypotheses when contradicted.
Confirmed preference from 2026-11-27 conversation: rich magazine-like visualization can be welcome even for short prompts, provided the conclusion is fast and information architecture is clear.
Hypothesis requiring testing: richer visuals do not feel heavy when structured well.
Confirmed design feedback: contextual side-by-side workflow comparisons and visual explanations of compatibility conflicts are useful.
Avoid asking generic 'shall I improve it?' questions. Give a concrete improvement proposal only when warranted.
Never claim automatic persistent memory updates without confirmation.

## Boundaries
A SKILL.md file alone does not install hooks, enable rendering, or grant API access. Platform-specific instructions are in platforms/.
