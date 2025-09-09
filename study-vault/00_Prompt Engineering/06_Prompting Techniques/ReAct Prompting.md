---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# ReAct Prompting

---
## **Resumo**
**ReAct Prompting (Reason and Act)** é uma abordagem que combina o raciocínio da LLM com a capacidade de executar ações externas, como interagir com API's, bancos de dados, etc. O modelo alterna entre *pensar* (**reason**), *agir* (**act**), *observar* (**observation**), formando um ciclo até chegar a solução do problema.

---
## **Conceitos Abordados**

### Como funciona?
1. **Reason (Raciocinar):**  
    O modelo analisa o problema, explicita seu raciocínio e decide qual ação tomar.
2. **Act (Agir):**  
    O modelo executa uma ação externa, como consultar uma API, buscar dados ou realizar um cálculo.
3. **Observation (Observar):**  
    O modelo avalia o resultado da ação, ajusta seu raciocínio e decide os próximos passos.

### Para que serve?
Tarefas que exigem dados atualizados ou problemas que possuem múltiplas etapas são exemplos de situações onde esta abordagem pode ser utilizada, permitindo automação de fluxos complexos, como assistentes virtuais, agentes de pesquisa, etc.

---
## **Conteúdos Adicionais**

### Exemplo
- **Reason:** "Preciso buscar a cotação atual do dólar em uma fonte confiável."
- **Act:** O modelo faz uma chamada para uma API de câmbio.
- **Observation:** Recebe o valor da cotação e verifica se está atualizado.
- **Reason:** "Agora posso informar a cotação ao usuário."

---
