# 🤖 Chatbot de Curadoria e Acessibilidade para E-commerce

Projeto desenvolvido durante a formação **AWS re/Start**, da **Escola da Nuvem**, com o objetivo de propor uma solução baseada em Inteligência Artificial e arquitetura Serverless para aprimorar a experiência de compra em plataformas de e-commerce, tornando-a mais intuitiva, personalizada e acessível.

---

#  Sobre o projeto

O projeto consiste em um chatbot inteligente capaz de compreender a intenção do usuário por meio de **Processamento de Linguagem Natural (NLP)**, recomendar produtos de forma personalizada e oferecer recursos nativos de acessibilidade para promover uma experiência de compra mais inclusiva.

A solução foi planejada utilizando serviços gerenciados da AWS e fundamentada em uma pesquisa com usuários para identificar as principais dificuldades enfrentadas durante a jornada de compras online.

---

#  Objetivos

- Melhorar a experiência de compra em e-commerce.
- Reduzir dificuldades durante a busca por produtos.
- Tornar a navegação mais acessível.
- Aplicar Inteligência Artificial utilizando arquitetura Serverless na AWS.
- Validar a solução por meio de pesquisa com usuários.

---

#  Problema

A pesquisa realizada identificou diversas dificuldades enfrentadas pelos consumidores durante compras online.

Principais resultados:

- 76,9% sentem falta de informações claras sobre os produtos.
- 69,2% consideram o processo de checkout muito complexo.
- 84,6% utilizariam um chatbot para esclarecer dúvidas técnicas.
- 69,2% afirmam que respostas imediatas aumentariam sua confiança durante a compra.

<img width="2752" height="1536" alt="Principais dificuldades na finalização de compras online" src="https://github.com/user-attachments/assets/da95128d-02b8-4a8f-8bff-75a4b877c509" />

<img width="2752" height="1536" alt="Principais ações de um chatbot na jornada de compra online" src="https://github.com/user-attachments/assets/109ab0ca-7b17-41ec-8bfe-834bbbd04b2a" />



---

#  Solução proposta

Foi projetado um chatbot inteligente capaz de oferecer uma experiência personalizada durante a jornada de compra, utilizando Inteligência Artificial para compreender a intenção do usuário e recomendar produtos de forma mais eficiente.

A solução contempla:

- Curadoria inteligente de produtos utilizando NLP;
- Recomendações personalizadas;
- Interface acessível;
- Alto contraste;
- Ajuste de fonte;
- Integração com catálogo de produtos;
- Arquitetura Serverless baseada em serviços AWS.



---

#  Arquitetura AWS

A solução foi concebida utilizando uma arquitetura Serverless composta pelos seguintes serviços:

## Frontend

- Amazon S3
- Amazon CloudFront

## Segurança

- AWS WAF
- Amazon Cognito
- Amazon API Gateway

## Processamento

- AWS Lambda
- Amazon Lex
- Amazon Kendra

## Banco de Dados

- Amazon DynamoDB
- DynamoDB Streams

## Monitoramento e Analytics

- Amazon CloudWatch
- AWS X-Ray
- Amazon Athena
- Amazon Kinesis Data Firehose
- Amazon QuickSight

<img width="1126" height="458" alt="image" src="https://github.com/user-attachments/assets/8bf24a34-cdc6-468d-b7f9-998e0620b8d7" />


---

#  Fluxo da solução

```text
Usuário
    │
    ▼
CloudFront
    │
    ▼
Amazon S3
    │
    ▼
AWS WAF
    │
    ▼
API Gateway
    │
    ▼
AWS Lambda
    │
 ┌──┴───────────────┐
 ▼                  ▼
Amazon Lex     Amazon Kendra
        │
        ▼
Amazon DynamoDB
        │
        ▼
CloudWatch
Athena
QuickSight
```

---

#  Protótipo

Foi desenvolvido um protótipo funcional da interface do chatbot integrado ao layout de um e-commerce, incluindo recursos de acessibilidade como:

- Alto contraste;
- Ajuste de fonte;
- Interface conversacional;
- Recomendação personalizada de produtos.

<img width="793" height="467" alt="image" src="https://github.com/user-attachments/assets/d313ff06-fdc8-400b-81cd-87111c7f101b" />


---

#  Pesquisa com usuários

Antes da definição da solução foi realizada uma pesquisa para compreender a jornada de compra dos consumidores.

Os resultados permitiram validar as principais dores dos usuários e direcionaram a definição dos requisitos funcionais e da arquitetura proposta.

<img width="790" height="597" alt="image" src="https://github.com/user-attachments/assets/436da098-f745-4517-9c14-afbd23d68e92" />

<img width="2752" height="1536" alt="Principais dificuldades na finalização de compras online" src="https://github.com/user-attachments/assets/0a9a15c1-1e16-4a6a-9e43-5c7bf017210e" />

<img width="2752" height="1536" alt="Principais ações de um chatbot na jornada de compra online" src="https://github.com/user-attachments/assets/e9c05d9a-8c18-4b3a-a86d-5cb48d9976fc" />


---

#  Metodologia

O desenvolvimento do projeto foi organizado utilizando metodologia ágil, dividido em quatro etapas:

## Sprint 1 — Descoberta e Design

- Pesquisa com usuários;
- Definição do escopo do MVP;
- Wireframes;
- Protótipo da interface.

## Sprint 2 — Interface e Acessibilidade

- Desenvolvimento do chat pop-up;
- Implementação de alto contraste;
- Ajuste de fonte;
- Responsividade.

## Sprint 3 — Inteligência Artificial

- Desenvolvimento do módulo NLP;
- Integração com API de produtos;
- Recomendações inteligentes.

## Sprint 4 — Testes e Validação

- Testes de usabilidade;
- Testes de acessibilidade;
- Correções;
- Entrega do MVP.

---

#  Tecnologias utilizadas

## Cloud Computing

- Amazon Web Services (AWS)
- Serverless Architecture

## Inteligência Artificial

- Amazon Lex
- Amazon Kendra
- Natural Language Processing (NLP)

## Desenvolvimento

- HTML
- CSS
- JavaScript

## Banco de Dados

- Amazon DynamoDB

## Segurança

- AWS WAF
- Amazon Cognito

## Observabilidade

- Amazon CloudWatch
- AWS X-Ray
- Amazon Athena
- Amazon QuickSight

---

#  Benefícios esperados

- Melhor experiência durante a jornada de compra.
- Maior acessibilidade para diferentes perfis de usuários.
- Redução do abandono de carrinho.
- Aumento da confiança na tomada de decisão.
- Redução da carga sobre o atendimento humano.
- Arquitetura escalável baseada em serviços gerenciados da AWS.

---

#  Melhorias futuras

- Integração com Amazon Bedrock para IA Generativa;
- Histórico personalizado de conversas;
- Recomendações baseadas no perfil do usuário;
- Pesquisa por voz;
- Dashboard analítico em tempo real;
- Integração com plataformas reais de e-commerce.

---

#  Equipe

Projeto desenvolvido durante a formação **AWS re/Start – Escola da Nuvem**.

**Integrantes:**

- Filipe Ribeiro Rocha
- Lorena Fernandes Carvalho
- Luka Alves Claro
- Melina Nascimento França
- Walison Alves de Souza
