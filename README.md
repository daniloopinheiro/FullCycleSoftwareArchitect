# 🧠 Fluxo de Estudo do Full Cycle para Arquiteto de Software

> Um guia estruturado para desenvolvedores que desejam se tornar arquitetos de software modernos e prontos para ambientes corporativos de alta complexidade.

---

## 🔄 Visão Geral do Fluxo

```mermaid
graph TD
    subgraph Fundamentos_e_Arquitetura [🧱 Fundamentos e Arquitetura]
        direction LR
        A1[📐 Fundamentos de Arquitetura]
        A2[🧩 SOLID Principles]
        A3[📘 Domain Driven Design]
        A4[🛠️ Modelagem Tática]
        A5[🌀 Event Storming]
        A6[🧼 Clean Architecture]
        A7[🏗️ Monolitos vs Microsserviços]
        A8[📡 Event Driven Architecture - EDA]
    end

    subgraph Pratica_Mensageria_Infraestrutura [⚙️ Prática, Mensageria e Infraestrutura]
        direction LR

        B1[✉️ RabbitMQ e Kafka]
        B2[🔐 Autenticação com Keycloak]
        B3[🎥 Projeto Codeflix]
        B4[🧑‍💻 .NET & React]
        B5[📽️ Microsserviço com Go]
        B6[🌳 Git e GitHub Avançado]
        B7[⚙️ Integração Contínua - CI/CD]
        B8[🌐 API Gateway + Kong]
        B9[📈 Observabilidade com OpenTelemetry]
        B10[🏗️ Terraform & Ansible]
        B11[☁️ Deploy em Cloud Providers]
    end

    %% A1 --> A2 --> A3 --> A4 --> A5 --> A6 --> A7 --> A8 --> B1
    %% B1 --> B2 --> B3 --> B4 --> B5 --> B6 --> B7 --> B8 --> B9 --> B10 --> B11

```

---

## 🧱 Etapas e Conteúdos

### 1. 📐 [Fundamentos da Arquitetura de Software](https://github.com/daniloopinheiro/fullcycle-arquiteto-software/blob/main/FundamentosArquiteturaSoftware.md)

* Conceitos básicos, estilos arquiteturais e papel do arquiteto.

### 2. 🧩 [SOLID Principles](https://github.com/daniloopinheiro/fullcycle-arquiteto-software/blob/main/SOLIDPrinciples.md)

* Princípios de design para sistemas sustentáveis.

### 3. 📘 Domain Driven Design (DDD)

* Entidades, Agregados, Repositórios e Contexto Delimitado.

### 4. 🛠️ Modelagem Tática em DDD

* Value Objects, Factories, Services, Specifications.

### 5. 🌀 Event Storming na Prática

* Descoberta colaborativa de eventos e fluxo de negócio.

### 6. 🧼 Arquitetura Hexagonal e Clean Architecture

* Separação de preocupações, Ports & Adapters, Onion Architecture.

### 7. 🏗️ Sistemas Monolíticos vs. Microsserviços

* Estratégias, trade-offs e aplicação prática.

### 8. 📡 Event Driven Architecture (EDA)

* Event Sourcing, CQRS, mensageria assíncrona.

### 9. ✉️ RabbitMQ e Apache Kafka

* Comparação e aplicação dos brokers de mensagem.

### 10. 🔐 Autenticação e Keycloak

* OpenID Connect, OAuth2, arquitetura segura com Keycloak.

---

## 🧪 Projetos e Prática

### 11. 🎥 Projeto Prático: Codeflix

* Clean Architecture + DDD + TDD em .NET.

### 12. 🧑‍💻 Tecnologias de Desenvolvimento

* **.NET**: APIs modernas, WebJobs, CQRS, Dapper.
* **React**: SPA, Hooks, Gerenciamento de estado.

### 13. 📽️ Microsserviço de Encoder de Vídeo com Go

* Microsserviço real com Kafka + Mongo + Docker.

---

## 🛠️ Práticas DevOps e Operacionais

### 14. 🌳 Git e GitHub Avançado

* GitFlow, trunk-based, GitOps com GitHub Actions.

### 15. ⚙️ Integração Contínua (CI/CD)

* Automatização de builds, testes e deploys.

### 16. 🌐 API Gateway

* Padrões de roteamento, segurança e controle de tráfego.

### 17. 🔀 Kong + Kubernetes

* Kong Gateway + Ingress Controller + Service Mesh.

### 18. 📈 Observabilidade com OpenTelemetry

* Logs, métricas e tracing distribuído.

### 19. 🏗️ Infraestrutura como Código (IaC)

* Terraform: provisionamento
* Ansible: configuração automatizada

### 20. ☁️ Deploy em Cloud Providers

* AWS, Azure e GCP com foco em arquitetura escalável e resiliente.

---

## ✅ Conclusão

Esse fluxo constrói uma base sólida de teoria e prática para arquitetos de software, com foco em **design, escalabilidade, mensageria, segurança, infraestrutura moderna e observabilidade**.

> 📌 **Dica**: Utilize ferramentas como [Whimsical](https://whimsical.com), [Lucidchart](https://lucidchart.com) ou [Mermaid Live Editor](https://mermaid.live/edit) para gerar e editar seus diagramas.

---

## 📬 Entre em Contato

Para **colaboração, dúvidas ou consultoria**, entre em contato:

* ✉️ Pessoal: [daniloopro@gmail.com](mailto:daniloopro@gmail.com)
* 🏢 DevsFree: [devsfree@devsfree.com.br](mailto:devsfree@devsfree.com.br)
* 📊 dopme.io: [contato@dopme.io](mailto:contato@dopme.io)
* 💼 LinkedIn: [Danilo O. Pinheiro](https://www.linkedin.com/in/daniloopinheiro)
