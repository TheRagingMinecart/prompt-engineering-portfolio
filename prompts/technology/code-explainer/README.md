# Code Explainer & Bug Fixer

> A friendly helper that breaks down confusing code and helps you fix bugs without using big tech words.

## Overview

This prompt acts like a friend who is great at coding sitting down next to you. It reads your code, tells you what it actually does in plain English, and shows you where the bugs are hiding.

**Best for:**
- Figure out what confusing code actually does
- Finding and fixing bugs when your code isn't working
- Learning clean coding habits in a relaxed way

**Structure:** Custom Layout (Context, Task, Rules, Output Format)
**Technique:** Zero-Shot Chain-of-Thought
**Output:** Simple breakdown, plain-English summary, bug list, and fixed code

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the text.
2. Fill in the placeholders:
   - `[PROGRAMMING_LANGUAGE]`: Python, JavaScript, HTML, etc.
   - `[CODE_SNIPPET]`: Paste the confusing code here.
   - `[TARGET_AUDIENCE]`: Total beginner, high school student, etc.
3. Paste it into your AI tool and hit run.

---

## Technical Details

- **Structure:** Custom Layout (Context, Task, Rules, Output Format)
- **Technique:** Zero-Shot Chain-of-Thought ("Think step-by-step")
- **Best models:** GPT-4o, Claude 3.5 Sonnet, Gemini
- **Placeholders:** 3
