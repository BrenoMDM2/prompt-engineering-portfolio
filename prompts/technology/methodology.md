```redução
# Metodologia de Design: Caçador de Repetições

## Objetivo do projeto
O objetivo deste prompt é para iniciantes em programação identificar linhas ou lógicas de código repetido e aprender a simplificar a aplicação do princípio DRY (*Don't Repeat Yourself*), sem ficar tão complexo.

---

## Abordagem de Design: Estrutura e Técnica

**Estrutura que utilizei:** Layout estruturado de **Contexto / Tarefa / Entradas (Contexto / Tarefa / Entradas)**.

**Por que essa estrutura se adapta à minha tarefa:**
- Porque eu gostei desse design e tambem
- Separar as instruções da tarefa do código do usuário, evitando que o modelo misture as orientações com o código a ser analisado.

**Técnica que usei:** Tiro zero.

**Por que esta técnica se adapta à minha tarefa:**
A identificação de repetições e a refatoração básica de código são capacidades nativas bem consolidadas em modelos de linguagem. Uma instrução direta e bem delimitada é suficiente para obter a resposta desejada sem a necessidade de exemplos (*few-shot*).

---

## Justificativa Parte por Parte

| Parte | O que coloquei aqui | Por que o prompt precisa disso |
|------|-----------------|------------------------|
| **CONTEXTO** | `eu achei legal essa ideia porque isso pode ajudar bastante com menos tempo de digitacao menos bugsfaciitar a leitura tambem ` |
| **TAREFA** | `Analisa o código que voce fez, identifica linhas ou lógicas que foram repetidas, explica em linguagem simples por que razão por um coigo desnessesario pode ser evitada e apresenta a versão corrigida e simplificada do código.` |
| **Código e linguagem de programação** | `PROGRAMMING_LANGUAGE: Python, JavaScript.`<br>`CÓDIGO: [Quando eu fazer o codigo, eu coloco aqui]` 
---

## Teste e iteração

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
