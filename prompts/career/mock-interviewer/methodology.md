# Design Methodology: Mock Interviewer & Feedback Coach

## Design Goal

I wanted to make a prompt that feels like a friendly friend giving you honest, helpful tips on your job interview answers.

---

## Design Approach: Structure and Technique

**Structure I used:** Modified C-A-R-E (Context, Action, Result, Example)

**Why this structure fits my task:**
- **Context** lets the AI know what job I'm applying for so it gives the right advice.
- **Example** shows the AI exactly how to write out the feedback so it doesn't leave me guessing.

**Technique I used:** Few-Shot

**Why this technique fits my task:**
- Giving the AI a quick example keeps the feedback super constructive and practical instead of just saying "Great job!"

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|---|---|---|
| Context | Hiring manager role + job level | Helps the AI judge my answer for the right kind of job. |
| Action | Check my draft answer | Tells the AI what to look for, like missing details or tone. |
| Example | A small sample feedback note | Shows the AI how to format its response neatly. |
| Result | Final tips & rewrite | Gives me a clean, updated answer I can actually practice. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Give me feedback on this interview answer for a [JOB_TITLE] role: [USER_ANSWER]
