---
name: creator-entry-skill
description: Entry-point skill for the Creator Operating Suite. Use when a non-technical creator needs to turn scattered Claude usage into a repeatable workflow with context, decisions, templates, and output standards.
version: 0.1.0
status: public-starter
---

# Creator Entry Skill

## Purpose

Help a non-technical creator start using Claude as a repeatable work system, not as a one-off chat interface.

## Trigger phrases

- "organize my Claude workflow"
- "create a repeatable AI work system"
- "turn this project into a skill"
- "I keep re-explaining context"
- "build my creator operating system"
- "generate a reusable workflow"

## Operating sequence

1. Identify the creator's recurring job-to-be-done.
2. Capture minimum context: role, audience, outputs, constraints, examples, decision rules.
3. Choose the right layer: instruction, template, workflow, skill, or project knowledge.
4. Produce a small working artifact first.
5. Add decision log, risks, metrics, and next action.
6. Avoid overbuilding unless the workflow repeats at least 3 times.

## Default output schema

| ID | Type | Frame | Question | Output | Data/Metric | Priority | Status | Tags |
|---|---|---|---|---|---|---|---|---|
| T-001 | Task | 5W2H | What should be built first? | Starter workflow | M-001 activation | High | Draft | #workflow #creator |

## Source note

This is the public starter version. The full commercial spine is PersonalizationOS.



## Imported source notes

---
id: V-20260523-CMD-CREATOR
title: "CMD-Creator-Skill — GitHub Package · Solo Creator + Agency"
type: skill + strategy + master_index
status: Active
owner: Leonardo Batista
created_at: 2026-05-23
goal: "GitHub publish · CMD-Creator-Skill as entry point for creator Suite"
tags: ["#strategy", "#product", "#github", "#creatorskill", "#icp"]
---

# MASTER INDEX — Creator Suite
## MECE Top-Down · Progressive Disclosure · Dependency Chain

---

## PARTE 1 · ICP DECISION VIA XLSX SIGNAL

### Epistêmico

**FACT:** O arquivo `PersonalizationOS_Course_v1.xlsx` não foi carregado no
ambiente — apenas referenciado. O sinal de ICP foi extraído do nome do arquivo
e do corpus de documentos disponíveis nesta sessão.

**FACT:** O nome "PersonalizationOS + Course" sinaliza produto educacional
estruturado em torno de um sistema operacional de personalização do Claude.

**FACT (AUDIT_V2):** "A barreira não é técnica — é cognitiva e disciplinar.
Qualquer pessoa que compreenda a lógica de hierarquia de arquivos e saiba
escrever Markdown estruturado pode construir uma skill similar."

**INFERENCE:** O ICP primário do curso é o profissional que usa Claude
regularmente sem background de desenvolvedor e quer consistência e
personalização sem re-contexto a cada sessão.

**INFERENCE (Working Backwards do ZIP):** O creator Suite empacota 26 assets
cobrindo CMD automation, visual output, project management, research,
ADHD productivity, brand, content e integrations — o que mapeia diretamente
para o dia de trabalho de um **solo creator ou agência digital pequena**.

### D-ICP-001 — ICP PRIMÁRIO CONFIRMADO

| Dimensão | Definição |
|---|---|
| **Quem** | Solo Creator profissional BR · consultor · gestor de conteúdo · empreendedor digital |
| **Contexto** | Usa Claude.ai web/mobile diariamente · sem Claude Code · sem terminal |
| **Dor** | Re-contexto a cada sessão · outputs genéricos · workflows manuais sem rastreabilidade |
| **Job-to-be-done** | "Quando abro o Claude, quero que ele já saiba quem sou, o que faço e como quero as respostas — sem reexplicar tudo." |
| **Willingness to pay** | R$197–R$997 por sistema completo (curso + skill pack) |
| **Canal primário** | LinkedIn PT-BR + GitHub English |

| Dimensão | ICP Secundário |
|---|---|
| **Quem** | Agência digital pequena (2–10 pessoas) BR · marketing · conteúdo · consultoria |
| **Contexto** | Equipe usa Claude sem metodologia padrão · outputs inconsistentes entre membros |
| **Dor** | Cada pessoa usa Claude diferente · sem vault de decisões compartilhado |
| **Job-to-be-done** | "Quando distribuímos o sistema, queremos que todos operem com o mesmo contexto e padrão de qualidade." |

