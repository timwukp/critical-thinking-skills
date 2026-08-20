# Argument Analysis Method

Argument analysis is the core critical thinking skill: systematically reconstructing, evaluating, and improving reasoning. Attend to both formal logic (reasoning structure) and material logic (premise truth).

For deep-critique mode (genealogical, perspectival, and value analysis), see `references/nietzsche.md`.

---

## Step 1: Argument Reconstruction

**Objective**: Transform the natural-language argument into standard form.

1. Identify the conclusion (what is being claimed?)
2. Extract premises (on what grounds?)
3. Mark implicit assumptions (unstated but necessary presuppositions)
4. Specify the reasoning type (deductive, inductive, analogical, etc.)

**Output format**:
```
Premise 1: [statement]
Premise 2: [statement]
Implicit assumption: [statement]
─────────────────
Conclusion: [statement]
Reasoning type: [deductive / inductive / analogical]
```

---

## Step 2: Premise Evaluation

Evaluate each premise on three dimensions:

1. **Truth** — is the premise true?
   - Check empirical evidence
   - Verify source credibility
   - Flag controversial claims

2. **Acceptability** — is the premise reasonably acceptable?
   - Check consistency with established knowledge
   - Check whether it presupposes a contested viewpoint
   - Consider alternative premises

3. **Relevance** — does the premise bear on the conclusion?
   - Detect red herrings
   - Identify emotional manipulation
   - Assess how directly the evidence supports the claim

---

## Step 3: Validity Check

**Deductive reasoning** — check formal validity (if the premises are true, must the conclusion be true?).
Common fallacies: affirming the consequent, denying the antecedent, four-term fallacy.

**Inductive reasoning** — evaluate sample representativeness and inductive strength.
Common fallacies: hasty generalization, cherry-picked evidence.

**Analogical reasoning** — assess whether the similarities are relevant and whether critical differences break the analogy.
Common fallacy: weak analogy.

For definitions, examples, and fixes, see `templates/fallacy-reference.md`.

---

## Step 4: Counterexample Testing

1. Construct scenarios where the premises are true but the conclusion is false
2. Probe boundary cases that strain the reasoning
3. Test robustness: does the argument hold across all plausible scenarios, or only under favorable conditions?

**Question bank**:
- Under what circumstances are the premises true but the conclusion false?
- Is this reasoning valid in all scenarios, or only some?
- What counterexamples most directly challenge this argument?

---

## Step 5: Improvement Suggestions

Critique should end constructively. Strategies:

1. Strengthen weak premises (supply additional evidence)
2. Qualify overly broad conclusions (add limiting conditions)
3. Make implicit assumptions explicit and testable
4. Offer alternative argumentative paths to the same (or a better-supported) conclusion

---

## Output Template

```markdown
## Argument Analysis Report

### Reconstructed Argument
[standard form]

### Premise Evaluation
- Premise 1: [evaluation + evidence quality]
- Premise 2: [evaluation + evidence quality]
- Implicit assumption: [evaluation + contestability]

### Reasoning Validity
- Reasoning type: [type]
- Validity assessment: [valid/invalid + reason]
- Detected fallacies: [if any]

### Counterexamples and Boundary Conditions
[relevant counterexamples or limitations]

### Perspective Analysis (deep-critique mode only — see references/nietzsche.md)
- Argument perspective: [from which standpoint?]
- Presupposed values: [hidden value judgments]
- Power dynamics: [whose interests does it serve?]

### Overall Assessment
[argument strength: strong/medium/weak + reason]

### Improvement Suggestions
[concrete strengthening strategies + alternative arguments]
```

Write the report in the user's language.
