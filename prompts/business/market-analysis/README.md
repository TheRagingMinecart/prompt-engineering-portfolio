# Study Guide & Flashcard Generator

> Turn raw class notes into structured study guides and practice flashcards tailored to any grade level.

## Overview

This prompt processes unformatted lecture or reading notes and creates a clear summary, core key terms, and practice flashcards. It helps students study faster and helps educators convert raw material into study sheets.

**Best for:**
- Converting raw class notes into study materials
- Creating practice test questions with answers
- Breaking down complex topics for specific grade levels

**Structure:** Modified R-T-F (Role, Task, Constraints, Output Format)
**Technique:** Zero-Shot Chain-of-Thought
**Output:** Markdown study sheet with key terms and flashcards

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[TARGET_GRADE_LEVEL]`: High school, Middle school, College, etc.
   - `[SUBJECT_OR_COURSE]`: Computer Science, History, Biology, etc.
   - `[RAW_CLASS_NOTES]`: Paste your lecture notes or text here.
3. Paste it into your AI model and run it.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations.

---

## Technical Details

- **Structure:** Modified R-T-F (Role, Task, Constraints, Format)
- **Technique:** Zero-Shot Chain-of-Thought ("Think step-by-step")
- **Best models:** GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro
- **Placeholders:** 3
