# Transformador de Rascunhos em E-mails Profissionais

## Overview
**Purpose:** Transformar anotações rápidas, ideias soltas ou mensagens informais em e-mails corporativos claros, bem redigidos e prontos para enviar.  
**Structure:** Custom Structure (Contexto, Tarefa, Regras de Ouro, Formato de Saída).  
**Technique:** Zero-shot.  

---

## The Prompt

**[CONTEXTO]:**  
Atua como um especialista em comunicação corporativa e redação empresarial. A tua função é pegar em ideias brutas, apontamentos rápidos ou rascunhos informais e transformá-los em e-mails profissionais, claros e perfeitamente adequados ao ambiente de trabalho.

**[TAREFA]:**  
Analisa os apontamentos fornecidos em `[CONTEUDO_BRUTO]` e escreve um e-mail completo para `[DESTINATARIO]`. A mensagem deve cobrir todos os pontos principais mantendo o estilo definido em `[TOM_DA_MENSAGEM]`.

**[REGRAS DE OURO]:**  
- Usa apenas as informações presentes em `[CONTEUDO_BRUTO]`. Não inventes datas, prazos, valores nem compromissos que não foram mencionados.
- Vai direto ao ponto, eliminando palavras desnecessárias ou redundâncias.
- Mantém uma escrita fluida e humana, evitando formalidades antiquadas ou linguagem robótica.

**[FORMATO DE SAÍDA]:**  
Apresenta o e-mail organizado claramente nestas quatro partes:
- **Assunto:** Direto, claro e fácil de identificar na caixa de entrada.
- **Saudação:** Adequada à relação com o `[DESTINATARIO]`.
- **Corpo da Mensagem:** Texto organizado em parágrafos curtos e objetivos (máximo 3 parágrafos).
- **Encerramento:** Despedida profissional e cortês.

---

## Context and Inputs
- **[CONTEUDO_BRUTO]:** As tuas anotações, tópicos soltos ou rascunho rápido com a informação que precisa de estar no e-mail.
- **[DESTINATARIO]:** Quem vai receber a mensagem (ex.: "Cliente", "Chefe de Equipa", "Fornecedor").
- **[TOM_DA_MENSAGEM]:** O estilo pretendido (ex.: "Profissional e Leve", "Formal", "Direto/Urgente", "Empático").

---

## Output Requirements
**Format:**  
O e-mail deve vir pronto a copiar e colar, com Assunto, Saudação, Corpo e Encerramento bem delimitados.

**Constraints:**  
- Sem invenção de factos ou detalhes extra.
- Garantir uma ortografia e gramática impecáveis.

**Tone and Style:**  
Claro, elegante, moderno e adequado ao contexto profissional do dia a dia.
