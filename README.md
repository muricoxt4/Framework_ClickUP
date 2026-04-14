# 🗂️ Framework de Gestão de Projetos — ClickUp

> Sistema de gestão desenvolvido e operado em uma **agência de publicidade** com carteira diversificad, utilizando o **ClickUp** como plataforma central de organização, produção e acompanhamento de clientes e equipes.

---

## 📋 Índice

- [Visão Geral](#-visão-geral)
- [Estrutura do Workspace](#-estrutura-do-workspace)
- [Espaço CLIENTES](#-espaço-clientes)
- [Espaço OPERAÇÕES](#-espaço-operações)
- [Painéis de Acompanhamento](#-painéis-de-acompanhamento)
- [Painel CS | Sprint](#-painel-cs--sprint)
- [Espaços de Suporte](#-espaços-de-suporte)
- [Fluxo de Trabalho](#-fluxo-de-trabalho)
- [Princípios do Framework](#-princípios-do-framework)
- [Automações via IA](#-automações-via-ia)

---

## 🧭 Visão Geral

O workspace foi estruturado para atender **múltiplos clientes simultaneamente** em diferentes segmentos, garantindo rastreabilidade, padronização e visibilidade em todas as etapas da produção.

A arquitetura é dividida em **6 espaços temáticos**, cada um com finalidade específica, de modo que a gestão de clientes, a operação interna, os dados cadastrais e o pipeline comercial funcionem de forma independente e integrada.

```
Workspace
├── 📁 CLIENTES          → Gestão de jobs por cliente
├── ⚙️  OPERAÇÕES         → Controle interno de produção
├── 🧩 MODELOS GERAIS    → Templates e padronização
├── 👥 PESSOAS           → RH e processos internos
├── 🗃️  CADASTROS         → Base de dados centralizada
└── 💼 COMERCIAL         → CRM e pipeline de vendas
```

---

## 🏗️ Estrutura do Workspace

| Espaço | Finalidade Principal | Tipo de Conteúdo |
|---|---|---|
| **CLIENTES** | Gestão de jobs por cliente | Pastas individuais por cliente com listas anuais |
| **OPERAÇÕES** | Controle interno de produção | Áreas: CS, Criativos, Conteúdo, Social Mídia, NPS |
| **MODELOS GERAIS** | Padronização e templates | Pasta e lista modelo replicáveis |
| **PESSOAS** | RH e processos internos | Processos, tutoriais e gestão de time |
| **CADASTROS** | Base de dados centralizada | Clientes, fornecedores e veículos |
| **COMERCIAL** | Pipeline de vendas e CRM | Prospecção e atividades comerciais |

---

## 👤 Espaço CLIENTES

Centraliza toda a produção voltada ao atendimento da carteira ativa. Cada cliente possui uma **pasta própria**, dentro da qual as listas são organizadas por ano — garantindo histórico permanente e fácil navegação por período.

### Lógica de Organização

```
CLIENTES/
├── NOME DO CLIENTE/
│   ├── Jobs 2025
│   └── Jobs 2026
├── OUTRO CLIENTE/
│   └── Jobs 2026
└── JOBS PARAQUEDAS - NÃO CLIENTES/
    └── Jobs
```

### Padrão de Nomenclatura

| Elemento | Padrão adotado |
|---|---|
| Nome da pasta | `NOME DO CLIENTE` (sempre em maiúsculas) |
| Lista de trabalho | `Jobs [ANO]` ou `Jobs ♾️` (demanda contínua) |
| Demandas avulsas | Pasta separada: `JOBS PARAQUEDAS` |
| Fluxo contínuo | Lista `Novas demandas` dentro da pasta do cliente |

### Benefícios da Estrutura

- ✅ Histórico de entregas preservado por cliente e por ano
- ✅ Onboarding ágil: basta duplicar a `PASTA MODELO` e renomear
- ✅ Carteira ativa sem mistura entre clientes diferentes
- ✅ Separação entre jobs formais e demandas avulsas

---

## ⚙️ Espaço OPERAÇÕES

Organiza o **fluxo interno de produção** da agência. Cada área funcional possui sua própria pasta com listas de tarefas dedicadas, permitindo autonomia de gestão sem interferência entre equipes.

### Áreas Cobertas

| Pasta | Função |
|---|---|
| **Gestão \| Operações** | Rotina geral, jobs paraquedas, demandas internas e carteira de clientes |
| **Gestão \| Criativos** | Controle da produção criativa por ciclo anual |
| **Gestão \| Conteúdo** | Organização de tarefas da área de produção de conteúdo |
| **Gestão \| Social Mídia** | Gestão de entregas e tarefas da área de SM |
| **NPS clientes** | Pesquisas de satisfação por ciclo — controle de NPS da carteira |

### Destaques

- 🔹 Separação clara entre Criativos, Conteúdo e Social Mídia
- 🔹 Lista **Carteira** centraliza a visão consolidada de relacionamento com clientes
- 🔹 NPS integrado ao workspace — satisfação cruzada com volume de entregas
- 🔹 Área de CS como hub de comunicação entre cliente e equipe interna

---

## 📊 Painéis de Acompanhamento

O workspace conta com **6 painéis (dashboards)** configurados para dar visibilidade ao andamento da produção em tempo real. Os painéis são organizados por área funcional e utilizam o modelo de **Sprint** para controle de ciclos de trabalho.

### Estrutura dos Painéis

| # | Painel | Finalidade |
|---|---|---|
| 🌐 | **PAINEL GERAL — FUTURO SEMANAL** | Visão macro de todas as entregas previstas para a semana, consolidando todas as áreas |
| 1 | **CS \| Sprint** | Acompanhamento do ciclo de atendimento ao cliente — demandas, rotina e carteira ativa |
| 2 | **Conteúdo \| Sprint** | Ciclo de produção de conteúdo — tarefas em andamento, pendentes e concluídas |
| 3 | **Criativo \| Sprint** | Controle do sprint da equipe criativa — jobs em produção e próximos na fila |
| 4 | **SM \| Sprint** | Gestão do ciclo de Social Mídia — publicações, pautas e status de aprovação |
| 5 | **Produtora \| Sprint** | Acompanhamento da produção audiovisual e projetos da produtora |

### Modelo de Sprint por Área

Cada área opera com seu próprio sprint, permitindo que equipes diferentes mantenham **ritmos independentes** sem interferir umas nas outras. O Painel Geral funciona como camada de consolidação — reunindo todas as áreas em uma única visão semanal.

### Fluxo de Uso dos Painéis

| Momento | Painel utilizado |
|---|---|
| Início da semana | **PAINEL GERAL** para alinhamento macro |
| Durante a semana | Sprint individual da área para acompanhamento em curso |
| Revisão de entrega | Sprint da área para checagem de conclusão e pendências |
| Reunião de gestão | **PAINEL GERAL** para visão consolidada e tomada de decisão |

---

## 🤝 Painel CS | Sprint

O painel de **Customer Success** é o hub central de relacionamento entre a agência e seus clientes. Ele integra a rotina diária do time de CS com a carteira ativa, garantindo que nenhuma demanda ou cliente fique sem acompanhamento.

### Estrutura do Painel

O painel CS | Sprint é alimentado por duas listas principais dentro do espaço **OPERAÇÕES**:

```
OPERAÇÕES/
└── Gestão | Operações/
    ├── Rotina         → Tarefas recorrentes do time de CS
    └── Carteira       → Registro e acompanhamento de cada cliente ativo
```

### Rotina do Time de CS

As tarefas de rotina garantem o funcionamento diário do atendimento:

| Tarefa | Tipo |
|---|---|
| Daily mensal (ex: Daily Abril 2026) | Recorrente mensal |
| Alinhamento Semanal CS e SM | Recorrente semanal |
| Check Diário de Chats | Recorrente diário |
| Acompanhamento de Clientes CS | Recorrente |
| Agenda de Demandas (individual por CS) | Contínua |
| Reuniões de Resultados — Agendas | Alta prioridade |

### Carteira de Clientes

A lista **Carteira** registra cada cliente como uma tarefa, com o CS responsável como assignee — permitindo visibilidade clara de **quem atende quem** e facilitando a distribuição de carga entre o time.

> Cada CS acessa o painel e vê apenas os clientes e demandas da sua carteira, sem ruído das outras contas.

### Como o Painel CS se Conecta ao Restante do Workspace

```
Painel CS | Sprint
    │
    ├──→ Pasta do cliente em CLIENTES    → jobs abertos e histórico
    ├──→ Sprint de cada área             → andamento da produção
    │     (Conteúdo / Criativo / SM / Produtora)
    └──→ PAINEL GERAL                   → visão semanal consolidada
```

- O CS **abre ou solicita** a abertura de jobs na pasta do cliente
- **Acompanha** o andamento via painel de sprint da área responsável
- Registra demandas e alinhamentos na **Agenda de Demandas** individual
- Fecha o ciclo com **Reuniões de Resultados** com o cliente

---

## 🧩 Espaços de Suporte

| Espaço | Pasta / Lista | Conteúdo |
|---|---|---|
| **MODELOS GERAIS** | PASTA MODELO | Template replicável para novos clientes — duplicar e renomear |
| **MODELOS GERAIS** | JOBS MODELO | Lista padrão de jobs com estrutura pré-configurada |
| **MODELOS GERAIS** | NPS Clientes | Template de pesquisa de satisfação para novos ciclos |
| **PESSOAS** | Gestão \| Pessoas | Processos internos e gestão de colaboradores |
| **PESSOAS** | Processos e tutoriais | Base de conhecimento e tutoriais operacionais |
| **CADASTROS** | Cadastros | Base unificada de clientes, fornecedores e veículos |
| **COMERCIAL** | CRM → Prospecção | Pipeline de novos clientes e oportunidades |
| **COMERCIAL** | Gestão \| Comercial → Atividades | Controle de atividades da área comercial |

---

## 🔄 Fluxo de Trabalho

Do primeiro contato à entrega final, o framework suporta um ciclo completo e repetível:

```
1. Prospecção         →  COMERCIAL > CRM > Prospecção
        ↓
2. Cadastro           →  CADASTROS > Cadastros | Clientes
        ↓
3. Criação da pasta   →  CLIENTES > duplicar PASTA MODELO e renomear
        ↓
4. Abertura do job    →  CLIENTES > pasta do cliente > lista do ano
        ↓
5. CS acompanha       →  Painel CS | Sprint + Agenda de Demandas
        ↓
6. Produção           →  OPERAÇÕES > sprint da área responsável
        ↓
7. Acompanhamento     →  Painéis de Sprint + PAINEL GERAL
        ↓
8. Entrega e NPS      →  Tarefa concluída + pesquisa de satisfação
```

---

## 🏛️ Princípios do Framework

| Pilar | Descrição | Como se manifesta |
|---|---|---|
| **Escalabilidade** | Crescer sem reorganizar | Pasta por cliente + templates prontos para duplicação |
| **Rastreabilidade** | Histórico sempre acessível | Listas anuais por cliente + NPS integrado |
| **Clareza Operacional** | Cada área sabe o que é seu | Espaços e pastas separados por função, sem sobreposição |
| **Autonomia por Área** | Equipes gerenciam sem depender de terceiros | Sprint e painel individual por área funcional |

---

## 🤖 Automações via IA

Este framework também é utilizado em conjunto com **agentes de IA** para automação de tarefas operacionais, como:

- **Replicação de tarefas entre meses** — criação automatizada de jobs recorrentes (ex: `LAGO | Crono Maio` → `LAGO | Crono Junho`) com todas as subtarefas, responsáveis e campos customizados preservados
- **Leitura de hierarquia** — mapeamento automático de espaços, pastas e listas para documentação e análise
- **Geração de documentação** — exportação da estrutura do workspace para formatos como `.docx` e `.md` para uso em portfólio

> As automações são executadas via integração com a **API do ClickUp** através de **MCP (Model Context Protocol)**, conectado ao modelo de linguagem **Claude** da Anthropic.

---

*Documentação gerada com apoio de IA — Claude (Anthropic) via integração MCP com ClickUp.*
