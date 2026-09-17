# Prompt Engineering Frameworks

This document serves as a reference guide for standard prompt engineering frameworks used to structure effective prompts for Large Language Models (LLMs).

---

## 1. RTF Framework (Role, Task, Format)
Best for quick, structured queries where clear boundaries are needed.

- **Role**: Define who the AI should act as (e.g., *Senior Software Engineer*).
- **Task**: Define what needs to be done (e.g., *Review this Python code for performance bottlenecks*).
- **Format**: Specify how the output should be presented (e.g., *Bullet points with code snippets*).

---

## 2. RACE Framework (Role, Action, Context, Expectation)
Best for complex tasks requiring background context and specific standards.

- **Role**: Set the persona/perspective of the LLM.
- **Action**: State the main objective or task.
- **Context**: Provide relevant background information and constraints.
- **Expectation**: Define the desired tone, structure, or quality standards.

---

## 3. TAG Framework (Task, Action, Goal)
Ideal for straightforward, goal-oriented requests.

- **Task**: Describe the overall assignment.
- **Action**: Outline the specific actions the model must execute.
- **Goal**: Clarify the intended outcome or ultimate objective.

---

## 4. CARE Framework (Context, Action, Result, Example)
Useful when broad context and reference examples are critical for accuracy.

- **Context**: Describe the background scenario.
- **Action**: Define what the model needs to perform.
- **Result**: Specify the desired end product.
- **Example**: Provide concrete input/output examples (Few-Shot Prompting).

---

## 5. RISEN Framework (Role, Instructions, Steps, End Goal, Narrowing)
Ideal for complex, multi-step workflows.

- **Role**: Establish the expert persona.
- **Instructions**: Give detailed instructions.
- **Steps**: Provide sequential execution steps.
- **End Goal**: Define the final deliverable.
- **Narrowing**: Specify negative constraints or rules (things to avoid).
