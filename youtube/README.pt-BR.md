# YouTube

## .NET

- [.NET 8 - Compilação Nativa AOT (Jose Carlos Macoratti)](https://www.youtube.com/watch?v=hKa2dSRtqpk): Introdução teórica e prática à compilação Ahead-of-Time (Native AOT) no .NET 8, comparando-a com a compilação JIT e demonstrando como reduzir o tempo de inicialização e o consumo de memória em Minimal APIs.
- [.NET Project Setup From Scratch Using These 6 Best Practices (Milan Jovanović)](https://www.youtube.com/watch?v=QRgtcbxJlo0): Guia com 6 práticas essenciais para estruturar um projeto .NET do zero, cobrindo `.editorconfig`, `Directory.Build.props`, gerenciamento centralizado de pacotes, análise estática de código, Docker/.NET Aspire e CI/CD.
- [5 HttpClient Best Practices Every .NET Dev Should Know (Milan Jovanović)](https://www.youtube.com/watch?v=djRxEwzoIWc): Melhores práticas para o uso eficiente do `HttpClient` no .NET, abordando descarte adequado, Named Clients, Typed Clients, desserialização fortemente tipada, Service Discovery e políticas de resiliência.
- [ASP.NET - Tratamento Global de erros : IExceptionHandler (Jose Carlos Macoratti)](https://www.youtube.com/watch?v=U6Wyq2a_xpk): Tutorial sobre como centralizar o tratamento de exceções em APIs ASP.NET Core usando a interface `IExceptionHandler` e padronizando respostas de erro no formato Problem Details (RFC 7807).
- [Best Practices for Hashing and Salting Passwords in .NET (Code Maze)](https://www.youtube.com/watch?v=Sh_PxjTmBug): Guia de segurança sobre armazenamento de senhas em C# utilizando o algoritmo nativo PBKDF2, geração de salts criptográficos exclusivos por usuário e verificação segura contra timing attacks.
- [C# - Acelere seu código com Span e ReadOnlySpan (Jose Carlos Macoratti)](https://www.youtube.com/watch?v=YdWyquvIbZA): Demonstração prática de como usar `Span<T>` e `ReadOnlySpan<T>` para manipular strings e arrays com alta performance e zero alocações na memória Heap, aliviando a pressão sobre o Garbage Collector.
- [Create an Event-Driven AWS Workflow in .NET (S3 + SQS + SES) (Milan Jovanović)](https://www.youtube.com/watch?v=-mQB3ONeBig): Construção de uma arquitetura orientada a eventos no .NET integrando Amazon S3 para upload de arquivos, Amazon SQS para filas de processamento em segundo plano e Amazon SES para envio de e-mails.
- [JWT Authentication with ASP.NET Core Identity Done Right (Milan Jovanović)](https://www.youtube.com/watch?v=-feKtsYWMy0): Passo a passo para implementar autenticação baseada em Tokens JWT (incluindo claims e roles) integrada ao ASP.NET Core Identity, substituindo o comportamento padrão baseado em cookies.
- [Make Your HttpClient Resilient - Circuit Breaker, Retry, Timeout (Milan Jovanović)](https://www.youtube.com/watch?v=aVyCa1RhZIc): Como configurar pipelines de resiliência no `HttpClient` com Polly e `Microsoft.Extensions.Http.Resilience`, aplicando estratégias de Timeout, Retry (com backoff exponencial e jitter) e Circuit Breaker.
- [Most .NET Devs Don’t Know This AWS Messaging Library Exists (Milan Jovanović)](https://www.youtube.com/watch?v=wmsioOgVTmI): Apresentação da biblioteca oficial `AWS.Messaging` para simplificar a publicação e o consumo de mensagens em filas SQS e tópicos SNS no .NET, com suporte nativo a retries e OpenTelemetry.
- [Rate Limiting Minimal APIs and Controllers the Right Way (Milan Jovanović)](https://www.youtube.com/watch?v=92_320zm5Uo): Implementação de limitação de taxa (*Rate Limiting*) particionada por usuário autenticado em Minimal APIs e Controllers, incluindo personalização de headers (`Retry-After`) e respostas `429` em Problem Details.
- [The Secret to FREE PDF Reporting in .NET – Handlebars + PuppeteerSharp (Milan Jovanović)](https://www.youtube.com/watch?v=XkhQLnO6v-Y): Solução gratuita para geração de relatórios PDF estilizados em .NET combinando templates HTML dinâmicos com Handlebars.Net e renderização via navegador headless com PuppeteerSharp.
- [This .NET Monitoring Setup Changes Everything: Grafana + OpenTelemetry (Milan Jovanović)](https://www.youtube.com/watch?v=FNcBtd4lGlM): Configuração de uma stack completa de observabilidade em aplicações distribuídas .NET exportando métricas, logs estruturados e traces via OpenTelemetry (OTLP) para o Grafana Cloud.
- [Todo dev .NET deve saber responder estas perguntas na entrevista! | por André Baltieri (balta)](https://www.youtube.com/watch?v=cmaVEOqBKKY): Compilado de 20 perguntas técnicas essenciais para entrevistas de C# e .NET divididas por nível de experiência (Estagiário, Júnior, Pleno e Sênior), cobrindo fundamentos, POO, SOLID, arquitetura e estimativas.

## AWS

- [AWS Certified Cloud Practitioner Certification Course 2026 (CLF-C02) - Pass the Exam (freeCodeCamp.org)](https://www.youtube.com/watch?v=7HKot-brXFE): Curso preparatório completo para a certificação AWS Certified Cloud Practitioner (CLF-C02), cobrindo conceitos fundamentais de computação em nuvem, segurança, compliance, arquitetura e serviços essenciais da AWS.
- [AWS Solutions Architect Associate Certification (SAA-C03) – Full Course to PASS the Exam (freeCodeCamp.org)](https://www.youtube.com/watch?v=c3Cn4xYfxJY): Curso completo voltado para a preparação e aprovação no exame de certificação AWS Solutions Architect Associate (SAA-C03).
- [AWS Solutions Architect Professional (SAP-C02) Certification Course – Pass the Exam (freeCodeCamp.org)](https://www.youtube.com/watch?v=hyEw7dQ9-JE): Guia avançado e abrangente para a certificação de nível profissional AWS Solutions Architect Professional (SAP-C02).

## Banco de dados

- [I replaced my entire stack with Postgres (The Coding Gopher)](https://www.youtube.com/watch?v=TdondBmyNXc): Exploração de como o PostgreSQL pode ser estendido com extensões e recursos avançados (como JSONB, PG Vector, Full-Text Search e filas nativas) para substituir ferramentas e serviços externos de uma aplicação.
- [O QUE NINGUÉM TE ENSINOU SOBRE BUSCAS INTELIGENTES NO BANCO DE DADOS](https://www.youtube.com/watch?v=UYOr-rpQs1I): Exploração das limitações do operador LIKE e de como implementar buscas eficientes e inteligentes utilizando Full-Text Search no MySQL e no PostgreSQL (com índices GIN, lexemas e relevância).
- [Postgres Just Got It's Biggest Upgrade In Years](https://www.youtube.com/watch?v=4Lmqvn_yz-c): Apresentação da extensão PG Durable (desenvolvida pela Microsoft), que permite gerenciar funções duráveis, filas, agendamentos e fluxos de trabalho complexos diretamente dentro do PostgreSQL.

## Desenvolvimento local

- [Desenvolvimento local usando AWS com Localstack](https://www.youtube.com/watch?v=1ow0NQv5Fsk): Demonstração prático-teórica do uso do LocalStack para simular serviços da AWS (como EC2, S3, DynamoDB, Lambda, SQS e Step Functions) localmente via Docker, permitindo testes e provisionamento offline sem custos.
- [Serverless .NET: API Gateway → Lambda → SNS/SQS (End-to-End)](https://www.youtube.com/watch?v=3MljS7isZD8): Explicação passo a passo da construção de uma arquitetura serverless em .NET (utilizando .NET Aspire, AWS Lambda, API Gateway, SNS e SQS) com testes locais e instrumentação via OpenTelemetry.
- [SIMULANDO AWS COM LOCALSTACK E TERRAFORM: GUIA COMPLETO](https://www.youtube.com/watch?v=0nU9yvqg2Rw): Guia completo sobre como integrar o LocalStack com o Terraform para provisionar e gerenciar infraestrutura simulada da AWS na própria máquina, evitando gastos e custos em nuvem.

## Front-end

- [No Bullshit Guide to Making Modern Websites](https://www.youtube.com/watch?v=WAV66F-Zbio)
- [No Bullshit Guide to Website Accessibility](https://www.youtube.com/watch?v=9_QsCBg-Evg)
- [The Only CSS Reset Guide You'll Ever Need](https://www.youtube.com/watch?v=0RX6nvacS7o)

## IA

- [5 MCPs que eu uso na prática para programar com IA (Claude Code + Cursor)](https://www.youtube.com/watch?v=PZzWx3lTf0E)
- [5 skills que eu uso todos os dias para programar com IA (+ BÔNUS)](https://www.youtube.com/watch?v=Q_vuCJ6Y4yk)
- [Arquitetura de Sistema de Agentes de IA segundo a Anthropic](https://www.youtube.com/watch?v=mHB8BbUhqoo)
- [Build a Receipt Scanner App in .NET and Local AI with Ollama](https://www.youtube.com/watch?v=XZYzW3z-C1w)
- [Claude Certified Architect - Foundations – Prepare for and pass the exam](https://www.youtube.com/watch?v=reDRM0tqhNs)
- [Claude Code - Usando o OpenSpec para a abordagem SDD](https://www.youtube.com/watch?v=VhWrM6q8Das)
- [Como CRIAR um Agente de IA RAG PERFEITO (5 passos)](https://www.youtube.com/watch?v=LZoLvV7p25A)
- [Engenharia de Prompt: O Guia Definitivo](https://www.youtube.com/watch?v=1VDcke66TRE)
- [Learn Every AI Agent Pattern From One Video (I Actually Ran All 35)](https://www.youtube.com/watch?v=PZsJfBVDZZc)
- [NLP, LLM, RAG, MCP, Agents: o guia definitivo para devs](https://www.youtube.com/watch?v=_-zE9mZVGWc)
- [Ollama + OpenWebUI - Seu ChatGPT pessoal e gratuito](https://www.youtube.com/watch?v=DzV7DcFprSE)
- [Pi Agent: o jeito minimalista de programar com IA (GUIA COMPLETO)](https://www.youtube.com/watch?v=YMc0f5i70Hc)
- [Someone Built Ollama for Audio… and It Runs Locally](https://www.youtube.com/watch?v=CvZuuKkT3Sw)

## Observabilidade

- [OpenTelemetry na Prática: Monitore Qualquer App com Custo Zero](https://www.youtube.com/watch?v=Wu0Ajkxh69Y)

## System design

- [65.000 Transações por Segundo! Por Que a Visa Nunca Pode Cair](https://www.youtube.com/watch?v=DDKwF8Cfcx8)
- [A Arquitetura do Pix — Como 150 Milhões de Transações/Dia São Processadas](https://www.youtube.com/watch?v=muu3zlOfnX0)
- [ARQUITETANDO O GOOGLE DRIVE NA PRÁTICA | SYSTEM DESIGN](https://www.youtube.com/watch?v=qMPfjCH3qQU)
- [ARQUITETANDO O TICKETMASTER NA PRÁTICA | SYSTEM DESIGN](https://www.youtube.com/watch?v=3XSijmIZxXU)
- [ARQUITETANDO O YOUTUBE NA PRÁTICA | SYSTEM DESIGN](https://www.youtube.com/watch?v=JBivKeZVex0)
- [Arquitetando um Encurtador de URL: O Maior Desafio dos Programadores em Entrevistas de System Design](https://www.youtube.com/watch?v=m_anIoKW7Jg)
- [ARQUITETURA BACKEND DO FACEBOOK | System Design](https://www.youtube.com/watch?v=6bTkTy6DjOQ)
- [Arquitetura Orientada a Eventos | O Guia Completo para ESCALAR MICROSSERVIÇOS do Jeito Certo](https://www.youtube.com/watch?v=8xFBQc1A4B8)
- [Como Escolher o Banco de Dados Correto pra sua Aplicação | System Design & Arquitetura de Software](https://www.youtube.com/watch?v=bhw4-Kq_RPs)
- [Como o Instagram Gera Bilhões de IDs Sem Servidor Central — Snowflake ID e Sharding (System Design)](https://www.youtube.com/watch?v=xod55ie5TDY)
- [Design a Payment System - System Design Interview](https://www.youtube.com/watch?v=olfaBgJrUBI)
- [É isso que um SENIOR precisa saber sobre SYSTEM DESIGN](https://www.youtube.com/watch?v=yaNjUYg6yY0)
- [Quanto de System Design você precisa saber](https://www.youtube.com/watch?v=EWzVZA_qTEw)
- [Real Life AWS Architecture Examples - Amazon Alexa](https://www.youtube.com/watch?v=TQg_RFqIlkA)
- [Real Life AWS Architecture Examples - Text To Speech](https://www.youtube.com/watch?v=ciTtw6aauIU)
- [System Design começa por esses Building Blocks](https://www.youtube.com/watch?v=ycaLfuBsfd4)
- [System Design: A Arquitetura do Nubank Explicada (Kafka, Datomic e Clojure)](https://www.youtube.com/watch?v=3oeHz3sFKWI)
- [System Design: Como o Twitter escala para 500M de Tweets por Dia?](https://www.youtube.com/watch?v=JgjPp4sfeqY)
- [System Design: Netflix NÃO usa AWS? Então como funciona?](https://www.youtube.com/watch?v=L7N6LgdnbNs)
- [System Design: Por que a Amazon criou o DynamoDB](https://www.youtube.com/watch?v=vOSn1cXGqRM)
- [System Design: Por que o LinkedIn precisou criar o Kafka](https://www.youtube.com/watch?v=ry_Nzm1HCGk)
- [System Design Course – APIs, Databases, Caching, CDNs, Load Balancing & Production Infra](https://www.youtube.com/watch?v=C842vFY5kRo)
- [System Design Global Payment Processing | Paypal](https://www.youtube.com/watch?v=7MXV7RfNtv0)
