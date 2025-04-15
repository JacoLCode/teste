<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Projeto Helpdesk com IA</title>
</head>
<body>

<div align="center">
    <img src="../assets/capa-readme-documentation.png" alt="capa-readme" width="100%" />
</div>

<br>

# Projeto Helpdesk com Inteligência Artificial

## Introdução
O projeto **Helpdesk com IA** tem como objetivo desenvolver um sistema de atendimento técnico com funcionalidades modernas de abertura, acompanhamento e resolução de chamados. A solução incorpora inteligência artificial para melhorar a experiência do usuário, oferecer automações e gerar insights úteis para a equipe de suporte.

## Objetivo
Criar um sistema robusto de helpdesk que auxilie usuários e técnicos no registro, acompanhamento e resolução eficiente de demandas, garantindo agilidade, organização e relatórios analíticos. O projeto será desenvolvido em ciclos ágeis utilizando a metodologia Scrum.

---

# Tecnologias Utilizadas
- **Banco de Dados**: MySQL ou PostgreSQL
- **Frameworks e Bibliotecas**: Bootstrap, Express / Flask
- **Ferramentas**: Git, GitHub, Postman, Figma
- **Inteligência Artificial**: (a definir - ex: NLP para análise de chamados, classificação automática etc.)

---

# Instalação e Execução

### Pré-requisitos
- Banco de dados configurado
- Git instalado

### Passos
```bash
# Clone o repositório
$ git clone https://github.com/seu-usuario/helpdesk-ia.git

# Acesse a pasta do projeto
$ cd helpdesk-ia

# Instale as dependências (Node.js)
$ npm install

# ou (Python)
$ pip install -r requirements.txt

# Inicie o sistema
$ npm start
# ou
$ python app.py
```

---

# Planejamento das Sprints

Este documento apresenta o planejamento detalhado das sprints para o desenvolvimento de um sistema de Helpdesk com Inteligência Artificial.

<details>
<summary><strong>Sprint 1 - Estrutura Básica do Sistema</strong></summary>

## User Stories

### PAS - 02 - Cadastro de Chamados
- Permitir que usuários registrem chamados.
- Campo para descrição detalhada.
- Upload de anexos (imagens/documentos).
- Notificação de status ao usuário.

### PAS - 08 - Gestão de Chamados
- Painel para visualizar e alterar chamados.
- Sistema de categorias.
- Atribuição de chamados a atendentes.

### PAS - 14 - Prioridade do Chamado
- Opção de prioridade: Baixa, Média, Alta, Crítica.
- Permitir que atendentes alterem prioridade.

### PAS - 12 - Comentários e Interação
- Sistema de comentários.
- Histórico de interações.

### PAS - 16 - Status de Chamado
- Criar status configuráveis (Aberto, Em andamento, Resolvido etc).
- Administração dos status pelo gestor.

### PAS - 18 - Histórico de Chamados
- Registro de mudanças.
- Interface para visualização do histórico.

## Definition of Done
- Código funcional no GitHub.
- Layouts implementados.
- Funcionalidades integradas ao sistema.
- Testes realizados e aprovados.

## Definition of Ready
- User stories claras e com critérios definidos.
- Wireframes disponíveis para cada funcionalidade.

## Burndown
<img src="BurnDown/BurnDown_Sprint1.PNG" alt="Burndown Sprint 1" width="100%" />

</details>

<details>
<summary><strong>Sprint 2 - Filtros e Métricas</strong></summary>

## User Stories

### PAS - 04 - Pesquisa e Filtros
- Busca por palavra-chave, ID e usuário.
- Filtros por data, status, prioridade e categoria.

### PAS - 09 - Relatórios e Métricas
- Relatórios de chamados (abertos/fechados/pendentes).
- Tempo médio de resolução.
- Métricas de desempenho da equipe.

## Definition of Done
- Código funcional e testado.
- Layouts integrados.
- Funcionalidades operacionais no sistema.
- Documentação atualizada.

## Definition of Ready
- Critérios de aceitação definidos.
- Wireframes prontos para cada módulo.

## Burndown
<img src="BurnDown/BurnDown_Sprint2.PNG" alt="Burndown Sprint 2" width="100%" />

</details>

<details>
<summary><strong>Sprint 3 - Interface e Experiência do Usuário</strong></summary>

## User Stories

### PAS - 36 - Usabilidade e Interface
- Layout responsivo para desktop e mobile.
- Interface intuitiva.
- Feedback visual para ações (confirmações, alertas etc).

## Definition of Done
- Interface finalizada e funcional.
- Layouts aprovados.
- Documentação de instalação atualizada.

## Definition of Ready
- Layouts definidos e aprovados.
- User stories revisadas com critérios claros.

## Burndown
<img src="BurnDown/BurnDown_Sprint3.PNG" alt="Burndown Sprint 3" width="100%" />

</details>

<details>
<summary><strong>Sprint 4 - Recuperação de Senha e Ajustes Finais</strong></summary>

## Funcionalidades previstas:
- Recuperação de senha via e-mail (link gerado automaticamente).
- Tela de redefinição segura.

### Wireframe de redefinição de senha
<img src="Wireframes/WireframePAS-34-2.JPG" alt="Wireframe Redefinição Senha" width="50%" />

## Burndown
<img src="BurnDown/BurnDown_Sprint4.PNG" alt="Burndown Sprint 4" width="100%" />

</details>

---

# Diagrama de Entidade-Relacionamento (DER)
<img src="DER_BD.png" alt="DER_BD" width="100%" />

---

# Autores e Créditos
- Lívia (Product Owner e Documentação)
- [Seu Nome aqui] (Scrum Master / Dev)
- [Outros colegas do grupo]

> Projeto desenvolvido para fins acadêmicos na disciplina de Projeto Integrador / Engenharia de Software.

<br>
<div align="center">
    <img src="../assets/footer.png" alt="footer" width="100%" />
</div>

</body>
</html>
