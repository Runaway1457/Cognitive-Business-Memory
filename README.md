# 🧠 Cognitive Business Memory

> **Assistente de Memória Empresarial com IA** - Sistema que "lembra" todo o contexto empresarial e conecta pontos invisíveis através de um Grafo de Conhecimento Temporal.

![Next.js](https://img.shields.io/badge/Next.js-15.1.1-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)
![Three.js](https://img.shields.io/badge/Three.js-0.183-black?style=flat-square&logo=three.js)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## 📸 Preview

```
┌─────────────────────────────────────────────────────────────────┐
│  🧠 Cognitive Business Memory                    AI Powered ⚡  │
├─────────────┬─────────────────────────────────┬────────────────┤
│   QUERY     │       3D KNOWLEDGE GRAPH        │    TIMELINE    │
│             │                                 │                │
│  Pergunte   │    ●━━━━━●━━━━━●               │  📅 Jan 2025   │
│  sobre...   │   /│     /│\    │              │  ├─ Slack msg  │
│             │  ● ━●━━━●  ●   ●              │  ├─ Email      │
│  ┌────────┐ │   \│     │    /               │  └─ Jira ticket│
│  │  ...   │ │    ●━━━━━●━━━●                │                │
│  └────────┘ │         ^                      │  📅 Fev 2025   │
│             │    (hover para detalhes)       │  └─ Meeting    │
│  Cadeia:    │                                 │                │
│  (1) João   │    Legenda:                     │                │
│  (2) Lucas  │    ● Pessoa  ● Cliente          │                │
│  (3) PIX    │    ● Feature ● Métrica          │                │
│  (4) Churn  │    ━━ Causal  ━━ Temporal       │                │
└─────────────┴─────────────────────────────────┴────────────────┘
```

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|----------------|-----------|
| 🔍 **Query com IA** | Perguntas em linguagem natural com cadeias causais |
| 🌐 **Grafo 3D** | Visualização interativa do conhecimento empresarial |
| 📊 **Timeline** | Eventos organizados cronologicamente |
| 📈 **Dashboard** | Métricas e alertas em tempo real |
| 🔗 **Conexões** | Causal, Temporal, Relacional, Semântico |

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/seu-usuario/cognitive-business-memory.git
cd cognitive-business-memory

# Instale
bun install

# Configure
cp .env.example .env.local

# Rode
bun run dev
```

Acesse: http://localhost:3000

## 🎯 Exemplo de Uso

```
Query: "Por que o cliente NeoBank cancelou?"

┌─────────────────────────────────────────────────────────────┐
│ CADEIA CAUSAL (94% confiança)                               │
├─────────────────────────────────────────────────────────────┤
│ (1) Ricardo Mendes saiu - Nov 2024                          │
│     └─ Único especialista em PIX                            │
│                                                             │
│ (2) Budget de contratação NEGADO - Dez 2024                 │
│     └─ Lucas ficou em 140% de capacidade                    │
│                                                             │
│ (3) PIX Instantâneo atrasou 3 meses                         │
│     └─ Feature crítica para o cliente                       │
│                                                             │
│ (4) Incidente de 4h em produção - Jan 2025                  │
│     └─ Gatilho final para cancelamento                      │
│                                                             │
│ (5) NeoBank CANCELOU R$2.4M/ano - Jan 2025                  │
└─────────────────────────────────────────────────────────────┘
```

## 🏗️ Arquitetura

```
┌────────────────────────────────────────────────────────────┐
│                    FRONTEND (Next.js 16)                   │
│  React 19 │ Three.js 3D │ shadcn/ui │ Tailwind CSS        │
├────────────────────────────────────────────────────────────┤
│                    BACKEND (API Routes)                    │
│  /api/query │ z-ai-web-dev-sdk │ Knowledge Graph Logic    │
├────────────────────────────────────────────────────────────┤
│                    DATA LAYER                              │
│  Entities │ Data Sources │ Graph Edges │ Causal Chains    │
└────────────────────────────────────────────────────────────┘
```

## 📁 Estrutura

```
src/
├── app/
│   ├── api/query/route.ts      # API IA
│   └── page.tsx                # Main page
├── components/cognitive/
│   ├── KnowledgeGraph3D.tsx    # 3D Graph
│   ├── QueryInterface.tsx      # AI Query
│   ├── Timeline.tsx            # Events
│   └── StatisticsPanel.tsx     # Metrics
└── lib/
    ├── mock-data.ts            # Data
    └── knowledge-graph.ts      # Logic
```

## 📊 Dados Incluídos

- **34 pessoas** (CEO, CTO, Developers, Sales, CS...)
- **7 clientes** (NeoBank, Saúde Tech, Varejo Plus...)
- **42 fontes de dados** (Slack, Email, Jira, Meetings...)
- **32 conexões** causais e temporais
- **Timeline** Out/2024 → Jan/2026

## 🔧 Stack

| Tecnologia | Versão |
|------------|--------|
| Next.js | 16.1.1 |
| React | 19.0 |
| TypeScript | 5.0 |
| Three.js | 0.183 |
| Tailwind CSS | 4.0 |
| shadcn/ui | latest |
| z-ai-web-dev-sdk | 0.0.16 |

## 📄 Licença

MIT - Veja [LICENSE](LICENSE)

## 🤝 Contribuir

Veja [CONTRIBUTING.md](CONTRIBUTING.md)

---

<p align="center">By Gabriel B</p>
