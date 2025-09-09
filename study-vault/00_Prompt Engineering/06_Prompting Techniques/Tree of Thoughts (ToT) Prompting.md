---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# Tree of Thoughts (ToT) Prompting

---
## **Resumo**
**Tree of Thoughts (ToT) Prompting** é uma evolução da técnica *Chain of Thought (CoT)*. Enquanto o CoT faz o modelo seguir um único caminho linear de raciocínio, o ToT permite que o modelo explore múltiplos caminhos de raciocínio simultaneamente, formando uma estrutura em *árvore*, onde cada *ramo* representa uma etapa intermediária ou sequência de raciocínios, possibilitando diferentes abordagens para resolver um problema.

---
## **Conceitos Abordados**

### Como funciona?
O modelo começa com um pensamento inicial e, a partir dele ramifica para diferentes possibilidades de raciocínio, criando caminhos paralelos para **exploração simultânea**, onde diversas alternativas são avaliadas e, no final, o modelo escolhe a solução mais promissora ou combina diversas soluções para uma melhor resposta.

### Para que serve?
Esta técnica pode ser utilizada em tarefas complexas que exigem análise de múltiplas soluções, em situações onde existem várias formas de chegar no mesmo resultado. Além disso, a técnica permite que o modelo proponha soluções mais criativas e abrangentes, podendo aumentar a precisão e qualidade da resposta.

---
## **Conteúdos Adicionais**

### Exemplo
- **CoT:** O modelo segue um único caminho de raciocínio, etapa por etapa, até chegar à resposta.
- **ToT:** O modelo considera várias possibilidades em cada etapa, por exemplo: "Se eu fizer A, pode acontecer X ou Y; se eu fizer B, pode acontecer Z ou W", e assim por diante, formando uma árvore de decisões.

---
