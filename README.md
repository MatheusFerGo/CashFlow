# CashFlow

> **Nota:** Este é um repositório desenvolvido para fins de estudo, com base no conteúdo da plataforma **[Rocketseat](https://www.rocketseat.com.br/)**. O projeto original, que serve como fundamento para este aprendizado, foi criado por **Wellison Arley**.
>
> ➡️ Repositório Original: **[welissonArley/CashFlow](https://github.com/welissonArley/CashFlow.git)**

---

### 📖 Sobre o Projeto Original

Esta API, desenvolvida utilizando **.NET 8**, adota os princípios do **Domain-Driven Design (DDD)** para oferecer uma solução estruturada e eficaz no gerenciamento de despesas pessoais. O principal objetivo é permitir que os usuários registrem suas despesas, detalhando informações como título, data, descrição, valor e tipo de pagamento, com os dados sendo armazenados de forma segura em um banco de dados **MySQL**.

A arquitetura da API baseia-se em **REST**, utilizando métodos HTTP padrão e é complementada por uma documentação **Swagger**, que proporciona uma interface gráfica interativa para explorar e testar os endpoints.

---

### ✨ Features Principais

-   **Arquitetura DDD:** Estrutura modular que facilita o entendimento e a manutenção do domínio.
-   **Testes de Unidade:** Cobertura de testes com `FluentAssertions` para garantir a qualidade e a funcionalidade.
-   **Geração de Relatórios:** Exportação de relatórios detalhados para `.PDF` e `.Excel`.
-   **API RESTful com Swagger:** Interface bem documentada que facilita a integração e os testes.

---

### 🛠️ Tecnologias Utilizadas

![.NET](https://img.shields.io/badge/.NET-8-512BD4?style=for-the-badge&logo=dotnet)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-4479A1?style=for-the-badge)
![AutoMapper](https://img.shields.io/badge/AutoMapper-FF5733?style=for-the-badge)
![FluentValidation](https://img.shields.io/badge/FluentValidation-009975?style=for-the-badge)

---

### 🚀 Começando

Siga os passos abaixo para ter uma cópia do projeto rodando localmente.

#### Pré-requisitos

* [.NET 8 SDK](https://dotnet.microsoft.com/pt-br/download/dotnet/8.0)
* [Visual Studio 2022](https://visualstudio.microsoft.com/pt-br/) ou [VS Code](https://code.visualstudio.com/)
* Um servidor MySQL (local ou em container)

#### Instalação

1.  Clone o repositório para sua máquina local:
    ```bash
    git clone [https://github.com/MatheusFerGo/CashFlow.git](https://github.com/MatheusFerGo/CashFlow.git)
    ```

2.  Navegue até a pasta do projeto:
    ```bash
    cd CashFlow
    ```

3.  Acesse a documentação Swagger para testar os endpoints: `http://localhost:<SUA_PORTA>/swagger`.