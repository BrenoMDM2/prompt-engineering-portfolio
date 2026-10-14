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



# Design Methodology: [Prompt Name]
## Design Goal
[A sentence or two on what you were trying to achieve and who the prompt is for.]
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** [A lesson framework, a modified framework, or your own
structure, for example: C-A-R-E, a modified R-T-F, or a custom
Context/Task/Constraints/Format layout.]
**Why this structure fits my task:**
- [Reason 1]
- [Reason 2]
**Technique I used:** [Zero-shot, few-shot, chain-of-thought, or zero-shot chain-
of-thought.]
**Why this technique fits my task:**
[For example: I used few-shot because the AI needed to copy a specific tone, so I
gave it two sample outputs. Or: I used zero-shot chain-of-thought because the task
needs step-by-step logic but I did not have examples, so I added "Think through
this step by step before you answer."]
**Example of modifying a framework (delete if not relevant):**
I started from R-T-F (Role, Task, Format) and added two parts. I added a
**Constraints** part to stop the model from making pricing claims, and an
**Example** part to lock in the tone I wanted. My final structure was Role, Task,
Constraints, Example, Format. Each added part solved a specific problem the plain
framework left open.
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| [Part 1] | [Your text] | [Reason] |
| [Part 2] | [Your text] | [Reason] |
| [Part 3] | [Your text] | [Reason] |
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
[Your plain, naive version of the same request]
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | [result] | [notes] |
| Version 1 | [result] | [notes] |
| Final | [result] | [notes] |
**What testing showed:** [In your own words, how your designed prompt performed
compared to the baseline, and what you changed as a result.]
**What I learned:** [What this taught you about prompt design.]
---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]
