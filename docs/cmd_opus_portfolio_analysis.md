---
id: CMD-OPUS-PORTFOLIO-001
title: "CMD Opus — Portfolio Analysis · All 34 Assets · Single Pass"
version: "1.0"
status: Active
model: "claude-opus-4-6 · Extended Thinking ON · Web Search ON"
project: "STRATEGY__opus"
owner: Leonardo Batista
created_at: 2026-05-23
input_files:
  - asset_cards.yaml
  - scored_assets.csv
  - solutions_inventory.csv
  - personalization-os-full-package.md
tags: ["#portfolio", "#decision", "#strategy", "#opus", "#mcp"]
---

# CMD_OPUS_PORTFOLIO_ANALYSIS_001
## Single Pass · 34 Assets · Extended Thinking · Working Backwards

---

## ATIVAÇÃO

```
ACTIVATE: CMD-OPUS-PORTFOLIO-001
OPERATOR: Leonardo Batista
MODE: Extended Thinking ON · Web Search ON · Single Pass
FRAME: Working Backwards + Scoring Matrix + Cynefin + First Principles
RULE: Processar TODOS os blocos B-001→B-006 em sequência sem parar.
      Usar asset_cards.yaml + scored_assets.csv como fonte primária.
      Registrar D-### por bloco.
      Encerrar com SYNTHESIS: top 3 decisões + P1→P6 + riscos + 3 tarefas.
```

---

## CONTEXTO OBRIGATÓRIO

Leonardo Batista. Empreendedor solo. 6 meses de Discovery → Validating/MVP.

**34 ativos catalogados** com MCP (Minimum Context Packet):
- 1 Diamond (score ≥85): PersonalizationOS Course v1 (86.0)
- 15 Gold (score 74–84): Editorial OS, cmd-creator-skill, X-Ray Suite, Creator Suite,
  cognitive-framework-router, forge-visual-canvas, A-Z Claude, CMD Suite, MCP Framework,
  Progressive Disclosure L000-L008, cmd-01-pps, projects-to-linear, workflow-to-skill-magic,
  tdah-linear-workflow-os v2.0.0, proprallt-card-builder
- 16 Silver (score 60–73): TDAH Package, ai-gov-discovery-orchestrator, cmd-02-mirp,
  adhd-desk-dashboard, bussola-deliverable-forge, x-ray-brand-layer, project-packager,
  Livro DK-style, cmd-03-maro, live-prompt-pro-converter, Empower v7,
  Executive Artifact System v3, Bússola PME, opus-reasoning-max-fak, x-ray-onboarding-ebook, cenefim
- 2 Bronze (score 45–59): Scripity, _cognitive-trigger-skill-os

**Scoring pesos:** Dor clara 20% · Output reproduzível 20% · Prova de uso 20% ·
Monetização plausível 15% · Baixa fricção 10% · Canal de distribuição 10% · Defensibilidade 5%

**Stack:** Claude Pro R$110/mês · 12+ contas · GitHub · Hotmart · bilíngue PT-BR/EN.

**Regra epistêmica:** Separar FACT / INFERENCE / HYPOTHESIS / GAP em cada bloco.

---

## BLOCOS DE ANÁLISE — PROCESSAR EM SEQUÊNCIA

---

### B-001 · DIAMOND CONFIRMATION — PersonalizationOS Course merece o topo?

```
TIPO: Validation
FRAME: First Principles + Competitive Analysis
WEB SEARCH: sim — verificar cursos equivalentes em PT-BR e EN (2025-2026)

O PersonalizationOS Course v1 tem score 86.0 (Diamond).
É o único ativo com esse tier no portfolio.

Perguntas:
  1. Existe concorrência direta no mercado BR para "curso de personalização Claude para não-devs"?
     (buscar: "curso personalizar Claude", "Claude para não desenvolvedores", "AI workflow course Brazil")
  2. O diferencial do stack de 8 camadas + budget formula + editorial OS integrado
     é DEFENSÁVEL vs cursos genéricos de "prompts para Claude"?
  3. O ICP confirmado (consultor/gestor, 28-55 anos, R$197-R$497) está alinhado com
     o mercado de cursos AI no Hotmart BR?
  4. O score 86.0 reflete realidade ou tem viés por ser o ativo mais familiar de Leo?
     (aplicar revisão cética de OP-04)
  5. Diamond é a decisão certa ou deveria ser reavaliado?

Output esperado:
  - Confirmação ou revisão do tier Diamond
  - Diferencial competitivo verificado com evidência externa
  - D-DIAMOND-001 registrada
```

