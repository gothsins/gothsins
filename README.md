<h1 align="center">Guilherme Almeida</h1>

<p align="center">
  Desenvolvedor Backend Java em formação, construindo APIs e sistemas com foco em segurança, arquitetura e evolução contínua.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/almeida-guilherme1999/">
    <img src="https://img.shields.io/badge/LinkedIn-Guilherme%20Almeida-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/gothsins">
    <img src="https://img.shields.io/badge/GitHub-gothsins-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

---

## Sobre mim

Sou estudante de **Análise e Desenvolvimento de Sistemas** e concentro meus estudos em desenvolvimento backend com **Java 21** e **Spring Boot**.

Gosto de construir projetos que vão além do CRUD básico e me forcem a entender melhor os problemas por trás da aplicação: autenticação, autorização, modelagem de dados, mensageria, cache, processamento assíncrono, testes e infraestrutura.

Tenho usado meus projetos como ambiente de aprendizado prático, tentando não apenas fazer uma funcionalidade funcionar, mas também entender **por que determinada solução faz sentido, como testá-la e como ela pode evoluir**.

Atualmente busco minha primeira oportunidade profissional em **desenvolvimento de software**, com foco especial em backend Java.

---

## Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square" />
</p>

### Dados e mensageria

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
</p>

### Testes, documentação e infraestrutura

<p>
  <img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Mockito-Testes-6DB33F?style=flat-square" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" />
</p>

---

## Projetos em destaque

### [finance-api](https://github.com/gothsins/finance-api)

API REST para gerenciamento de finanças pessoais, construída com foco em segurança, isolamento de dados por usuário e evolução de uma aplicação backend além de operações CRUD tradicionais.

**Principais pontos:**

- autenticação stateless com Spring Security e JWT
- isolamento de dados por usuário
- filtros dinâmicos e paginação com JPA Specification
- cache com Redis e invalidação automática
- comunicação assíncrona via RabbitMQ
- processamento em lote com Spring Batch
- testes unitários e de integração
- documentação com Swagger/OpenAPI
- Docker e Docker Compose
- pipeline de CI com GitHub Actions
- deploy em produção

<p>
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

---

### [flowboard-api](https://github.com/gothsins/flowboard-api)

Backend orientado a eventos que explora processamento assíncrono, comunicação em tempo real e autorização em diferentes níveis.

Foi desenvolvido principalmente para estudar problemas que não estavam presentes no `finance-api`, especialmente **Kafka, WebSocket, controle de acesso e resiliência no processamento de eventos**.

**Principais pontos:**

- Apache Kafka como base para processamento de eventos
- controle de idempotência
- retry com backoff e Dead Letter Topic
- comunicação em tempo real com WebSocket/STOMP
- autenticação JWT
- RBAC e autorização baseada no recurso
- autenticação e ACLs no Kafka
- rate limiting
- tratamento de vulnerabilidade XSS e Content-Security-Policy
- Docker Compose
- deploy na AWS EC2
- testes para comportamentos críticos do consumidor Kafka

<p>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/WebSocket-STOMP-4A154B?style=flat-square" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white" />
</p>

---

## Em desenvolvimento

Esses projetos ainda estão evoluindo. Prefiro mantê-los aqui como registro do que estou construindo atualmente, sem apresentá-los como produtos finalizados.

### [Questlog](https://github.com/gothsins/questlog)

Aplicação **full stack** para organizar biblioteca de jogos, acompanhar progresso, avaliações e histórico.

O backend está sendo desenvolvido com:

- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Flyway

O frontend faz parte da próxima etapa do projeto.

<p>
  <img src="https://img.shields.io/badge/Status-Em_desenvolvimento-F7B731?style=flat-square" />
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" />
</p>

---

### [HookForge](https://github.com/gothsins/hookforge-api)

Projeto em desenvolvimento criado para me levar além do que já implementei nos projetos anteriores.

A proposta é utilizá-lo para aprofundar decisões de arquitetura, modelagem, testes e construção de uma aplicação de maior escopo conforme o projeto amadurece.

Ainda está nas primeiras etapas, portanto arquitetura e funcionalidades podem mudar bastante durante o desenvolvimento.

<p>
  <img src="https://img.shields.io/badge/Status-Em_desenvolvimento-F7B731?style=flat-square" />
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
</p>

---

## Atualmente

- aprofundando meus conhecimentos em Java e Spring
- evoluindo o Questlog e o HookForge
- estudando arquitetura e qualidade de código através de projetos práticos
- buscando minha primeira oportunidade profissional em desenvolvimento de software

---

<p align="center">
  <a href="https://www.linkedin.com/in/almeida-guilherme1999/">
    <img src="https://img.shields.io/badge/LinkedIn-Vamos%20conversar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
