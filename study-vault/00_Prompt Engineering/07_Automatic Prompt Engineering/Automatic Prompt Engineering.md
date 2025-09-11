---
tags:
  - note
topic: "[[00_Prompt Engineering/07_Automatic Prompt Engineering/_Automatic Prompt Engineering|_Automatic Prompt Engineering]]"
---
# Automatic Prompt Engineering

---
## **Resumo**
**Automatic Prompt Engineering (APE)** é uma abordagem que utiliza LLMs para **gerar** e **otimizar** prompts de forma automática, com o  objetivo de reduzir o esforço manual na criação de prompts, além de otimizar as interações com as LLMs.

---
## **Conceitos Abordados**

### Como funciona o APE?
1. **Geração Automática de Variantes:**  
    O modelo é instruído a criar várias versões de um prompt para uma tarefa específica. Por exemplo, gerar 10 formas diferentes de pedir um pedido em um chatbot.
2. **Avaliação das Variantes:**  
    Cada variante é avaliada usando métricas automáticas (como BLEU ou ROUGE) para medir sua qualidade ou aderência ao objetivo.
3. **Seleção e Otimização:**  
    As variantes com melhor desempenho são selecionadas e podem ser refinadas em ciclos iterativos, buscando sempre melhorar os resultados.

Esta técnica é de extrema importância, pois aumenta a eficiência por realizar um processo que se feito manualmente seria demorado, além de auxiliar em termos criativos, por explorar prompts que possivelmente um ser humano não pensaria. Também permite escalar de forma muito rápida.


### Métricas de Avaliação: BLEU e ROUGE
As métricas de avaliação são utilizadas para sabermos quais prompts são melhores através de **métricas objetivas**, sendo as mais comuns a *BLEU* e a *ROUGE*.
- **BLEU (Bilingual Evaluation Understudy)**
	É uma métrica originalmente criada para avaliar traduções automáticas, mas que pode ser usada para comparar textos utilizados como referência. Em seu funcionamento, mede a sobreposição de *n-gramas* (sequência de palavras) entre o texto gerado e o texto de referência, onde quanto maior o score do BLEU, mais parecido o texto gerado está em relação ao texto de referência.
- **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)** 
	É uma família de métricas usadas para avaliar a qualidade de resumos automáticos, mas também útil para comparar textos em geral. Seu funcionamento é através da medida de sobreposição de *n-gramas*, palavras ou frases entre o texto gerado de referência, focando em *recall* (quantas informações relevantes foram capturadas). Quanto maior o *score*, melhor o texto gerado cobre o texto de referência.

---
## **Conteúdos Adicionais**

### Exemplo
Imagine que você está treinando um chatbot para receber pedidos de clientes. Você pede ao LLM para gerar 10 variações de prompts como:

- "Gostaria de fazer um pedido."
- "Quero comprar um produto."
- "Posso solicitar um item?"

Depois, você avalia cada frase usando BLEU ou ROUGE, comparando com frases de referência que representam boas práticas de atendimento. As frases com melhores scores são selecionadas para uso ou para uma nova rodada de refinamento.

---
