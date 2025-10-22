# 🧠 NeoDesk — Plataforma Inteligente de Suporte Técnico

<p align="center">
  <img src="docs/img/logo-inovatech.png" alt="logo da InovaTech" width="200">
  <h3 align="center">InovaTech Solutions</h3>
  <p align="center">Status do Projeto: <b>Em desenvolvimento 🚧</b></p>
</p>

---

## 🗂️ Índice

1. [Resumo](#resumo)  
2. [Desafio](#desafio)  
3. [Solução](#solução)  
4. [Principais Funcionalidades](#principais-funcionalidades)  
5. [Backlog do Produto](#backlog-do-produto)  
6. [DoR (Definition of Ready)](#dor-definition-of-ready)  
7. [DoD (Definition of Done)](#dod-definition-of-done)  
8. [Cronograma de Sprints](#cronograma-de-sprints)  
9. [Tecnologias](#tecnologias)  
10. [Manual de Instalação (Quickstart)](#manual-de-instalação-quickstart)  
11. [Como Contribuir](#como-contribuir)  
12. [Equipe](#equipe)  
13. [Links Úteis](#links-úteis)  
14. [Licença](#licença)

---

## 🧾 Resumo

O **NeoDesk** é uma plataforma moderna e escalável de **suporte técnico inteligente**, que integra **automação** e **inteligência artificial** para triagem inicial, priorização automática de tickets e geração de insights para melhorar a gestão de atendimento técnico.

---

## 🚧 Desafio

Desenvolver uma solução de Helpdesk inteligente para a **InovaTech** que:

- 💬 Ofereça atendimento **24/7** via assistente virtual.  
- ⚙️ Realize **triagem automatizada de chamados**.  
- 📚 Disponibilize uma **base de conhecimento dinâmica**.  
- 📊 Gere **dashboards e relatórios gerenciais**.  
- 🔒 Garanta **conformidade com a LGPD**.  

---

## 💡 Solução

O **NeoDesk** combina:

- 🤖 **Assistente Virtual de IA** para triagem e resolução de casos simples.  
- 🎫 **Gerenciador de Tickets** com priorização automática.  
- 📚 **Base de Conhecimento Inteligente** que aprende com as interações.  
- 📊 **Painel Analítico** com métricas de desempenho.  
- 🔒 **Segurança e auditoria** para aderência à LGPD.  

---

## ⚙️ Principais Funcionalidades

| 🧩 Funcionalidade | 💬 Descrição |
|------------------|-------------|
| 🤖 **Assistente Virtual (IA)** | Triagem e resolução automatizada de chamados. |
| 🎫 **Gerenciamento de Tickets** | Registro, priorização e filtros inteligentes. |
| 📚 **Base de Conhecimento** | Aprendizado contínuo com interações. |
| 📊 **Dashboard Analítico** | Métricas e relatórios gerenciais. |
| 🔒 **Conformidade LGPD** | Controle de acesso e trilhas de auditoria. |

---

## 📋 Backlog do Produto

| 🏅 **Rank** | ⚙️ **Prioridade** | 🧠 **User Story** | 🎯 **Story Points** | 🏁 **Sprint** | 🔖 **Requisito** | 📊 **Status** |
|:-----------:|:----------------:|:-----------------|:------------------:|:-------------:|:----------------:|:--------------:|
| **1** | 🔴 Alta | Login com autenticação segura | 8 | 1 | R09 | ✅ Concluído |
| **2** | 🔴 Alta | Abrir chamado via assistente virtual | 13 | 2 | R01 | 🚧 Em desenvolvimento |
| **3** | 🔴 Alta | Visualizar e priorizar chamados automaticamente | 21 | 2 | R02 | 🚧 Em desenvolvimento |
| **4** | 🔴 Alta | IA tenta resolver antes do atendimento humano | 34 | 2 | R01 | 🚧 Em desenvolvimento |
| **5** | 🟠 Média | Painel com métricas e gráficos | 20 | 4 | R04 | ⏳ Aguardando início |
| **6** | 🟠 Média | Notificações sobre status de chamados | 13 | 3 | R03 | ⏳ Aguardando início |
| **7** | 🟠 Média | Consulta à base de conhecimento | 16 | 3 | R03 | ⏳ Aguardando início |
| **8** | 🟢 Baixa | Exportar relatórios em PDF | 8 | 4 | R04 | ⏳ Aguardando início |
| **9** | 🟢 Baixa | Auditoria de ações (LGPD) | 12 | 4 | R09 | ⏳ Aguardando início |

**Legenda:**  
✅ Concluído · 🚧 Em desenvolvimento · ⏳ Aguardando início  

---

## 🧩 DoR — *Definition of Ready*

Uma User Story está pronta para entrar em desenvolvimento quando:

- [x] Critérios de aceitação documentados  
- [x] Modelagem do banco concluída  
- [x] Protótipos validados no Figma  
- [x] Requisitos técnicos revisados  
- [x] Estrutura inicial do repositório configurada  

---

## 🧪 DoD — *Definition of Done*

Uma tarefa é considerada finalizada quando:

- [x] Código testado e versionado no GitHub  
- [x] Banco de dados funcional e populado (seed)  
- [x] Manual de instalação e usuário atualizado  
- [x] Testes de integração realizados  
- [x] Documentação e apresentação publicadas  

---

## 🗓️ Cronograma de Sprints

| 🏁 **Sprint** | 📅 **Período** | 🎯 **Objetivo Principal** |
|:-------------:|:--------------:|:--------------------------|
| Sprint 1 | 01/08 – 21/08 | Implementação do login e estrutura base |
| Sprint 2 | 22/08 – 12/09 | Assistente virtual e módulo de tickets |
| Sprint 3 | 13/09 – 02/10 | Base de conhecimento e notificações |
| Sprint 4 | 03/10 – 23/10 | Dashboard e auditoria de logs |

---

## 💻 Tecnologias

| Camada | Tecnologias |
|:-------|:-------------|
| **Backend** | C# / .NET |
| **Banco de Dados** | Microsoft SQL Server |
| **Frontend** | React |
| **Design / UI** | Figma |
| **Versionamento** | Git / GitHub |

---

## ⚡ Manual de Instalação (Quickstart)

### 🧱 Pré-requisitos
- [.NET SDK](https://dotnet.microsoft.com/en-us/download)  
- [Node.js (v16+)](https://nodejs.org/)  
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)  
- [Git](https://git-scm.com/)  

---

### 📥 Clone o Repositório
```bash
git clone https://github.com/SEU_USUARIO/neoDesk.git
cd neoDesk
