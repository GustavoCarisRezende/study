---
tags:
  - note
topic: "[[00_Prompt Engineering/06_Prompting Techniques/_Prompting Techniques|_Prompting Techniques]]"
---
# Self-Consistency Prompting

---
## **Resumo**
**Self-Consistency Prompting** é uma abordagem avançada de prompting que busca aumentar a confiabilidade das respostas geradas pela LLM em tarefas de raciocínio complexo. De forma geral, é solicitada a LLM que busque a solução para um problema diversas vezes, dando a possibilidade dela ir por caminhos diferentes (*normalmente são utilizadas configurações de temperatura mais elevadas para maior variedade de respostas*). Com isso, as respostas obtidas vão para um sistema onde é identificada a resposta com maior frequência (*majority voting*), esta é a resposta considerada mais confiável

---
## **Conceitos Abordados**

### Como funciona
1. **Geração de múltiplas respostas:** O modelo é solicitado a resolver o mesmo problema várias vezes, cada vez podendo seguir um caminho de raciocínio diferente.
2. **Uso de temperatura alta:** Ao aumentar a temperatura, o modelo explora diferentes abordagens e soluções, em vez de repetir sempre o mesmo padrão.
3. **Votação por maioria:** Após coletar várias respostas, identifica-se qual resposta aparece com mais frequência (majority voting). Essa resposta é considerada a mais confiável.
4. **Pseudo-probabilidade:** A frequência de cada resposta pode ser interpretada como uma indicação da confiança do modelo naquela solução.

### Para que serve?
Esta técnica **aumenta a precisão** das respostas, reduzindo o impacto de erros em cadeias de raciocínio individuas, pois a resposta final é baseada no consenso de múltiplas tentativas. Isso **melhora a confiabilidade** sobre as respostas geradas e possibilita **explorar diferentes abordagens** para a solução do mesmo problema.

---
## **Conteúdos Adicionais**

### Limitações
Entretanto, esta técnica possuí alguns **contras**, como o maior **custo computacional**, pois são necessárias múltiplas requisições e a **complexidade de implementação**, pois exige um sistema para coletar, comparar e votar nas respostas.

---
