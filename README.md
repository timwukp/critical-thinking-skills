# 批判性思辨 Agent Skill | Critical Thinking Agent Skill

## 簡介 | Introduction

**中文**：這是一個賦予 AI 代理人系統性批判思考能力的 Agent Skill:論證分析、偏見偵測、假設映射、證據評估、謬誤識別與紅隊分析。另提供可選的「深度批判模式」,整合尼采哲學方法論(譜系學批判、視角主義、價值重估)。

**English**: An Agent Skill that gives AI agents systematic critical thinking capabilities: argument analysis, bias detection, assumption mapping, evidence evaluation, fallacy detection, and red-team analysis. An optional "deep-critique mode" integrates Nietzschean methodology (genealogical critique, perspectivism, value revaluation).

**注意 | Note**:給 agent 讀的指令檔(`SKILL.md`、`methods/`、`templates/`、`references/`)為英文,以節省 context token;agent 會以使用者的語言回覆。本 README 為雙語,供人閱讀。
Agent-facing files (`SKILL.md`, `methods/`, `templates/`, `references/`) are in English to keep context tokens lean; the agent always replies in the user's language. This README is bilingual for human readers.

---

## 特點 | Features

- ✅ 完整的批判性思維方法(論證分析、偏見偵測、假設映射、證據評估)| Complete critical thinking methods (argument analysis, bias detection, assumption mapping, evidence evaluation)
- ✅ 謬誤參考手冊與快速檢查清單 | Fallacy reference handbook and quick reasoning checklist
- ✅ 內建工作流程(標準批判性探究、紅隊分析)| Built-in workflows (standard critical inquiry, red-team analysis)
- ✅ 可選的尼采式深度批判模式 | Optional Nietzschean deep-critique mode
- ✅ 漸進式載入架構(依任務按需讀取方法檔)| Progressive-disclosure architecture (method files loaded on demand)

---

## 安裝 | Installation

**中文**:將本 repo 複製到 Claude Code 的 skills 目錄:

**English**: Clone this repo into Claude Code's skills directory:

```bash
git clone https://github.com/timwukp/critical-thinking-skills ~/.claude/skills/critical-thinking
```

(專案層級則放到 `<project>/.claude/skills/critical-thinking`。| For project-level installation, use `<project>/.claude/skills/critical-thinking`.)

---

## 使用 | Usage

### 基本使用 | Basic Usage

**中文觸發詞 | Chinese triggers**:
- 「分析這個論證」
- 「找出偏見」
- 「紅隊這個計劃」
- 「質疑這個假設」
- 「證據充分嗎」

**English triggers**:
- "Analyze this argument"
- "Identify biases"
- "Red team this plan"
- "Question this assumption"
- "Is the evidence sufficient"

### 深度批判模式 | Deep-Critique Mode

**中文**:當你明確要求「深度批判」或「哲學批判」,或議題涉及價值、道德、社會規範時,agent 會額外載入尼采方法論(`references/nietzsche.md`),進行譜系質問、視角分析與價值重估。技術性、事實性問題不會啟用此模式。

**English**: When you explicitly ask for a "philosophical critique" / "深度批判", or the topic centrally involves values, morality, or social norms, the agent additionally loads the Nietzschean methodology (`references/nietzsche.md`) for genealogical interrogation, perspective analysis, and value revaluation. It stays off for technical or factual questions.

---

## 目錄結構 | Directory Structure

```
critical-thinking-skills/
├── SKILL.md                        # 技能定義:觸發條件、工作流程、路由表 | Skill definition: triggers, workflows, routing
├── README.md                       # 本文件 | This file
├── methods/
│   ├── argument-analysis.md        # 論證分析方法 | Argument analysis
│   ├── bias-detection.md           # 偏見偵測方法 | Bias detection
│   ├── assumption-mapping.md       # 假設映射方法 | Assumption mapping
│   └── evidence-evaluation.md      # 證據評估方法 | Evidence evaluation
├── templates/
│   ├── fallacy-reference.md        # 謬誤參考手冊 | Fallacy reference handbook
│   └── reasoning-checklist.md      # 推理快速檢查清單 | Quick reasoning checklist
└── references/
    └── nietzsche.md                # 尼采方法論(深度批判模式)| Nietzschean methodology (deep-critique mode)
```

---

## 哲學出處 | Philosophical Sources

> **中文**:本專案引用尼采是**方法論借用**——取其分析工具(譜系學批判、視角主義、價值重估的思考框架),而非採納其哲學結論或世界觀。本 skill 不預設、不推廣、也不反對任何宗教或信仰立場;它是一個中性的思維分析工具,屬於學術與工程範疇。
>
> **English**: This project's use of Nietzsche is a **methodological borrowing** — adopting his analytical tools (genealogical critique, perspectivism, the framework of value revaluation), not his philosophical conclusions or worldview. This skill presupposes, promotes, and opposes no religion or belief system; it is a neutral reasoning tool, academic and technical in scope.

**中文**:深度批判模式的尼采方法論出處(詳見 `references/nietzsche.md`):

**English**: Sources for the Nietzschean methodology in deep-critique mode (see `references/nietzsche.md` for details):

1. **譜系學批判、主奴道德 | Genealogical critique; master/slave morality** — 《道德的譜系》(*On the Genealogy of Morals*, 1887);《善惡的彼岸》§260 (*Beyond Good and Evil* §260)
2. **視角主義 | Perspectivism** — 《善惡的彼岸》(*Beyond Good and Evil*, 1886);「沒有事實,只有解釋」出自遺稿(*Nachlass*,收錄於《權力意志》§481)
3. **重估一切價值 | Revaluation of all values** — 晚期著作:《偶像的黃昏》(*Twilight of the Idols*, 1889)、《敵基督者》(*The Antichrist*)、《瞧,這個人》(*Ecce Homo*)
4. **永恆輪迴 | Eternal recurrence** — 《快樂的科學》§341 (*The Gay Science* §341)、《查拉圖斯特拉如是說》(*Thus Spoke Zarathustra*, 1883–1885)

**《權力意志》注意事項 | Note on *The Will to Power***:此書非尼采本人著作,而是其妹 Elisabeth Förster-Nietzsche 編纂的遺稿集,編輯方式廣受爭議,引用時應標注為遺稿(*Nachlass*)材料。
Not a book Nietzsche wrote — a posthumous compilation by his sister Elisabeth Förster-Nietzsche whose editing is widely regarded as distorting; cite as *Nachlass* material.

---

## 貢獻 | Contributing

**中文**:歡迎提交 Issue 和 Pull Request!

**English**: Issues and Pull Requests are welcome!

---

## 授權 | License

MIT License

---

## 致謝 | Acknowledgments

- **哲學基礎 | Philosophical foundation**:弗里德里希・尼采 Friedrich Nietzsche (1844–1900)
- **批判性思維方法 | Critical thinking methods**:學術文獻與批判思維教學實踐 | Academic literature and critical thinking pedagogy
- **技術框架 | Technical framework**:Anthropic Agent Skills 規範與社群最佳實踐 | Anthropic Agent Skills specification and community best practices
