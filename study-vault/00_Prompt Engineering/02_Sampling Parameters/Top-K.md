---
tags:
  - note
topic: "[[00_Prompt Engineering/02_Sampling Parameters/_Sampling Parameters|_Sampling Parameters]]"
---
# Top-K

---
## **Resumo**
Top-K é um parâmetro de sampling utilizado em LLMs para limitar o conjunto de opções de palavras que o modelo pode escolher a cada etapa da geração de texto. O **K** representa a quantidade de palavras prováveis consideradas antes de selecionar a próxima palavra.

---
## **Conceitos Abordados**

### Como funciona
O modelo calcula a probabilidade de todas as palavras possíveis para a próxima posição e seleciona apenas as palavras com maior probabilidade. A quantidade de palavras com maior probabilidade é definida com base em **K**.

### Impacto no comportamento
Valores **baixos** de K tendem a gerar respostas mais previsíveis e seguras, porém com menor diversidade e maior repetição de padrões. Já valores **altos** de K tendem a gerar respostas mais variadas e criativas, com maiores chances de textos inovadores, entretanto também podem perder a coerência;

---
## **Conteúdos Adicionais**

### Exemplos práticos
- **K baixo (5):** O modelo só pode escolher entre 5 palavras mais prováveis naquele momento, tornando a resposta mais provável.
- **K alto (50):** O modelo só pode escolher entre 50 palavras mais prováveis naquele momento, aumentando a diversidade das respostas.

### Analogia
Podemos pensar no Top-K como um filtro de opções:
- **K baixo:** O modelo só pode escolher entre os “candidatos favoritos”.
- **K alto:** O modelo pode considerar “candidatos alternativos”, trazendo mais variedade

### Diferença em relação à Temperatura
- **Temperatura:** Ajusta a aleatoriedade na escolha das palavras.
- **Top-K:** Limita o universo de opções antes da escolha.

---