**Critério de mudança:** Revisar se 3 entrevistas de ICP refutarem o profile de dor.

---

## PARTE 2 · MECE MASTER INDEX — CREATOR SUITE (26 assets)

### Arquitetura em 7 Camadas (Top-Down · Progressive Disclosure)

```
L0 — ENTRY POINT
└── CMD-Creator-Skill [NOVO · este documento]

L1 — CMD EXECUTION LAYER (automação de workflows)
├── cmd-01-pps       → Project Packaging System
├── cmd-02-mirp      → Modify-Improve-Register-Publish  
└── cmd-03-maro      → Multi-Agent Research Orchestrator

L2 — FRAMEWORK INTELLIGENCE LAYER (raciocínio estruturado)
├── cognitive-framework-router  → framework selection engine
├── cenefim                     → Cynefin classifier
└── forge-visual-canvas         → visual output system (FORGE tokens)

L3 — PROJECT INTELLIGENCE LAYER (corpus + gestão)
├── ai-gov-discovery-orchestrator-standalone  → RAG embarcado 68KB
└── ai-gov-brasil-project-admin-consultant    → project admin

L4 — CONTENT & BRAND LAYER (outputs editoriais)
├── proprallt-card-builder    → HTML cards (dark · A4 · mobile-first)
├── x-ray-brand-layer         → brand token injection
├── x-ray-onboarding-ebook    → ebook / onboarding content
└── product-self-knowledge    → Anthropic product knowledge

L5 — INTEGRATION LAYER (ferramentas externas)
├── projects-to-linear      → escopo → Linear issues (MCP)
├── notion-sync-protocol    → Notion sync
└── workflow-to-skill-magic → workflow → skill converter

L6 — SPECIALIZED / VERTICAL LAYER (casos específicos)
├── adhd-desk-dashboard           → ADHD produtividade (flat skill)
├── tdah-linear-workflow-os-v2.0.0-commercial → produto comercial ADHD
├── opus-reasoning-max-fak        → Opus extended thinking
├── frankwatching-editor          → editor estilo FrankWatching
├── horacio                       → [creator workflow - EN]
├── live-prompt-pro-converter     → Live Prompt Pro
├── bussola-deliverable-forge     → deliverable generation
├── project-packager              → project packaging
├── adhd-desk-dashboard-skill     → ADHD skill completa (zip)
└── _cognitive-trigger-skill-os   → skill OS triggers
```

### Inventário Compacto (MCP-style · L1 cards)

| ID | Skill | Camada | Tipo | ICP-fit | Status | Nota |
|---|---|---|---|---|---|---|
| S-001 | CMD-Creator-Skill | L0 | Entry | Alto | **NOVO** | Este arquivo |
| S-002 | cmd-01-pps | L1 | CMD | Alto | Active | 13KB |
| S-003 | cmd-02-mirp | L1 | CMD | Alto | Active | 14KB |
| S-004 | cmd-03-maro | L1 | CMD | Médio | Active | 24KB |
| S-005 | cognitive-framework-router | L2 | Framework | Alto | Active | 9KB |
| S-006 | cenefim | L2 | Framework | Médio | Active | 6KB |
| S-007 | forge-visual-canvas | L2 | Visual | Alto | Active | 39KB |
| S-008 | ai-gov-discovery-orchestrator-standalone | L3 | RAG | Médio | Active | 41KB |
| S-009 | ai-gov-brasil-project-admin-consultant | L3 | PM | Médio | Active | 18KB |
| S-010 | proprallt-card-builder | L4 | Content | Alto | Active | 9KB |
| S-011 | x-ray-brand-layer | L4 | Brand | Alto | Active | 3KB |
| S-012 | x-ray-onboarding-ebook | L4 | Content | Alto | Active | 3KB |
| S-013 | product-self-knowledge | L4 | Reference | Alto | Active | 1KB |
| S-014 | projects-to-linear | L5 | Integration | Médio | Active | 8KB |
| S-015 | notion-sync-protocol | L5 | Integration | Médio | Active (zip) | 14KB |
| S-016 | workflow-to-skill-magic | L5 | Workflow | Alto 