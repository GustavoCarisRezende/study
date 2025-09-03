---
tags:
  - note
topic: "[[00_Prompt Engineering/03_Output Control/_Output Control|_Output Control]]"
---
# Max Tokens

---
## **Resumo**
**Max Tokens** é um parâmetro utilizado em LLMs para definir o número máximo de tokens que podem ser geradas em uma resposta.

---
## **Conceitos Abordados**

### Por que controlar o número de tokens?
Controlar o número de tokens é de extrema importância, pois com isso podemos por exemplo **limitar o tamanho da resposta**, evitando respostas excessivamente longas ou curtas, garantindo um output correto de acordo com o contexto. Além disso podemos controlar o **gerenciamento de recursos**, pois as LLMs consomem recursos computacionais proporcionalmente ao número de tokens gerados.
Em casos sensíveis, esta limitação pode **prevenir vazamento de informações** em cenários sensíveis.

---
## **Conteúdos Adicionais**

### Exemplo Prático

Imagine que você está desenvolvendo um chatbot para atendimento ao cliente e deseja que cada resposta tenha, no máximo, 100 tokens:

```
Usuário: Explique o que é computação em nuvem. Modelo (com max_tokens = 100): Computação em nuvem é um modelo de entrega de serviços de TI onde recursos como servidores, armazenamento e aplicativos são disponibilizados pela internet. Isso permite que empresas e usuários acessem e utilizem esses recursos sob demanda, sem a necessidade de investir em infraestrutura própria...
```

---
