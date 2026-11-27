<div align="center">

**한국어** · [English](README.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

<a href="https://dominkang90.github.io/visual-intelligence-v8/ko/"><img src="assets/readme/ko/00.png" alt="VISUAL INTELLIGENCE V8.0 표지: AI 답변을 읽는 정보에서 이해하고 판단하는 경험으로" width="100%" /></a>

[**▶ 넘겨 보는 매거진으로 열기**](https://dominkang90.github.io/visual-intelligence-v8/ko/) · [**3분 시작하기**](#quick-start) · [**핵심 스킬**](skills/visual-intelligence/SKILL.md) · [**검수 시나리오**](tests/TESTS.md)

</div>

<br />

<img src="assets/readme/ko/01.png" alt="01 결론: 예쁜 화면보다 이해 속도와 판단 품질" width="100%" />

<img src="assets/readme/ko/02.png" alt="02 전후 비교: 같은 정보, 더 빠른 이해" width="100%" />

<img src="assets/readme/ko/03.png" alt="03 작동 흐름: 질문 하나가 다음 행동이 되기까지" width="100%" />

<details>
<summary>작동 흐름을 텍스트(Mermaid)로 보기</summary>

```mermaid
flowchart TB
    A["사용자 질문"] --> B{"어떤 표현이 유용한가?"}
    B -->|"간단한 정보"| C["간결한 답변"]
    B -->|"비교·선택"| D["비교표·판단 도구"]
    B -->|"절차·구조"| E["흐름도·구조도"]
    B -->|"시나리오 탐색"| F["인터랙티브 시뮬레이션*"]
    C --> G["정확성·사용성 검수"]
    D --> G
    E --> G
    F --> G
    G --> H["실행할 다음 행동"]
```

</details>

<a id="quick-start"></a>

<img src="assets/readme/ko/04.png" alt="04 시작하기: 3단계" width="100%" />

| 환경 | 적용 방법 |
| :--- | :--- |
| ChatGPT | [맞춤 지침 설정](platforms/chatgpt/SETUP.md) |
| Codex | [스킬 설정](platforms/codex/SETUP.md) |
| Claude / Claude Code | [환경별 설정](platforms/claude/SETUP.md) |
| Gemini / Gemini CLI | [환경별 설정](platforms/gemini/SETUP.md) |

**첫 답변 검증용 질문**

```text
MCP와 AI 에이전트의 관계를
초보자도 이해할 수 있는 구조도로 설명해줘.
```

<img src="assets/readme/ko/05.png" alt="05 저장소 구성" width="100%" />

[`skills/visual-intelligence/SKILL.md`](skills/visual-intelligence/SKILL.md) 핵심 스킬 · [`hooks/pre-design.md`](hooks/pre-design.md) 제작 전 검수 · [`hooks/post-design.md`](hooks/post-design.md) 제작 후 검수 · [`hooks/feedback.md`](hooks/feedback.md) 피드백 분석 · [`platforms/`](platforms/) 플랫폼별 안내 · [`tests/TESTS.md`](tests/TESTS.md) 검수 시나리오

<img src="assets/readme/ko/06.png" alt="06 품질 기준: 100점 + 100점" width="100%" />

<img src="assets/readme/ko/07.png" alt="07 현재 구현 범위" width="100%" />

<img src="assets/readme/ko/08.png" alt="08 설치 후 돌려 볼 6가지 검수 시나리오" width="100%" />

<p align="right"><a href="tests/TESTS.md"><b>검수 시나리오 열기 →</b></a></p>

---

<div align="center">

**바로가기** · [핵심 스킬](skills/visual-intelligence/SKILL.md) · [제작 전 검수](hooks/pre-design.md) · [제작 후 검수](hooks/post-design.md) · [피드백 분석](hooks/feedback.md) · [ChatGPT 지침](platforms/chatgpt/GLOBAL-INSTRUCTIONS.txt) · [변경 이력](CHANGELOG.md) · [MIT 라이선스](LICENSE)

<sub>README 그림은 같은 내용의 매거진 화면을 캡처한 것입니다. 상호작용(카드 누르기, 복사, 체크리스트)은 매거진에서 됩니다.</sub>

<sub>VISUAL INTELLIGENCE V8.0 · 장식보다 이해, 설명보다 실행.</sub>

**한국어** · [English](README.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

</div>
