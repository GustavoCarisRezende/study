---
tags:
  - note
topic: "[[00_Prompt Engineering/04_Repetition Penalties/_Repetition Penalties|_Repetition Penalties]]"
---
# Frequency Penalty

---
## **Resumo**
**Frequency Penalty** é um parâmetro utilizado em LLMs para controlar a repetição de palavras ou tokens durante a geração de textos. Ele atua penalizando tokens com base na frequência com que já apareceram na resposta até o momento.

---
## **Conceitos Abordados**

### Como funciona?
Cada vez que um token é utilizado, o modelo aumenta a penalização para este token nas próximas escolhas, reduzindo a probabilidade dele aparecer novamente. Isso tem como principal objetivo incentivar o modelo a variar o vocabulário, evitando repetições desnecessárias.

---
## **Conteúdos Adicionais**

### Exemplo prático

> Imagine que um modelo está gerando uma resposta e já usou a palavra "importante" três vezes. Com o **frequency penalty** ativado, a chance de o modelo usar "importante" novamente diminui a cada repetição, levando-o a buscar alternativas como "relevante", "fundamental" ou "essencial".

---
