---
tags:
  - note
topic: "[[00_Prompt Engineering/04_Repetition Penalties/_Repetition Penalties|_Repetition Penalties]]"
---
# Presence Penalty

---
## **Resumo**
**Presence Penalty** é um parâmetro que aplica penalidades na LLM para evitar repetição de tokens, porém, possuí um funcionamento diferente do *Frequency Penalty*.

---
## **Conceitos Abordados**

### Como funciona?
o *Presence Penalty* aplica uma penalização a qualquer token que já tenha sido utilizado anteriormente na resposta, independente de quantas vezes ele apareceu.

---
## **Conteúdos Adicionais**

### Diferença entre Presence Penalty e Frequency Penalty
Enquanto o *Frequency Penalty* aumenta a penalização conforme a frequência de uso, o *Presence Penalty* só considera se o token já foi usado ou não, aplicando a penalização de forma igual para todos os tokens já presentes.
Para exemplificar a diferença, imagina que o token da palavra *estudo* tenha sido usado na frase que a LLM esteja elaborando:
- Com **Frequency Penalty**, caso a palavra se repita 1 vez, e penalidade será de 1 ponto, caso se repita pela segunda vez, a penalidade aumenta em 3 pontos, e assim sucessivamente *(valores fictícios)*.
- Já com **Presence Penalty**, a cada aparição da palavra "esestudotudo", a penalização aumenta em 1 ponto, independente de quantas vezes ela já apareceu na resposta.

### Exemplos práticos

> Se o modelo já usou a palavra "eficiente" uma vez, o presence penalty reduz a probabilidade de ela ser escolhida novamente, mesmo que tenha aparecido apenas uma vez. Isso incentiva o modelo a buscar outras palavras, como "rápido", "produtivo" ou "ágil".

---
