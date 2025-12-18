# 🎯 HabitsHub – API de Gestão de Hábitos e Rotina

[![.NET](https://img.shields.io/badge/.NET-8.0-512bd4)](https://dotnet.microsoft.com/download)
[![EF Core](https://img.shields.io/badge/EF%20Core-SQLite-blue)](https://learn.microsoft.com/ef/core/)

O **HabitsHub** é uma API robusta desenvolvida para ajudar usuários a manterem a consistência em suas rotinas. O grande diferencial é o **Sistema de Streaks (Ofensivas)**, que calcula automaticamente quantos dias consecutivos o usuário realizou uma tarefa, inspirado em apps como o Duolingo.



## 🚀 Funcionalidades Principais
- **CRUD de Hábitos**: Gerencie suas metas diárias.
- **Lógica de Streaks**: 
  - Incrementa o contador ao realizar a tarefa em dias seguidos.
  - Mantém o recorde histórico (`Longest Streak`).
  - Reseta automaticamente se o usuário pular um dia.
- **Persistência Local**: Utiliza SQLite para facilitar a execução sem configurações complexas de infraestrutura.
- **Arquitetura em Camadas**: Organização clara entre Domínio, Infraestrutura e API.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** C#
- **Framework:** ASP.NET Core 8
- **ORM:** Entity Framework Core
- **Banco de Dados:** SQLite
- **Documentação:** Swagger (OpenAPI)

## 🏗️ Estrutura do Projeto
- `HabitsHub.Core`: Entidades de domínio e regras de negócio (Lógica de Streaks).
- `HabitsHub.Infrastructure`: Contexto do banco de dados e mapeamentos.
- `HabitsHub.API`: Controllers e configuração da injeção de dependência.

## 🏁 Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone [https://github.com/jmarcosaraujo/HabitsHub.git](https://github.com/jmarcosaraujo/HabitsHub.git)
