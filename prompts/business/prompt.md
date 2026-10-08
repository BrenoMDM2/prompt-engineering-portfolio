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

