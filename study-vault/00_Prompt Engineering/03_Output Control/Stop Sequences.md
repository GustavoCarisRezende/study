---
tags:
  - note
topic: "[[00_Prompt Engineering/03_Output Control/_Output Control|_Output Control]]"
---
# Stop Sequences

---
## **Resumo**
**Stop Sequences** são parâmetros que indicam ao modelo de linguagem (LLM) exatamente onde ele deve interromper a geração de texto. Uma **stop sequence** é uma cadeia de caracteres (palavras, símbolo ou conjunto de palavras) que, ao ser detectada durante a geração, faz com que o modelo para imediatamente de produzir tokens.

---
## **Conceitos Abordados**

### Por que usar Stop Sequences?
O uso de stop sequences é de extrema importância para **delimitar respostas**, garantindo que o modelo não ultrapasse um ponto específico, como o fim de uma frase ou um bloco de código. Além disso **evita outputs indesejados** e impede que o modelo continue gerando textos além do necessário, oque pode incluir informações irrelevantes ou sensíveis.

---
## **Conteúdos Adicionais**

### Exemplo Prático
Imagine que você está desenvolvendo um sistema que gera respostas em formato de lista, e quer que o modelo pare ao encontrar o marcador `"FIM DA LISTA"`:

`Prompt: Liste três vantagens da computação em nuvem. Termine com "FIM DA LISTA". Modelo:  1. Escalabilidade 2. Redução de custos 3. Flexibilidade FIM DA LISTA`

Ao configurar `"FIM DA LISTA"` como stop sequence, o modelo interrompe a geração assim que esse texto aparece, evitando que continue escrevendo além do desejado.

---
