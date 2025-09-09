---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# Zero-Shot Prompting

---
## **Resumo**
**Zero-Shot Prompting** é uma técnica de prompting onde você fornece à LLM apenas a descrição da tarefa a ser realizada, sem apresentar exemplos específicos de como a tarefa deve ser executada. A LLM irá utilizar seu conhecimento obtido durante o treinamento para resolver a tarefa apenas baseado na descrição.

---
## **Conceitos Abordados**

### Como funciona?
Você fornece para a LLM oque deseja que ela faça, de forma objetiva e direta, fornecendo ás informações que serão processadas. Desta forma, o modelo tenta inferir a melhor resposta possível, baseando-se em padrões obtidos durante o treinamento, sem depender de exemplos específicos.

### Para que serve?
Esta técnica pode ser utilizada para:
- **Classificação simples:** *Exemplo: "Diga se o sentimento deste texto é positivo ou negativo: 'Adorei o produto!'"*
- **Geração de texto:** *Exemplo: "Escreva uma breve introdução sobre energia renovável."*
- **Perguntas e respostas:** *Exemplo: "Quem foi Albert Einstein?"*

---
