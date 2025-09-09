---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# Chain of Thought (CoT) Prompting

---
## **Resumo**
**Chain of Thought (CoT) Prompting** é uma técnica que incentiva a LLM a explicitar seu raciocínio, detalhando cada etapa do pensamento antes de chegar a resposta final. O modelo é orientado ad *pensar em voz alta*, mostrando o caminho lógico ou matemático que leva a solução.

---
## **Conceitos Abordados**

### Como funciona?
Esta técnica **estimula o raciocínio passo a passo**, pois, com a adição das instruções como *Vamos pensar passo a passo* ao prompt, o modelo é incentivado a dividir o problema em partes menores e resolver cada uma delas sequencialmente. Com isso, podemos visualizar as **etapas intermediárias**, tornando o processo mais transparente e compreensível.
Esta técnica também **aumenta a precisão** das respostas, pois evita erros de lógica ou saltos de conclusão, especialmente em tarefas complexas.

### Para que serve?
- **Evita erros de lógica em tarefas complexas**
- **Aumenta a transparência sobre as respostas**
- Ideal para problemas complexos que exigem uma análise detalhada.

---
## **Conteúdos Adicionais**

### Exemplo prático
**Pergunta direta:**  
*"Se João tem 3 maçãs e compra mais 2, quantas maçãs ele tem agora?"*

**Prompt com Chain of Thought:**  
*"João tem 3 maçãs. Ele compra mais 2 maçãs. Vamos pensar passo a passo:*
- Primeiro, João tinha 3 maçãs.
- Depois, ele comprou mais 2.
- 3 + 2 = 5.  
	  Portanto, João tem 5 maçãs."

---
