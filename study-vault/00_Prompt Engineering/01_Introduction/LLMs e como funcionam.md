---
tags:
  - note
topic: "[[00_Prompt Engineering/01_Introduction/_Introduction|_Introduction]]"
---
# LLMs e como funcionam

---
## **Resumo**
Breve descrição do que será estudado.

---
## **Conceitos Abordados**

### Oque são LLMs?
LLMs (*Large Language Model* ou *Modelo de Linguagem de Grande Porte*), são algoritmos de inteligência artificial treinados para compreender, manipular e gerar linguagem natural (*textos*) em grande escala. Dentre exemplos de LLMs podemos citar (GPT4.1, GPT5, LLama, entre outras...).
Dentre ás principais características de uma LLM podemos destacar:
- **Tamanho:** Possuem o *large* no nome pois os modelos podem possuir bilhões ou até mesmo trilhões de parâmetros.
- **Capacidade de generalização:** Conseguem responder perguntas, criar textos, traduzir idiomas, dentre outras funções;
- **Treinamento:** Os modelos são treinados com um enorme volume de dados retirados de diversas fontes, como a internet, livros, artigos, etc.

### Como funcionam as LLMs?

#### Arquitetura Transformer
A maior parte das LLMs utiliza a arquitetura Transformer. Esta arquitetura é composta por mecanismos de atenção que permitem o modelo *focar* em partes relevantes do texto ao gerar respostas.

#### Processo de treinamento
O modelo lê grandes quantidades de texto e aprende padrões estatísticos de como as palavras e frases se relacionam, ajustando seus parâmetros para prever a próxima palavra em uma sequência, com base no contexto anterior.

#### Geração de Texto
Quando inserimos um prompt, o modelo analisa e gera uma resposta tentando manter a coerência e relevância reconhecendo padrões e probabilidades de ocorrência de palavras e frases, pois a LLM não *entende* o texto como um ser humano.

---
## **Conteúdos Adicionais**

### Exemplo prático
Em um cenário onde a LLM recebe o seguinte prompt:

<center>Explique o que é computação em nuvem</center>

O LLM vai analisar o prompt e buscar padrões de aprendizado sobre *computação em nuvem* e gerar uma resposta com base no assunto visto durante o treinamento.

---
