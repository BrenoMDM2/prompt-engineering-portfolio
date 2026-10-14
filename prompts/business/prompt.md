# Draft-to-Professional-Email Transformer

## Overview
**Purpose:** Transform quick notes, scattered ideas, or informal messages into clear, well-written, and ready-to-send corporate emails.  
**Structure:** Custom Structure (Context, Task, Golden Rules, Output Format).  
**Technique:** Zero-shot.  

---

## The Prompt

**[CONTEXT]:**  
Act as an expert in corporate communication and business writing. Your role is to take raw ideas, quick notes, or informal drafts and transform them into professional, clear emails perfectly suited for the workplace.

**[TASK]:**  
Analyze the notes provided in `[RAW_CONTENT]` and write a complete email to `[RECIPIENT]`. The message must cover all key points while maintaining the style defined in `[MESSAGE_TONE]`.

**[GOLDEN RULES]:**  
- Use only the information present in `[RAW_CONTENT]`. Do not invent dates, deadlines, figures, or commitments that were not mentioned.
- Get straight to the point, eliminating unnecessary words or redundancies.
- Maintain a fluid, human writing style, avoiding outdated formalities or robotic language.

**[OUTPUT FORMAT]:**  
Present the email clearly organized into these four parts:
- **Subject:** Direct, clear, and easy to identify in the inbox.
- **Salutation:** Appropriate for the relationship with the `[RECIPIENT]`.
- **Message Body:** Text organized into short, objective paragraphs (maximum 3 paragraphs).
- **Closing:** Professional and courteous sign-off. ---

## Context and Inputs
- **[RAW_CONTENT]:** Your notes, rough bullet points, or a quick draft containing the information that needs to be in the email.
- **[RECIPIENT]:** The person receiving the message (e.g., "Client," "Team Lead," "Supplier").
- **[MESSAGE_TONE]:** The desired style (e.g., "Professional yet Casual," "Formal," "Direct/Urgent," "Empathetic").

---

## Output Requirements
**Format:**  
The email must be ready to copy and paste, with clearly defined Subject, Salutation, Body, and Closing sections.

**Constraints:**  
- Do not invent facts or add extra details.
- Ensure impeccable spelling and grammar.

**Tone and Style:**  
Clear, elegant, modern, and appropriate for a professional day-to-day context.












# [Prompt Name] Template
## Instructions for Use (delete this section when you build your actual prompt)
Your prompt must include:
- A short description of what it does
- Your prompt, organized into clearly labeled parts
- At least one `[PLACEHOLDER]` in square brackets and CAPS
- Output requirements so the AI knows what a good answer looks like
**Two design choices to make and note:**
- **Structure:** organize your prompt into intentional, labeled parts. Use a
framework from the lesson (for example R-T-F or C-A-R-E), modify a framework, or
design your own set of parts. What matters is that the structure is deliberate and
every part earns its place.
- **Technique:** the prompting method you use. Zero-shot (no examples), few-shot
(one or more worked examples), chain-of-thought (ask the AI to reason step by
step), or zero-shot chain-of-thought (add an instruction like "Think step by step"
with no examples).
You justify both choices in `methodology.md`.
---
## Overview
**Purpose:** [A sentence or two on what this prompt produces.]
**Structure:** [Name your framework, your modified framework, or "custom
structure," then list the parts it breaks into, for example: Context, Task,
Constraints, Format.]
**Technique:** [Zero-shot, few-shot, chain-of-thought, or zero-shot chain-of-
thought.]
---
## The Prompt
Organize your prompt into labeled parts, in the order that makes sense for your
task. Each label is one part of your structure. Somewhere in here, state the core
task or objective clearly, since that is the part the AI most needs to get right.
If your technique is few-shot, include your example(s) here; if it is chain-of-
thought, include the instruction to reason step by step.
**[PART LABEL 1]:**
[The content for this part.]
**[PART LABEL 2]:**
[The content for this part.]
**[PART LABEL 3]:**
[The content for this part.]
[Add or remove parts so the structure matches your design.]
---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[PLACEHOLDER_1]:** [What goes here and why it matters]
- **[PLACEHOLDER_2]:** [What goes here and why it matters]
- **[PLACEHOLDER_3]:** [What goes here and why it matters]
---
## Output Requirements
**Format:** [How the answer should be structured, for example length, headings,
bullets, or a table.]
**Constraints:** [Rules that keep the AI on scope and protect quality.]
**Tone and Style:** [The voice, reading level, and style you want.]
---
## Additional Instructions (optional)
Anything else the AI should keep in mind that does not fit one of the parts above.
Delete this section if you do not need it.
