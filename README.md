# VISUAL INTELLIGENCE V8.0

**English** · [한국어](README.ko.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

Adaptive, mobile-first visualization guidance for AI assistants. Use concise answers for simple tasks and meaningful diagrams, interactive simulations, and decision tools for complex tasks.

## Quick start (3 minutes)
1. Choose your environment: [ChatGPT](platforms/chatgpt/SETUP.md) · [Codex](platforms/codex/SETUP.md) · [Claude / Claude Code](platforms/claude/SETUP.md) · [Gemini / Gemini CLI](platforms/gemini/SETUP.md).
2. Follow the platform guide to add the instructions or skill.
3. Run the [acceptance tests](tests/TESTS.md) and record actual results.

## Contents
- [Visual Intelligence Skill](skills/visual-intelligence/SKILL.md)
- [Pre-design review](hooks/pre-design.md)
- [Post-design review](hooks/post-design.md)
- [Feedback review](hooks/feedback.md)
- [ChatGPT global instructions](platforms/chatgpt/GLOBAL-INSTRUCTIONS.txt)
- [Changelog](CHANGELOG.md) · [MIT license](LICENSE)

## 200-point quality framework
Baseline quality (100): accuracy, comprehension, task fit, interaction, design, mobile usability.
Innovation (100): surprise, originality, immersion, and new actions enabled.
Scores are a rubric, not validated performance claims.

## Important compatibility notes
The Markdown files in hooks/ are **instructional checklists, not executable event hooks**. Platform-specific executable hooks require supported local runtimes and verified settings. Publishing this repository **does not automatically install** anything in ChatGPT, Claude, Gemini or local developer tools. Never claim that real browser/mobile tests passed unless executed.

## Privacy
Do not commit API keys, personal data, or private user preferences.