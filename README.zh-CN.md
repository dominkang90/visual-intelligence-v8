# HAEON Response OS V9 — release candidate

**AI-led minimal-touch setup:** give your AI this request:

> Read AI-SETUP.md on the v9-ai-setup branch of https://github.com/dominkang90/visual-intelligence-v8 and install and verify the skill for my environment with minimal manual steps.

[AI setup protocol](AI-SETUP.md) reuses the existing V8.1 skill. Automatic installation depends on actual host permissions; ChatGPT, Claude chat and Gemini may require a manual settings action. End-to-end platform tests remain pending. Existing V8.1 documentation and V8.0 visual examples follow.

---

<div align="center">

[한국어](README.ko.md) · [English](README.md) · [日本語](README.ja.md) · **简体中文**

<a href="https://dominkang90.github.io/visual-intelligence-v8/zh-CN/"><img src="assets/readme/zh-CN/00.png" alt="VISUAL INTELLIGENCE V8.0 封面：让 AI 回答从读信息变成理解并做决定" width="100%" /></a>

[**▶ 以翻页杂志打开**](https://dominkang90.github.io/visual-intelligence-v8/zh-CN/) · [**三分钟入门**](#quick-start) · [**核心技能**](skills/visual-intelligence/SKILL.md) · [**测试场景**](tests/TESTS.md)

</div>

<br />

<img src="assets/readme/zh-CN/01.png" alt="01 结论：比起好看的画面，更重视理解速度与决策质量" width="100%" />

<img src="assets/readme/zh-CN/02.png" alt="02 对比：同样的信息，更快理解" width="100%" />

<img src="assets/readme/zh-CN/03.png" alt="03 流程：从一个问题到下一步行动" width="100%" />

<details>
<summary>以文本（Mermaid）查看流程</summary>

```mermaid
flowchart TB
    A["用户提问"] --> B{"哪种表达最有帮助？"}
    B -->|"简单信息"| C["简洁回答"]
    B -->|"比较·选择"| D["对比表·决策工具"]
    B -->|"流程·结构"| E["流程图·结构图"]
    B -->|"场景探索"| F["交互式模拟*"]
    C --> G["准确性·可用性审查"]
    D --> G
    E --> G
    F --> G
    G --> H["可执行的下一步"]
```

</details>

<a id="quick-start"></a>

<img src="assets/readme/zh-CN/04.png" alt="04 三步开始" width="100%" />

| 环境 | 配置方法 |
| :--- | :--- |
| ChatGPT | [自定义指令](platforms/chatgpt/SETUP.md) |
| Codex | [技能配置](platforms/codex/SETUP.md) |
| Claude / Claude Code | [配置指南](platforms/claude/SETUP.md) |
| Gemini / Gemini CLI | [配置指南](platforms/gemini/SETUP.md) |

**第一个验证问题**

```text
用初学者也能看懂的架构图
解释 MCP 和 AI 智能体的关系。
```

<img src="assets/readme/zh-CN/05.png" alt="05 仓库里有什么" width="100%" />

[`skills/visual-intelligence/SKILL.md`](skills/visual-intelligence/SKILL.md) 核心技能 · [`hooks/pre-design.md`](hooks/pre-design.md) 设计前检查 · [`hooks/post-design.md`](hooks/post-design.md) 设计后检查 · [`hooks/feedback.md`](hooks/feedback.md) 反馈分析 · [`platforms/`](platforms/) 各平台指南 · [`tests/TESTS.md`](tests/TESTS.md) 测试场景

<img src="assets/readme/zh-CN/06.png" alt="06 质量标准：100 分 + 100 分" width="100%" />

<img src="assets/readme/zh-CN/07.png" alt="07 现在能做的和还不能做的" width="100%" />

<img src="assets/readme/zh-CN/08.png" alt="08 配置后亲自运行的 6 个场景" width="100%" />

<p align="right"><a href="tests/TESTS.md"><b>打开测试场景 →</b></a></p>

---

<div align="center">

**快速链接** · [核心技能](skills/visual-intelligence/SKILL.md) · [设计前检查](hooks/pre-design.md) · [设计后检查](hooks/post-design.md) · [反馈分析](hooks/feedback.md) · [ChatGPT 指令](platforms/chatgpt/GLOBAL-INSTRUCTIONS.txt) · [变更记录](CHANGELOG.md) · [MIT 许可证](LICENSE)

<sub>README 中的图片是同内容杂志页面的截图。卡片点击、复制、清单等交互请在杂志中使用。</sub>

<sub>VISUAL INTELLIGENCE V8.0 · 理解胜于装饰，行动胜于解释。</sub>

[한국어](README.ko.md) · [English](README.md) · [日本語](README.ja.md) · **简体中文**

</div>
