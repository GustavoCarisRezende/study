---
tags:
  - note
topic: "[[00_Prompt Engineering/02_Sampling Parameters/_Sampling Parameters|_Sampling Parameters]]"
---
# Top-P

---
## **Resumo**
**Top-P**, também conhecido como **Nucleus Sampling**, é um parâmetro de sampling que define um *núcleo* de palavras candidatas para a próxima posição no texto, baseado em uma probabilidade acumulada. Em vez de limitar por quantidade fixa, o Top-P limita por probabilidade total.

---
## **Conceitos Abordados**

### Como funciona
O modelo calcula a probabilidade de todas as palavras possíveis para a próxima posição, selecionando um menor conjunto de palavras cuja soma das probabilidades seja igual ou superior ao valor de **P**. A próxima palavra é escolhida de forma aleatória entre estas opções.

### Impacto no comportamento
- **P baixo:** O modelo é mais restritivo, escolhendo entre poucas opções prováveis, gerando respostas mais previsíveis e seguras.
- **P alto:** O modelo considera mais opções, aumentando a diversidade e criatividade, porém aumentando a chance de perder a coerência.

---
## **Conteúdos Adicionais**

### Exemplo Prático
- Se **Top-P = 0.9**, o modelo considera apenas as palavras que, juntas, somam 90% da probabilidade total.
- Se poucas palavras têm alta probabilidade, o conjunto será pequeno.
- Se muitas palavras têm probabilidade semelhante, o conjunto será maior.

### Analogia
Imagine o Top-P como um “balde de probabilidades”:
- Você vai colocando palavras no balde até que a soma das probabilidades atinja o valor P
- Só então o modelo escolhe uma palavra desse balde

### Diferença em relação ao Top-K
- **Top-K:** Limita por quantidade fixa de palavras.
- **Top-P:** Limita por probabilidade acumulada, adaptando o tamanho do conjunto conforme o contexto.

---
