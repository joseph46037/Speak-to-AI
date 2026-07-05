# The 11S Method

The 11S Method is a practical framework for writing better AI prompts.

Most weak AI output starts with an unclear request. The user knows what they want, but the AI receives only fragments: a task, a few facts, maybe a preferred tone. The AI then guesses the structure, scope, source material, audience, quality standard, and missing assumptions.

11S reduces that guessing.

It gives the user eleven control points for turning a vague request into a prompt the AI can follow, test, and improve.

---

## 1. Structure

**Structure** controls how the answer should be organized.

It answers: **What should the final response look like?**

Examples:

- Start with the conclusion.
- Use headings.
- Put the facts before the analysis.
- End with next steps.
- Use a table followed by a short explanation.

Structure gives the answer a shape before the AI starts writing.

---

## 2. Schema

**Schema** controls the required fields, categories, labels, and reusable format.

It answers: **What parts must be included every time?**

Examples:

- Include sections for facts, issues, risks, missing information, and recommendations.
- Use columns for task, owner, deadline, and status.
- Return JSON with specific keys.
- Use a legal outline with I., A., 1., and a.

Structure is the overall shape. Schema is the required pattern inside that shape.

---

## 3. Syntax

**Syntax** controls wording, grammar, formatting, and command form.

It answers: **How should the instructions be written?**

Examples:

- Use complete sentences.
- Avoid vague pronouns.
- Use plain English.
- Do not use bullet points.
- Use numbered sections.
- Write in Markdown.

Syntax reduces confusion caused by sloppy wording.

---

## 4. Semantics

**Semantics** controls meaning.

It answers: **What do the important words mean in this prompt?**

Examples:

- “Client” means the law firm’s client, not the AI user.
- “Draft” means an internal working draft, not a final filing.
- “Source” means only the uploaded documents unless otherwise stated.
- “Review” means identify problems, not rewrite the entire document.

Semantics prevents the AI from using the wrong meaning for the right word.

---

## 5. Specificity

**Specificity** controls the amount and precision of detail.

It answers: **What exact information should the AI rely on?**

Examples:

- Use Indiana law.
- Write for a tenth-grade audience.
- Limit the answer to 500 words.
- Use the attached transcript only.
- Identify the three weakest assumptions.
- Do not invent a fourth item to complete a list.

Specificity turns general requests into usable instructions.

---

## 6. Scope

**Scope** controls what is inside and outside the assignment.

It answers: **How far should the AI go?**

Examples:

- Draft only the introduction.
- Do not rewrite the facts section.
- Do not conduct legal research.
- Do not add new claims.
- Do not discuss federal law unless asked.

Scope protects the task from expanding beyond the user’s intent.

---

## 7. Source

**Source** controls what the AI may rely on.

It answers: **Where should the answer come from?**

Examples:

- Use only the uploaded file.
- Use official court rules.
- Use current product documentation.
- Use primary legal authority.
- If a claim cannot be verified, say so.

Source is one of the strongest anti-hallucination controls in the 11S Method.

---

## 8. Safeguards

**Safeguards** control the mistakes the AI must avoid.

It answers: **What could go wrong, and how should the prompt prevent it?**

Examples:

- Do not invent citations.
- Separate facts from assumptions.
- Flag missing information.
- Identify uncertainty.
- Do not provide legal advice to a client without attorney review.
- Do not enter confidential information into unapproved systems.

Safeguards turn caution into instructions the AI can follow.

---

## 9. Style

**Style** controls voice, tone, audience fit, and rhetorical limits.

It answers: **How should the response sound?**

Examples:

- Write for a busy managing partner.
- Use plain English.
- Be direct and professional.
- Avoid hype.
- Avoid sarcasm.
- Use a warmer tone for a client letter.

Style should improve readability without weakening accuracy.

---

## 10. Sequence

**Sequence** controls the order of operations.

It answers: **What should the AI do first, second, third, and last?**

Examples:

- First summarize the facts.
- Second identify missing information.
- Third draft the response.
- Fourth run a quality check.
- Fifth provide the final version.

Sequence matters because AI often produces weaker output when it drafts before it analyzes.

---

## 11. Stress Test

**Stress Test** controls the final quality check.

It answers: **Would this output survive careful review?**

Examples:

- Are the facts supported?
- Are the citations real?
- Is the jurisdiction correct?
- Did the answer follow the requested format?
- Did it avoid unsupported assumptions?
- Did it stay within scope?

Stress Test is the final guardrail before the user relies on the output.

---

## The 11S Method In One Sentence

The 11S Method tells the AI what to do, what to use, what to avoid, how to organize the answer, how to sound, and how to check the work before giving it back.

---

## Simple 11S Template

```text
Structure:
Organize the answer like this: [insert structure].

Schema:
Include these required sections or fields: [insert schema].

Syntax:
Follow these wording and formatting rules: [insert syntax rules].

Semantics:
Use these definitions: [insert important meanings].

Specificity:
Use these exact facts, details, constraints, and examples: [insert specifics].

Scope:
Include this: [insert included items].
Do not include this: [insert exclusions].

Source:
Rely on these materials only: [insert sources].

Safeguards:
Avoid these errors: [insert safeguards].

Style:
Write in this tone for this audience: [insert style].

Sequence:
Work in this order: [insert sequence].

Stress Test:
Before finalizing, check: [insert quality checks].
```

---

## Why 11S Works

11S works because it converts intent into operating instructions.

A weak prompt asks the AI to guess.

A strong 11S prompt gives the AI a job, a boundary, a source, a format, a voice, a sequence, and a final review standard.

That is the difference between asking AI to produce something and teaching AI how to produce the thing you actually need.
