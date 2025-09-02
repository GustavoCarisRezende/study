---
tags:
  - note
topic: "[[00_Prompt Engineering/02_Sampling Parameters/_Sampling Parameters|_Sampling Parameters]]"
---
# Temperatura

---
## **Resumo**
No contexto de Sampling Parameters em LLMs, a temperatura é um parâmetro que controla o grau de aleatoriedade na escolha das próximas palavras durante a geração de texto, agindo como um "regulador de criatividade" do modelo.

---
## **Conceitos Abordados**

### Temperatura baixa (ex: 0.1 a 0.3)
Com parametrizações de temperatura baixa, o modelo tende a escolher palavras mais prováveis, seguindo padrões mais previsíveis e conservadores, tornando as respostas mais seguras, diretas e menos criativas, sendo útil para tarefas onde a previsão e consistência são essenciais.

### Temperatura alta (0.7 a 1.0)
O modelo considera opções menos prováveis, tornando as respostas mais variáveis e criativas, podendo gerar textos inovadores. Todavia, corre o risco de produzir respostas incoerentes ou fora do contexto, sendo indicado para situações de brainstorming, geração de ideias, etc.

---
## **Conteúdos Adicionais**

### Exemplo prático
Se você pedir para o modelo completar a frase “O céu é...”
- **Temperatura baixa:** “azul.”
- **Temperatura alta:** “um vasto oceano de possibilidades, onde sonhos voam.”

---
