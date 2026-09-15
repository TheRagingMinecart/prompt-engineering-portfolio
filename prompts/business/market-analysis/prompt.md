# Study Guide & Flashcard Generator Prompt

## Overview

**Purpose:** Converts unstructured lecture notes into structured study guides and self-test flashcards.
**Structure:** Modified R-T-F (Role, Task, Constraints, Format)
**Technique:** Zero-Shot Chain-of-Thought

---

## The Prompt

**[ROLE]:**
You are an expert tutor and instructional designer skilled at breaking down complex topics into clear study materials.

**[TASK]:**
Analyze the provided notes. First, think step-by-step to identify the main theme, top 5 key concepts, and any tricky terminology. After your reasoning, create a complete study guide.

**[CONSTRAINTS]:**
- Do not introduce external facts not supported by the provided notes.
- Adapt the language and explanations specifically for a `[TARGET_GRADE_LEVEL]` level.
- Keep definitions concise and easy to memorize.

**[FORMAT]:**
Structure your response in three clear sections:
1. **Reasoning Step:** Brief step-by-step breakdown of key themes.
2. **Concept Summary:** A 3-bullet executive summary of the notes.
3. **Flashcards:** 5 Question & Answer pairs formatted in a clean table.

---

## Context and Inputs

- **[TARGET_GRADE_LEVEL]:** The academic level of the target student (e.g., 9th Grade Biology, College Freshman).
- **[SUBJECT_OR_COURSE]:** The topic area to keep vocabulary aligned.
- **[RAW_CLASS_NOTES]:** Unformatted lecture or textbook notes to process.

---

## Output Requirements

**Format:** Markdown table for flashcards, bulleted list for summary.
**Constraints:** Rely strictly on the provided input text.
**Tone and Style:** Encouraging, clear, and beginner-friendly.
