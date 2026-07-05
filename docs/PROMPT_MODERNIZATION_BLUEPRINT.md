# Speak to AI Prompt Modernization Blueprint

This blueprint explains how to revise a prompt without destroying the parts that make the prompt work.

The goal is not prettier language. The goal is better execution.

A prompt may contain operational machinery: role instructions, source limits, step order, output format, protected definitions, examples, validation rules, and review checks. When AI rewrites a prompt, it often smooths the language but accidentally removes that machinery.

Speak to AI modernization prevents that failure.

---

## Operating Philosophy

Use the smallest prompt that reliably preserves intent.

A prompt should be as short as practical, but never shorter than functional.

Clarity matters. Brevity matters. Reliability matters more than both.

A prompt that sounds elegant but loses control over the output has failed.

---

## What Modernization Means

Modernization means improving clarity, usability, portability, and reliability while preserving the instructions that make the prompt execute correctly.

Modernization does not mean:

- deleting source rules,
- removing safeguards,
- flattening output structure,
- changing the user’s intent,
- replacing specific commands with vague summaries,
- or making specialized prompts generic.

---

## Protected Prompt Mechanics

During modernization, do not silently remove or weaken these parts:

1. Role instructions.
2. Task instructions.
3. Input placeholders.
4. Output format.
5. Required headings.
6. Tables or schemas.
7. Citation rules.
8. Source restrictions.
9. Confidentiality limits.
10. Legal, ethical, or safety warnings.
11. Step-by-step sequence.
12. Validation checklist.
13. Examples.
14. Definitions.
15. Local rules or jurisdiction requirements.
16. Command behavior.
17. File or document load order.
18. Version history.
19. Required assumptions.
20. Known exclusions.
21. Review standards.
22. Escalation rules.
23. Attorney-review requirements.
24. Human-approval gates.
25. Final quality-control checks.

---

## 11S Modernization Pass

When modernizing a prompt, review it through each 11S layer.

### 1. Structure

Preserve the organization of the intended output.

Ask: What shape should the final answer take?

### 2. Schema

Preserve required fields, labels, placeholders, tables, JSON structures, or outline levels.

Ask: What exact sections or fields must appear?

### 3. Syntax

Improve wording without changing command meaning.

Ask: Are the instructions written clearly enough for the AI to follow?

### 4. Semantics

Preserve the meaning of key terms.

Ask: What do the important words mean here?

### 5. Specificity

Increase useful detail without inventing facts.

Ask: What concrete information does the AI need?

### 6. Scope

Control what the AI should and should not do.

Ask: How far should the AI go?

### 7. Source

Preserve source rules and verification requirements.

Ask: Where should the answer come from?

### 8. Safeguards

Preserve safety, accuracy, confidentiality, and quality controls.

Ask: What mistakes must the prompt prevent?

### 9. Style

Preserve the intended voice and audience fit.

Ask: How should the response sound?

### 10. Sequence

Preserve the order of operations.

Ask: What should the AI do first, second, third, and last?

### 11. Stress Test

Require final self-checking before the answer is presented.

Ask: Would this output survive review by a careful human?

---

## Humanizing Text Layer

Use this layer only when the prompt owner asks for a more natural, persuasive, reader-friendly, or less mechanical version of the output.

Humanizing does not mean adding theatrical language.

Humanizing means making the text easier for a real person to read while preserving truth, structure, source limits, safeguards, and operational function.

Allowed rhetorical modes are limited to:

1. Plain explanation with no rhetorical device.
2. Praeteritio.
3. Distinctio.
4. Irony through euphemism.

No other rhetorical device should be intentionally added unless the prompt owner expressly authorizes it.

### Plain Explanation

Plain explanation states the point directly without decorative phrasing.

Use it for most of the text.

### Praeteritio

Praeteritio means mentioning a point by saying you will not dwell on it.

Example:

> I will not belabor the obvious risk: a prompt that sounds cleaner but loses its source rules has not been improved.

Use praeteritio sparingly. Do not use it to smuggle in unsupported accusations.

### Distinctio

Distinctio clarifies the meaning of a word or concept by distinguishing it from nearby ideas.

Example:

> Modernization means improving clarity and reliability. It does not mean deleting the command structure that made the prompt work.

Distinctio is preferred when a term could be misunderstood.

### Irony Through Euphemism

Irony through euphemism uses mild, understated language to describe a serious flaw.

Example:

> A prompt that invents cases with confidence has created a small professional-development opportunity for everyone involved.

Use it carefully. Do not use it when the subject involves trauma, disability, death, protected-class issues, medical facts, criminal allegations, child-related facts, or other sensitive material.

---

## Humanizing Instruction

```text
Revise the text for a more natural human reader while preserving meaning, structure, source limits, safeguards, citations, record support, and output requirements. Use only plain explanation, praeteritio, distinctio, and irony through euphemism. Do not intentionally add any other rhetorical device. If a sentence works best without a rhetorical device, leave it plain. Remove mechanical phrasing, repetitive sentence patterns, generic transitions, filler language, and predictable paragraph rhythm. Vary sentence and paragraph length naturally, but do not add facts, soften legal risk, obscure uncertainty, alter defined terms, or weaken required safeguards.
```

---

## Modernization Sequence

When asked to revise, improve, convert, or modernize a prompt, follow this order:

1. Identify the prompt’s actual purpose.
2. Identify the intended user and audience.
3. Identify the required output.
4. Identify the operational mechanics that must be preserved.
5. Identify missing information.
6. Identify weak assumptions.
7. Identify source-control needs.
8. Identify safeguards.
9. Rebuild the prompt using the 11S structure.
10. Preserve specialized instructions unless they conflict with safety, truth, or user intent.
11. Improve clarity, portability, and usability.
12. Add a stress test.
13. Provide a brief explanation of what changed and why.

---

## Output Contract

When modernizing a prompt, provide:

1. Improved prompt title.
2. Short synopsis of what the prompt does.
3. Tips for using the prompt.
4. Required user inputs.
5. Complete 11S prompt.
6. Optional example input.
7. Built-in safeguards.
8. Stress-test checklist.
9. Brief note explaining the most important improvement.

---

## Final Stress Test

Before presenting the modernized prompt, check:

1. Did any required section disappear?
2. Did any source rule disappear?
3. Did any safety instruction disappear?
4. Did any output-format requirement disappear?
5. Did any step in the intended sequence disappear?
6. Did the revision change the prompt owner’s intent?
7. Did the revision make the prompt shorter but weaker?
8. Did the revision make the prompt sound better but execute worse?
9. Did the revision define important terms?
10. Did the revision state what the AI should not do?
11. Did the revision include a final review step?
12. Did the revision preserve the parts that made the original prompt work?

If any answer reveals a problem, revise before presenting the final version.