---

### B-002 · PORTFOLIO ARCHITECTURE — Quais produtos lançar e em qual ordem?

```
TIPO: Decision
FRAME: Working Backwards + Sequenciamento de Produto + Unit Economics
WEB SEARCH: não necessário

Contexto:
  Gold assets que podem virar produtos independentes:
  - PersonalizationOS Course v1 (P-001) — candidato a MVP principal
  - Editorial OS FullStack Runtime (P-002) — bundle ou standalone?
  - A-Z Claude (P-005) — produto de entrada mais simples?
  - cmd-creator-skill (S-001) — lead magnet gratuito no GitHub
  - X-Ray Suite (SU-001) — produto premium para consultores
  - Creator Suite (SU-002) — bundle gratuito + funil pago
  - TDAH Package (P-003) — nicho específico, Silver

Pergunta central:
  "Qual é a arquitetura de produto ideal para maximizar receita em 90 dias
   E construir audiência sustentável para os próximos 12 meses?"

Perguntas:
  1. Qual é a sequência correta de lançamento: PersonalizationOS primeiro ou
     Creator Suite como lead magnet primeiro?
  2. A-Z Claude (score 77.5, Gold) pode ser lançado ANTES do PersonalizationOS Course
     como produto de entrada de menor ticket?
  3. X-Ray Suite (score 77.5, Gold) é um produto separado ou linha premium do mesmo funil?
  4. TDAH Package (score 73.5, Silver) deve ser lançado em paralelo (nicho diferente)
     ou bundled como módulo do Course?
  5. Empower v7 (score 68.0, Silver, blockers ativos) deve ser descontinuado até os
     blockers resolverem ou mantido como candidato Q3?

Output esperado:
  - Arquitetura de produto em 3 tiers (entry/core/premium)
  - Sequência de lançamento P1→P4 com critérios de entrada
  - D-PRODUCT-ARCH-001 registrada
```

---

### B-003 · SKILLS PRIORITIZATION — Quais skills publicar no GitHub primeiro?

```
TIPO: Decision
FRAME: Impact × Effort + Progressive Disclosure
WEB SEARCH: não necessário

Das 19 skills catalogadas, 14 têm score Gold ou acima.
A pergunta não é "quais são melhores" — o score já responde isso.
A pergunta é "qual ordem de publicação no GitHub maximiza adoção e cria funil para o curso?"

Contexto:
  Top Gold skills por score:
  S-001: cmd-creator-skill (81.0) — entry point, gratuito
  S-005: cognitive-framework-router (79.0) — metodologia central
  S-007: forge-visual-canvas (77.5) — output visual, alta visibilidade
  S-009: projects-to-linear (75.5) — integração prática
  S-013: workflow-to-skill-magic (75.5) — meta-skill de criação
  S-002: cmd-01-pps (78.5) — packaging utility

  Baixo score (Bronze) = não publicar ainda:
  S-019: _cognitive-trigger-skill-os (57.5)

Perguntas:
  1. Qual skill deve ser publicada PRIMEIRO como ponto de entrada do Creator Suite no GitHub?
     (não necessariamente a de maior score — considerar efeito de demonstração)
  2. Existe uma "skill demonstrativa" que mostra o poder do sistema em ≤2 min de README?
  3. Quais 3 skills formam o "minimal kit" que um novo usuário precisa para ver valor imediato?
  4. Quais skills são infraestrutura interna (não publicar como produto standalone)?
  5. Qual skill pode virar um vídeo YouTube de 5 minutos que atrai o ICP certo?

Output esperado:
  - Sequência de publicação GitHub (fase 1: 3 skills / fase 2: 5 skills)
  - "Minimal kit" de 3 skills para novo usuário
  - D-SKILLS-PUB-001 registrada
```

