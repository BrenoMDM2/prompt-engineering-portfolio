# Design Plan: Repetition Hunter

## Project Goal
The goal of this prompt is to help beginner programmers spot repeated code and learn how to keep their code short and clean, without getting lost in complicated tech words.

---

## Design Approach: Structure and Technique

**Structure used:** Simple layout split into **Context / Task / Inputs**.

**Why this structure fits my task:**
- Keeps everything neat and easy to read.
- Separates the instructions from the user's code so the AI doesn't mix up what to do with the code it needs to check.

**Technique used:** Zero-shot (Direct prompt).

**Why this technique fits my task:**
AI is already really good at finding repeated lines and cleaning up code. A clear, direct instruction gets the job done without needing extra examples.

---

## Section-by-Section Justification

| Section | What I put here | Why the prompt needs it |
| :--- | :--- | :--- |
| **CONTEXT** | `You are a patient senior programming mentor focused on teaching best practices to beginners.` | Gives the AI a friendly role so it explains things simply, like a helpful guide, without using hard words. |
| **TASK** | `Analyze the provided code, identify repeated lines or logic, explain in simple terms why unnecessary code should be avoided, and present a corrected and simplified version.` | Tells the AI the exact steps to follow from start to finish. |
| **INPUTS** | `PROGRAMMING_LANGUAGE: Python, JavaScript.`<br>`CODE: [User pastes code here]` | Keeps the user's code in one place so the AI knows exactly what to look at. |

---

## Testing and Iteration

**Baseline (simple request without structure):**
`"Simplify this code and remove repetitions: [when I make the code put here]"`

| Version | Result / Score | What Changed |
| :--- | :---: | :--- |
| **Baseline** | [To be filled after testing] | [e.g., The AI just gave back code without explaining anything] |
| **Version 1** | [To be filled after testing] | [e.g., Used words that were too hard for beginners] |
| **Final Version** | [To be filled after testing] | [e.g., Explained everything simply in plain English] |

* **What testing showed:** [Write what happened after you tested both prompts]
* **What I learned:** [Write what you learned about making prompts]

---

## Strengths and Limitations

* **Works well when:** []
* **Struggles when:** []
* **Would improve next:** []
