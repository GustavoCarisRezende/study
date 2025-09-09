---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# One-Shot & Few-Shot Prompting

---
## **Resumo**
**One-Shot & Few-Shot Prompting** são estratégias em que você fornece exemplos explícitos a LLM para mostrar como ela deve responder a uma tarefa. A diferença entre as técnicas está na quantidade de exemplos:
- **One-Shot:** Um único exemplo.
- **Few-Shot:** Vários exemplos (geralmente de 3 a 5).

---
## **Conceitos Abordados**

### Como funciona?
- **One-Shot Prompting:**  
    Você apresenta uma tarefa, fornece um exemplo de entrada e saída, e depois pede ao modelo para resolver um novo caso semelhante.    

**Exemplo:**
```
Pergunta: Qual é a capital da França?  
Resposta: Paris

Pergunta: Qual é a capital da Alemanha?
```

- **Few-Shot Prompting:**  
	Você apresenta vários pares de exemplo (entrada e saída), mostrando diferentes variações ou casos, e então pede ao modelo para responder a um novo caso.

**Exemplo:**
```
Pergunta: Qual é a capital da França?  
Resposta: Paris
   
Pergunta: Qual é a capital da Itália?  
Resposta: Roma
    
Pergunta: Qual é a capital da Alemanha?
```

---
## **Conteúdos Adicionais**

### Quando usar?
- **One-shot:** Quando um exemplo já é suficiente para ilustrar o padrão desejado.
- **Few-shot:** Vários exemplos para reforçar o padrão.
- **Vantagem:** Mais controle sobre a resposta, maior precisão e consistência.

---