---

### B-004 · SILVER ASSETS — O que fazer com os 16 ativos Silver?

```
TIPO: Analysis + Decision
FRAME: MECE + Cynefin + Issue Tree

16 ativos com score 60-73 (Silver). Três destinos possíveis para cada:
  A. BUNDLE — incluir em produto maior sem preço separado
  B. HOLD — manter ativo mas não investir até ter receita do Diamond/Gold
  C. DEPRECATE — arquivar · não vale o esforço de manutenção

Contexto por subcategoria:

SILVER que provavelmente são BUNDLE:
  - adhd-desk-dashboard (72.5) → bundle TDAH Package
  - x-ray-brand-layer (70.0) → bundle X-Ray Suite
  - x-ray-onboarding-ebook (65.5) → bundle X-Ray Suite
  - cenefim (63.5) → componente do cognitive-framework-router
  - ai-gov-discovery-orchestrator (73.0) → template interno, não produto

SILVER que podem ser HOLD:
  - Empower v7 (68.0) → blockers ativos, potencial alto quando resolver
  - Livro DK-style (68.5) → em produção, lead magnet de alto valor no médio prazo
  - cmd-03-maro (68.5) → produto B2B válido mas nicho específico
  - bussola-deliverable-forge (72.0) → bundle Bússola PME quando lançar
  - Executive Artifact System v3 (67.5) → pode ser M6 do PersonalizationOS Course

SILVER que podem ser DEPRECATE:
  - Scripity (59.5, Bronze realidade) → diferencial fraco · concorrência alta
  - project-packager (69.0) → overlap com cmd-01-pps · consolidar em um só

Perguntas:
  1. Para cada Silver, classificar em A/B/C com justificativa de 1 linha.
  2. Existe algum Silver que foi subavaliado e deveria ser reavaliado como Gold?
     (critério: evidência externa que o sistema de score não capturou)
  3. Empower v7 (blockers) merece um plano de desbloqueio ou deve ser arquivado até Q3?
  4. Executive Artifact System v3 é produto separado ou M6 do PersonalizationOS Course?
  5. O Livro DK-style tem papel estratégico como credencial de autoridade mesmo com
     score baixo em "prova de uso"?

Output esperado:
  - Tabela: cada Silver com decisão A/B/C + justificativa
  - Mapa de consolidação (quais Silver viram módulos de produtos Gold/Diamond)
  - D-SILVER-DECISION-001 registrada
```

---

### B-005 · BRONZE ANALYSIS — Scripity e _cognitive-trigger-skill-os

```
TIPO: Decision Gate
FRAME: Cynefin (Chaotic/Complex) + Kill Criteria

Apenas 2 ativos Bronze:
  P-008: Scripity (59.5) — produto de script de vídeo
  S-019: _cognitive-trigger-skill-os (57.5) — sistema de triggers automáticos

Para cada um, responder:
  1. O score reflete genuinamente baixo potencial ou há condições que mudariam a avaliação?
  2. Existe evidência externa de demanda que o score não capturou?
     (WEB SEARCH para Scripity: mercado de "script generators" para criadores BR)
  3. Qual seria o mínimo viável para mover cada um para Silver?
  4. Kill criteria: se essas condições não forem atendidas em 60 dias, arquivar?
  5. Para S-019: é infraestrutura necessária para outros produtos funcionarem?
     (se sim, manter como dependência não-publicada)

Output esperado:
  - Decisão: HOLD com condições / DEPRECATE
  - Kill criteria para cada
  - D-BRONZE-001 registrada
```

---

### B-006 · 90-DAY PORTFOLIO ROADMAP — O plano completo

