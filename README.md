<div align="center">

[한국어](README.ko.md) · **English** · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

<a href="https://dominkang90.github.io/visual-intelligence-v8/en/"><img src="assets/readme/en/00.png" alt="VISUAL INTELLIGENCE V8.0 cover: make AI answers easier to understand, explore, and act on" width="100%" /></a>

[**▶ Open as a swipeable magazine**](https://dominkang90.github.io/visual-intelligence-v8/en/) · [**Get started**](#quick-start) · [**Explore the skill**](skills/visual-intelligence/SKILL.md) · [**Run acceptance checks**](tests/TESTS.md)

</div>

<br />

<img src="assets/readme/en/01.png" alt="01 Verdict: understanding and decisions over decoration" width="100%" />

<img src="assets/readme/en/02.png" alt="02 Before and after: from text overload to decision-ready answers" width="100%" />

<img src="assets/readme/en/03.png" alt="03 How it works: from one question to a clear next action" width="100%" />

<details>
<summary>View the flow as text (Mermaid)</summary>

```mermaid
flowchart TB
    A["User request"] --> B{"What helps most?"}
    B -->|"Simple fact"| C["Concise answer"]
    B -->|"Compare / decide"| D["Table or decision aid"]
    B -->|"Process / system"| E["Flow or structure"]
    B -->|"Explore scenarios"| F["Interactive simulation*"]
    C --> G["Accuracy + usability review"]
    D --> G
    E --> G
    F --> G
    G --> H["Clear next action"]
```

</details>

<a id="quick-start"></a>

<img src="assets/readme/en/04.png" alt="04 Quick start in 3 steps" width="100%" />

| Environment | Setup |
| :--- | :--- |
| ChatGPT | [Custom instructions](platforms/chatgpt/SETUP.md) |
| Codex | [Skill setup](platforms/codex/SETUP.md) |
| Claude / Claude Code | [Setup guide](platforms/claude/SETUP.md) |
| Gemini / Gemini CLI | [Setup guide](platforms/gemini/SETUP.md) |

**First test prompt**

```text
Explain how MCP and AI agents work together
using a beginner-friendly architecture diagram.
```

<img src="assets/readme/en/05.png" alt="05 What's in the repository" width="100%" />

[`skills/visual-intelligence/SKILL.md`](skills/visual-intelligence/SKILL.md) Core skill · [`hooks/pre-design.md`](hooks/pre-design.md) Pre-design review · [`hooks/post-design.md`](hooks/post-design.md) Post-design review · [`hooks/feedback.md`](hooks/feedback.md) Feedback review · [`platforms/`](platforms/) Platform guides · [`tests/TESTS.md`](tests/TESTS.md) Acceptance scenarios

<img src="assets/readme/en/06.png" alt="06 Quality framework: 100 + 100" width="100%" />

<img src="assets/readme/en/07.png" alt="07 Status and limitations" width="100%" />

<img src="assets/readme/en/08.png" alt="08 Six acceptance scenarios to run after setup" width="100%" />

<p align="right"><a href="tests/TESTS.md"><b>Open acceptance scenarios →</b></a></p>

---

<div align="center">

**Documentation** · [Core skill](skills/visual-intelligence/SKILL.md) · [Pre-design](hooks/pre-design.md) · [Post-design](hooks/post-design.md) · [Feedback](hooks/feedback.md) · [ChatGPT instructions](platforms/chatgpt/GLOBAL-INSTRUCTIONS.txt) · [Changelog](CHANGELOG.md) · [MIT license](LICENSE)

<sub>README images are captures of the magazine with the same content. Interactions (cards, copy, checklist) work in the magazine.</sub>

<sub>VISUAL INTELLIGENCE V8.0 · Clarity first. Interaction when it matters.</sub>

[한국어](README.ko.md) · **English** · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

</div>
