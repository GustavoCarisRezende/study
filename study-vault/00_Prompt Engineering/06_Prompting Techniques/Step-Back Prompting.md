---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# Step-Back Prompting

---
## **Resumo**
**Step-Back Prompting** é uma técnica de prompting que consiste em dar um passo atrás antes de resolver determinada tarefa. Ou seja, primeiro realizando perguntas conceituais a LLM sobre o assunto e, com o conhecimento obtido nas respostas, abordar uma tarefa mais específica.

---
## **Conceitos Abordados**

### Como funciona?
Inicialmente é solicitado a LLM que reflita sobre  princípios, conceitos ou informações amplas relacionadas ao tema. O modelo irá fornecer uma base conceitual ou lista de princípios. Com base nessa resposta, você pede ao modelo para resolver o problema específico, utilizando do conhecimento recém ativado.

### Para que serve?
Esta técnica pode **reduzir vieses**, ou seja, evita que o modelo apresente respostas baseada apenas em conhecimentos superficiais. Além disso, **aumenta a precisão** e **melhora a criatividade**.

---
## **Conteúdos Adicionais**

### Exemplo
- **Tarefa específica:** Escrever a história de um nível de jogo de tiro em primeira pessoa.
- **Step-back:** Primeiro, pergunte: "Quais são os cenários mais envolventes para níveis de jogos de tiro em primeira pessoa?"
- **Aplicação:** Use as ideias geradas para criar a história do nível, tornando-a mais rica e fundamentada.

---
