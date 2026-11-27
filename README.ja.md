<div align="center">

[한국어](README.ko.md) · [English](README.md) · **日本語** · [简体中文](README.zh-CN.md)

<a href="https://dominkang90.github.io/visual-intelligence-v8/ja/"><img src="assets/readme/ja/00.png" alt="VISUAL INTELLIGENCE V8.0 表紙：AIの回答を、読む情報から理解して判断できる体験へ" width="100%" /></a>

[**▶ めくれるマガジンで開く**](https://dominkang90.github.io/visual-intelligence-v8/ja/) · [**3分ではじめる**](#quick-start) · [**中核スキル**](skills/visual-intelligence/SKILL.md) · [**テストシナリオ**](tests/TESTS.md)

</div>

<br />

<img src="assets/readme/ja/01.png" alt="01 結論：見た目より理解の速さと判断の質" width="100%" />

<img src="assets/readme/ja/02.png" alt="02 比較：同じ情報を、より速く理解" width="100%" />

<img src="assets/readme/ja/03.png" alt="03 流れ：1つの質問が次の行動になるまで" width="100%" />

<details>
<summary>流れをテキスト（Mermaid）で見る</summary>

```mermaid
flowchart TB
    A["ユーザーの質問"] --> B{"どの表現が役立つか？"}
    B -->|"簡単な情報"| C["簡潔な回答"]
    B -->|"比較・選択"| D["比較表・判断ツール"]
    B -->|"手順・構造"| E["フロー図・構成図"]
    B -->|"シナリオ探索"| F["インタラクティブシミュレーション*"]
    C --> G["正確性・使いやすさのレビュー"]
    D --> G
    E --> G
    F --> G
    G --> H["実行できる次の行動"]
```

</details>

<a id="quick-start"></a>

<img src="assets/readme/ja/04.png" alt="04 3ステップではじめる" width="100%" />

| 環境 | 設定方法 |
| :--- | :--- |
| ChatGPT | [カスタム指示の設定](platforms/chatgpt/SETUP.md) |
| Codex | [スキルの設定](platforms/codex/SETUP.md) |
| Claude / Claude Code | [環境別の設定](platforms/claude/SETUP.md) |
| Gemini / Gemini CLI | [環境別の設定](platforms/gemini/SETUP.md) |

**最初の確認用の質問**

```text
MCPとAIエージェントの関係を
初心者にもわかる構成図で説明して。
```

<img src="assets/readme/ja/05.png" alt="05 リポジトリの中身" width="100%" />

[`skills/visual-intelligence/SKILL.md`](skills/visual-intelligence/SKILL.md) 中核スキル · [`hooks/pre-design.md`](hooks/pre-design.md) 設計前チェック · [`hooks/post-design.md`](hooks/post-design.md) 設計後チェック · [`hooks/feedback.md`](hooks/feedback.md) フィードバック分析 · [`platforms/`](platforms/) プラットフォーム別ガイド · [`tests/TESTS.md`](tests/TESTS.md) テストシナリオ

<img src="assets/readme/ja/06.png" alt="06 品質基準：100点 + 100点" width="100%" />

<img src="assets/readme/ja/07.png" alt="07 今できることとまだできないこと" width="100%" />

<img src="assets/readme/ja/08.png" alt="08 設定後に試す6つのシナリオ" width="100%" />

<p align="right"><a href="tests/TESTS.md"><b>テストシナリオを開く →</b></a></p>

---

<div align="center">

**リンク** · [中核スキル](skills/visual-intelligence/SKILL.md) · [設計前チェック](hooks/pre-design.md) · [設計後チェック](hooks/post-design.md) · [フィードバック](hooks/feedback.md) · [ChatGPT指示](platforms/chatgpt/GLOBAL-INSTRUCTIONS.txt) · [変更履歴](CHANGELOG.md) · [MITライセンス](LICENSE)

<sub>READMEの画像は同じ内容のマガジン画面をキャプチャしたものです。カード操作・コピー・チェックリストはマガジンで使えます。</sub>

<sub>VISUAL INTELLIGENCE V8.0 · 装飾より理解、説明より実行。</sub>

[한국어](README.ko.md) · [English](README.md) · **日本語** · [简体中文](README.zh-CN.md)

</div>
