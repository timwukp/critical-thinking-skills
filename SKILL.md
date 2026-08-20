---
name: critical-thinking
description: Systematic critical thinking - argument analysis, bias detection, assumption mapping, evidence evaluation, logical fallacy detection, red-team analysis. Use when the user asks to analyze an argument, find biases or fallacies, question assumptions, evaluate evidence or claims, red-team a plan, find root causes, seek alternative explanations, or asks 分析論證、找出偏見、質疑假設、紅隊這個計劃、證據充分嗎、這個說法可靠嗎、根本原因是什麼、還有其他解釋嗎.
---

# Critical Thinking

Apply systematic critical thinking to arguments, claims, plans, and evidence. Always respond in the user's language, even though these instructions and the method files are in English.

## When to use

- **Decision evaluation** — analyze the reasoning quality of business, policy, or personal decisions
- **Argument audit** — review the logical rigor of academic, media, or professional discourse
- **Risk analysis / red-teaming** — identify vulnerabilities in plans, strategies, or systems
- **Information verification** — assess the credibility of news, research, or claims
- **Root cause analysis** — trace multi-layer causal chains behind problems
- **Perspective diversification** — generate and evaluate alternative explanatory frameworks

## When NOT to use

- Emergencies requiring rapid intuitive response
- Pure creative brainstorming (premature critique kills ideas)
- Routine decisions with established consensus
- Purely technical or procedural tasks with no contested claims

## Routing: which file to read

Read only the files relevant to the task at hand:

| Task | Read |
|------|------|
| Reconstruct and evaluate an argument's logic | `methods/argument-analysis.md` |
| Detect cognitive or systemic biases | `methods/bias-detection.md` |
| Surface and stress-test assumptions | `methods/assumption-mapping.md` |
| Judge the quality of evidence or a claim | `methods/evidence-evaluation.md` |
| Name or verify a specific logical fallacy | `templates/fallacy-reference.md` |
| Quick sanity check (lightweight, no full method needed) | `templates/reasoning-checklist.md` |
| Deep philosophical critique (see mode below) | `references/nietzsche.md` |

## Standard critical inquiry workflow

For a full analysis, work through these six steps. For narrower requests (e.g. "find the fallacy"), jump straight to the relevant method file.

1. **Clarify** — define key terms, identify the core claim, bound the question's scope.
2. **Gather** — identify relevant evidence, assess sources, flag information gaps.
3. **Surface assumptions** — extract implicit presuppositions, question their plausibility, consider alternatives (`methods/assumption-mapping.md`).
4. **Analyze reasoning** — reconstruct the inference chain, detect fallacies, rate inferential strength (`methods/argument-analysis.md`).
5. **Seek alternatives** — generate rival explanations, look for counterexamples, probe boundary conditions.
6. **Conclude** — state how strongly the evidence supports the conclusion, mark uncertainties explicitly, suggest what further inquiry would settle the question.

## Red-team workflow

When asked to red-team a plan, proposal, or argument:

1. **Understand the target** — restate the core claim, list its key assumptions, make the success criteria explicit.
2. **Attack systematically** — hit the most fragile assumption first; hunt counterexamples and edge cases; surface unanticipated risks; challenge evidence sufficiency.
3. **Build adversarial scenarios** — construct worst cases, trace cascade-failure paths, adopt an adversary's perspective, find single points of failure.
4. **Recommend** — propose concrete hardening measures, mitigation strategies, monitoring indicators; state the residual risk honestly.

## Deep-critique mode (optional)

Activate ONLY when (a) the user explicitly asks for deep or philosophical critique (e.g. "深度批判", "哲學批判", "philosophical critique"), or (b) the subject centrally involves values, morality, or social norms. Do NOT activate for technical, factual, or procedural questions — genealogical/power analysis degrades those answers.

When active, read `references/nietzsche.md` and add three layers to the standard workflow:
- **Genealogical interrogation** — where did this concept or norm historically come from, and who benefits from its acceptance?
- **Perspective analysis** — from which standpoint does the argument proceed, and what do rival perspectives reveal?
- **Value revaluation** — what values does the argument presuppose, and what alternatives exist? After critique, always propose a constructive alternative (critique that only destroys is incomplete).

## Quality bar

A successful analysis demonstrates:

- [ ] Clear reconstruction of the argument structure
- [ ] At least one key assumption identified and interrogated
- [ ] Relevant fallacies or reasoning flaws detected (if present)
- [ ] Evidence quality and sufficiency evaluated
- [ ] At least one alternative perspective or explanation offered
- [ ] Uncertainties and limitations explicitly acknowledged
- [ ] Concrete improvement suggestions or next inquiry steps

## Pitfalls to avoid

- **Analysis paralysis** — over-analysis that blocks action; match depth to stakes.
- **False balance** — do not manufacture "both sides" when the evidence is lopsided.
- **Cynical skepticism** — questioning for its own sake; every critique should end constructively.
- **Elitism** — critique targets ideas, never persons; respect the interlocutor's commitments and acknowledge the limits of your own perspective.
