# Design Methodology: Study Guide & Flashcard Generator

## Design Goal

The goal was to build a reliable prompt that converts messy notes into clear study flashcards without introducing false information or hallucinated facts.

---

## Design Approach: Structure and Technique

**Structure I used:** Modified R-T-F (Role, Task, Constraints, Format)

**Why this structure fits my task:**
- Adding explicit **Constraints** prevents the model from injecting outside facts that weren't in the student's actual class notes.
- Setting a distinct **Format** ensures the output renders immediately as clean Markdown flashcards rather than messy paragraphs.

**Technique I used:** Zero-Shot Chain-of-Thought

**Why this technique fits my task:**
- Creating study cards requires logic: selecting what is important versus what is minor detail.
- Asking the AI to reason step-by-step before producing the final cards drastically reduces errors and ensures the 5 most critical concepts are chosen.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Expert tutor & instructional designer | Sets the tone to be clear, educational, and easy to understand. |
| Task | Reason step-by-step then create study guide | Forces logical selection of key topics before generating outputs. |
| Constraints | Rely only on notes, adapt to grade level | Keeps output accurate to the source material and at the right difficulty. |
| Format | 3 explicit sections including a table | Ensures consistent, usable Markdown output every time. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Make flashcards from these notes: [RAW_CLASS_NOTES]