```
TIPO: Execution Plan
FRAME: Working Backwards + 5W2H + Sequenciamento de Dependências
WEB SEARCH: sim — verificar calendário de features Anthropic e tendências AI BR Q2/Q3 2026

Com base em B-001→B-005:

Fase 1 · Dias 1-30 (GitHub + Lead Magnet):
  - Quais 3 artefatos precisam ir ao GitHub para criar prova social?
  - Qual é o primeiro post LinkedIn que apresenta o sistema para o ICP?
  - Qual é a métrica de sucesso do mês 1?

Fase 2 · Dias 31-60 (Validação + Course):
  - Quando gravar os 6 módulos do PersonalizationOS Course?
  - Como usar os Gold assets como "prova da metodologia" durante a validação?
  - 3 entrevistas de ICP: quem convidar e como estruturar?

Fase 3 · Dias 61-90 (Lançamento):
  - O que precisa estar pronto para o go-live no Hotmart?
  - Qual é a sequência da semana de lançamento?
  - Kill criteria: se qual número não for atingido em 7 dias, ajustar?

Output esperado:
  - Tabela de fases com data, entrega, owner, métrica e critério de go/no-go
  - Mapa de dependências (o que desbloqueia o quê)
  - D-ROADMAP-90D-001 registrada
```

---

## FORMATO DE SAÍDA (para cada bloco)

```
### B-00X · [TÍTULO]

**Epistêmico:**
FACT: [dados verificados]
INFERENCE: [conclusões lógicas]
HYPOTHESIS: [premissas não testadas]
GAP: [o que falta saber]

**Análise:**
[raciocínio + recomendação]

**Decisão:**
D-[CÓDIGO]-001 — [decisão registrada com critério de mudança]
```

---

## SYNTHESIS FINAL (após B-006)

```
## SYNTHESIS

### TOP 3 DECISÕES MAIS CRÍTICAS (impacto × urgência)
1. D-### — [decisão]
2. D-### — [decisão]
3. D-### — [decisão]

### PORTFOLIO MAP: DECISÃO POR TIER
| Tier | Asset | Decisão | Próxima Ação |
|---|---|---|---|

### SEQUÊNCIA P1→P6 (90 dias)
| Fase | Entrega | Data | Critério de Sucesso |

### RISCOS ATIVOS PÓS-ANÁLISE
R-### — [risco] — Nível: Alto/Médio/Baixo

### PRÓXIMAS 3 TAREFAS PARA LEONARDO
T-001 — [tarefa] — prazo — output esperado
T-002 — [tarefa] — prazo — output esperado
T-003 — [tarefa] — prazo — output esperado
```

---

## REGRAS DE EXECUÇÃO

1. Processar B-001→B-006 em sequência sem parar para gate.
2. Web Search nos blocos marcados com "WEB SEARCH: sim".
3. Separar FACT/INFERENCE/HYPOTHESIS/GAP em cada bloco.
4. Registrar uma D-### por bloco.
5. Usar asset_cards.yaml como fonte canônica de scores e dados.
6. Não criar novos produtos — analisar e decidir sobre os 34 existentes.
7. Conceitos proprietários intocáveis: PersonalizationOS · Creator Suite ·
   Editorial OS · CMD Suite · X-Ray Suite · AI Gov Brasil · Inside Claude Mind.
8. Extended Thinking: usar em B-001 (validação Diamond), B-002 (arquitetura de produto)
   e B-006 (roadmap 90 dias). Para B-003/B-004/B-005: raciocínio direto.
9. Ao final: perguntar "Leonardo, qual dos 6 blocos você quer aprofundar primeiro?"

---

## COMO USAR ESTE CMD

**Passo 1.** Abrir projeto STRATEGY__opus (Opus 4.6 · Extended Thinking ON · Web Search ON).

**Passo 2.** Fazer upload dos 3 arquivos no Project Knowledge:
  - asset_cards.yaml
  - scored_assets.csv
  - solutions_inventory.csv

**Passo 3.** Colar este arquivo completo como primeira mensagem.

**Passo 4.** Aguardar processamento (estimativa: 10-20 min com Extended Thinking em B-001/B-002/B-006).

**Passo 5.** Ao receber o SYNTHESIS, escolher 1 bloco para aprofundar.

---

_PersonalizationOS Portfolio · Leonardo Batista · AI Gov Brasil · 2026-05-23_
