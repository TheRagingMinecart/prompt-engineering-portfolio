---

## 2. Technology Category: Code Explainer & Bug Fixer

### File 1: `prompts/technology/code-explainer/README.md`
```markdown
# Code Explainer & Bug Fixer

> Explains tricky code in plain English and helps you spot and fix mistakes.

## Overview

This prompt helps you make sense of confusing code snippets. It breaks down what the code is doing step-by-step and shows you how to fix bugs without using confusing computer jargon.

**Best for:**
- Learning what a piece of code actually does
- Finding bugs or errors in your code
- Getting cleaner, easier-to-read code

**Structure:** Custom Context/Task/Rules/Output Layout
**Technique:** Zero-Shot Chain-of-Thought
**Output:** Simple breakdown with plain-English notes and fixed code

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the text.
2. Fill in the blanks:
   - `[PROGRAMMING_LANGUAGE]`: Python, JavaScript, HTML, etc.
   - `[CODE_SNIPPET]`: Paste the code you want to check.
   - `[TARGET_AUDIENCE]`: Total beginner, student, etc.
3. Paste it into your AI tool and hit run.

---

## Technical Details

- **Structure:** Custom Context / Task / Rules / Output
- **Technique:** Zero-Shot Chain-of-Thought ("Think through this step-by-step")
- **Best models:** GPT-4o, Claude 3.5 Sonnet, Gemini
- **Placeholders:** 3
