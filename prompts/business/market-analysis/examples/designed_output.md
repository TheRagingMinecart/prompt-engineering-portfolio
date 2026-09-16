# Designed Prompt Output

## Prompt Used
(Copied from prompt.md)

## Evaluator Score: 10/10

## Output Generated:
### 1. Reasoning Step
- Target Audience: 9th Grade Computer Science
- Core Themes: Variables, Data Types, Assignment Operators

### 2. Concept Summary
- Variables store data values in memory dynamically in Python.
- Primitive types include integers, floats, strings, and booleans.
- The `=` operator assigns values from right to left.

### 3. Flashcards
| Question | Answer |
| :--- | :--- |
| What is a variable in Python? | A named location in memory used to store a value. |
| How does Python determine data types? | Dynamically from the value assigned.|

## Rubric Breakdown

* **Clarity & Specificity:** 30/30 - The core task of generating a study guide from notes is explicit, and the constraints are clear, specific, and bounded.
* **Structure & Framework Use:** 30/30 - The prompt employs a well-defined custom structure using clearly labeled components (`[ROLE]`, `[TASK]`, `[CONSTRAINTS]`, and `[FORMAT]`).
* **Context & Inputs:** 20/20 - The prompt supplies clear context regarding target audience level, role, and the goal of analyzing notes without adding irrelevant filler.
* **Output Requirements:** 20/20 - Explicit rules are provided for exact output sections, table formatting, bulleted summaries, and target tone/reading level.

## Comparison & Feedback

This designed prompt provides precise boundaries and structural tags that force the LLM to output a clean, formatted table and controlled summaries targeted at a 9th-grade level. Compared to a naive prompt (such as "Make flashcards and a study guide from these notes"), this structured design prevents external hallucinations, locks in exact counts for flashcards and bullet points, and guarantees consistent output formatting.

FINAL SCORE: 100


## Evaluator Feedback:
- Clear structure (Role, Task, Constraints, Format).
- Zero-Shot CoT ensures logical concept selection.
- Explicit constraints prevent hallucinated external facts.
