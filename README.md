# Santander Dev Week 2023 (ETL com Python) 👨‍💼📈🤖

Bem-vindo ao repositório da Santander Dev Week 2023! Aqui você encontrará informações e recursos relacionados ao projeto de ETL (Extração, Transformação e Carga) com Python, conduzido pela DIO em parceria com Santander.

## Contexto 📊📋

Neste projeto, assumimos o papel de cientista de dados no Santander. A nossa missão é aprimorar a interação com os clientes, proporcionando uma experiência personalizada. Vamos utilizar a Inteligência Artificial Generativa para criar mensagens de marketing sob medida, que serão entregues a cada cliente.

## Condições do Problema 📝🔍

Temos uma planilha simples em formato CSV ('SDW2023.csv') contendo uma lista de IDs de usuário do banco. Abaixo está um exemplo do formato:

```
UserID
1
2
3
4
5
```

O desafio consiste nos seguintes passos:

1. Consumir o endpoint GET [https://sdw-2023-prd.up.railway.app/users/{id}](https://sdw-2023-prd.up.railway.app/users/{id}) para obter os dados de cada cliente.
2. Utilizar a API do ChatGPT (OpenAI) para criar mensagens de marketing personalizadas, enfatizando a importância dos investimentos.
3. Atualizar a lista de "news" de cada usuário enviando as informações de volta para a API. Isso será feito usando o endpoint PUT [https://sdw-2023-prd.up.railway.app/users/{id}](https://sdw-2023-prd.up.railway.app/users/{id}).

## Recursos Adicionais 📦🔗

- [API Santander Dev Week 2023](https://sdw-2023-prd.up.railway.app/swagger-ui/index.html)
- [Documentação da API ChatGPT da OpenAI](https://platform.openai.com/docs/api-reference/introduction)


Divirta-se codificando e aprimorando a experiência dos nossos clientes com mensagens personalizadas! 💼🎉📩
