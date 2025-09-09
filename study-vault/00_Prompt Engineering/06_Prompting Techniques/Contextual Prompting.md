---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# Contextual Prompting

---
## **Resumo**
**Contextual Prompting** é uma técnica em que são fornecidas informações para a LLM sobre o contexto específico e imediato, relacionadas diretamente à tarefa ou situação atual. Diferente do *system prompting* (que define regras gerais para toda a seção) e do *role prompting* (que define um papel fixo), o **contextual prompting** entrega detalhes dinâmicos e situacionais que mudam conforme a necessidade em cada interação.

---
## **Conceitos Abordados**

### Como funciona?
No prompt informado a LLM, são inseridas informações referentes ao contexto (cenário, objetivo, público-alvo, dentre outras informações que auxiliem o modelo a entender melhor a tarefa), isso permite que a LLM se **adapte de forma dinâmica**, de acordo com o contexto informado.

### Para que serve?
Esta técnica pode ser utilizada para aumentar a relevância das respostas geradas pela LLM, garantindo que estejam de acordo com o contexto e, consequentemente aumentando a precisão. Além disso, esta técnica também pode ser utilizada em situação onde é necessário maior flexibilidade entre as interações com o modelo.

---
## **Conteúdos Adicionais**

### Exemplos
- **Prompt:**  
    "Contexto: Você está escrevendo para um blog sobre jogos de arcade dos anos 80. Sugira 3 temas para artigos."
- **Resposta esperada:**  
    O modelo sugere temas diretamente relacionados a jogos de arcade dos anos 80, como "A evolução dos fliperamas clássicos", "Os jogos mais icônicos da década de 80" e "Como os arcades influenciaram a cultura pop".

---
