# Design Methodology: Code Explainer & Bug Fixer

## Design Goal

I wanted to make a prompt that acts like a friendly mentor sitting down with you to explain confusing code without making you feel overwhelmed.

---

## Design Approach: Structure and Technique

**Structure I used:** Custom Layout (Context, Task, Rules, Output Format)

**Why this structure fits my task:**
- Putting **Rules** in place keeps the AI from using super complex technical words that are hard to follow.

**Technique I used:** Zero-Shot Chain-of-Thought

**Why this technique fits my task:**
- Code needs to be checked carefully step-by-step. Telling the AI to "think step-by-step" before writing its answer helps it catch tiny mistakes like missing quotes or wrong calculations.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|---|---|---|
| Context | Patient programming helper persona | Sets a friendly, encouraging tone. |
| Task | Trace code step-by-step | Forces the AI to read the code line-by-line first. |
| Rules | Target audience & simple terms | Keeps the explanation beginner-friendly. |
| Output Format | 4 simple sections | Gives me a clean explanation and working code. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Explain this code and fix any bugs: [CODE_SNIPPET]
