---
id: V-20260523-PERS-OS-FULL
title: "PersonalizationOS — Full Package"
subtitle: "Template Library Renamed · Customer Journey · 20 FAQs · CMD Opus Final Agent"
version: "1.0"
status: Active
owner: Leonardo Batista
integrates: [PersonalizationOS_Course_v1.numbers, Editorial_OS_FullStack_Runtime_v1.md]
created_at: 2026-05-23
tags: ["#product", "#course", "#editorial", "#opus", "#github"]
---

# PersonalizationOS — Full Package
## Rename · Progressive Disclosure · Journey · FAQs · Opus Agent

---

# PARTE 1 · TEMPLATE LIBRARY — RENAME COMPLETO
## Progressive Disclosure + Dependency Chain + Cause-Effect

---

### Lógica do Sistema de Nomes

A renomeação segue a arquitetura das 8 camadas do Módulo 1 do curso.
O prefixo é sempre `L[NNN]`, onde NNN é o número da camada.
A progressão da esquerda para a direita representa a ordem de dependência:
você não pode configurar L-003 sem antes ter definido L-001.
Isso é o progressive disclosure: cada layer só é relevante depois da anterior estar estável.

```
L-000 (Entry)    → ponto de entrada antes do stack
L-001 (Global)   → fundação: quem você é, como opera
L-002 (Memory)   → persistência entre sessões
L-003 (Project)  → contexto local de cada projeto
L-004 (Knowledge)→ base documental por projeto
L-005 (Skill)    → procedimentos repetíveis acionados por trigger
L-006 (Style)    → forma de entrega do output
L-007 (Connector)→ integrações externas (Linear, GitHub, Notion)
L-008 (Prompt)   → execução pontual por tarefa
```

### Tabela Completa de Rename

| ID antigo | Nome antigo | ID novo | Nome novo | Camada | Carrega quando |
|---|---|---|---|---|---|
| — | CMD Creator Skill (entry) | `L000-entry-creator-skill.md` | Creator Entry Point | L-000 | Primeira sessão · sem stack ainda |
| T-01 | Global Power User | `L001-global-power-user.md` | Global · Power User | L-001 | Setup inicial · consultor/pesquisador/fundador |
| T-02 | Global Universal | `L001-global-universal.md` | Global · Universal | L-001 | Setup inicial · usuário prático sem framework |
| CMD_GLOBAL_V2 | CMD Global V2 | `L001-cmd-global-strategy.md` | Global · Strategy/CMD | L-001 | Projetos com vault de decisões + batch queries |
| **NOVO** | Editorial Creator (este arquivo) | `L001-global-editorial-creator.md` | Global · Editorial Creator | L-001 | Criadores + editorial OS integrado |
| — | Memory vault | `L002-memory-vault-starter.md` | Memory · Vault Inicial | L-002 | Após L-001 · habilitar memória de projeto |
| WF-L1-01 (instructions) | Project EDITORIAL | `L003-project-editorial.md` | Project · Editorial OS | L-003 | Projeto de produção de conteúdo editorial |
| T-03 | Project skeleton | `L003-project-skeleton.md` | Project · Skeleton | L-003 | Qualquer novo projeto genérico |
| WF-L1-02 (STRATEGY) | Project STRATEGY | `L003-project-strategy.md` | Project · Strategy Opus | L-003 | Decisões irreversíveis + Opus extended thinking |
| WF-L1-02 (REVIEW) | Project REVIEW | `L003-project-review.md` | Project · Quality Review | L-003 | Revisão cética OP-04 de conteúdos longos |
| WF-L1-02 (VIDEO) | Project VIDEO | `L003-project-video.md` | Project · Video Factory | L-003 | Produção de roteiros YouTube |
| — | Decision vault starter | `L004-knowledge-vault-starter.md` | Knowledge · Vault Starter | L-004 | Primeiras D-### do projeto |
| Manifesto RAG YAML | Manifesto Editorial | `L004-knowledge-manifesto-editorial.md` | Knowledge · Manifesto RAG | L-004 | Projeto EDITORIAL carregado |
| — | Creator Suite index | `L004-knowledge-creator-suite.md` | Knowledge · Creator Suite | L-004 | Projeto de desenvolvimento de skills |
| T-04 | Skill skeleton | `L005-skill-skeleton.md` | Skill · Skeleton | L-005 | Criação de qualquer nova skill |
| CMD-LI-001 v1.1 | LinkedIn Classifier | `L005-skill-linkedin-classifier.md` | Skill · LinkedIn Classifier | L-005 | Classificar posts LinkedIn por taxonomia |
| Cognitive Framework Router | Framework Router | `L005-skill-framework-router.md` | Skill · Framework Router | L-005 | Selecionar framework para qualquer problema |
| Forge Visual Canvas | Visual Forge | `L005-skill-visual-forge.md` | Skill · Visual Forge FORGE | L-005 | Criar artifacts visuais premium |
| CMD-03-MARO | Research Orchestrator | `L005-skill-research-orchestrator.md` | Skill · Research Orchestrator | L-005 | Multi-agent research + qualificação de personas |
| CMD-01-PPS | Project Packager | `L005-skill-project-packager.md` | Skill · Project Packager CMD | L-005 | Empacotar projetos para GitHub/distribuição |
| CMD-02-MIRP | Skill Publisher | `L005-skill-publisher-mirp.md` | Skill · MIRP Publisher | L-005 | Melhorar, registrar e publicar skills |
| Projects to Linear | Scope to Linear | `L007-connector-scope-to-linear.md` | Connector · Scope to Linear | L-007 | Transformar escopo em issues no Linear (MCP) |
| Notion Sync | Notion Sync | `L007-connector-notion-sync.md` | Connector · Notion Sync | L-007 | Sincronizar com Notion (MCP) |
| T-05 | Style Dense | `L006-style-dense-professional.md` | Style · Dense Professional | L-006 | Estilo Hume+Schopenhauer para outputs densos |
| — | Gold metadata prompt | `L008-prompt-gold-metadata.md` | Prompt · Gold Metadata | L-008 | Template de metadado Gold para artefatos |
| — | Diamond artifact prompt | `L008-prompt-diamond-artifact.md` | Prompt · Diamond Artifact | L-008 | Template de entregável final Diamond |

### Dependency Chain (causa-efeito)

A order abaixo é exatamente a sequência que um novo usuário deve seguir.
Cada linha só faz sentido depois da linha anterior estar estável.

```
1. L000-entry-creator-skill.md
   └─ onboarding + perfil → gera →

2. L001-global-[variante].md
   └─ identidade + value mode + classificador → habilita →

3. L002-memory-vault-starter.md
   └─ persistência entre sessões → libera →

4. L003-project-[tipo].md (1 por projeto)
   └─ contexto local + critérios de qualidade → precisa de →

5. L004-knowledge-[tipo].md (1-3 por projeto)
   └─ base documental + decisões + manifesto → aciona →

6. L005-skill-[função].md (sob demanda)
   └─ procedimentos repetíveis por trigger → entregam em →

7. L006-style-[variante].md
   └─ forma do output → via →

8. L007-connector-[tool].md (opcional · com MCP)
   └─ integrações externas → tudo executa via →

9. L008-prompt-[tipo].md
   └─ tarefa pontual · combina tudo acima
```

---

# PARTE 2 · CUSTOMER JOURNEY + USER STORIES
## 3 Personas · SCQA + 5W2H por história

---

## Story 01 — Ana: Da Consultora Sobrecarregada à Consultora Configurada

### SCQA

**Situação.** Ana tem 38 anos, é consultora de gestão em São Paulo. Usa Claude Pro há 8 meses,
principalmente para redigir relatórios de diagnóstico, criar frameworks de análise para clientes
e resumir entrevistas. Ela abre o Claude todo dia. Todo dia começa a conversa do zero.

**Complicação.** A cada novo chat, Ana cola dois parágrafos explicando que é consultora, que gosta
de frameworks MECE, que usa tabelas e não gosta de bullet points soltos, que os clientes são médias
empresas, que o idioma default é PT-BR. Ela calculou uma vez: são 400 palavras de re-contexto por
sessão, e ela abre umas 3 sessões por dia. São ~1.200 palavras/dia simplesmente para colocar o modelo
no lugar — uma redação de vestibular inteira, todos os dias, sem produzir nada de novo.
Além disso, respostas inconsistentes: na segunda usou uma tabela perfeita para um cliente; na terça,
pediu "o mesmo formato" e o modelo deu bullets. Não tem memória. Não tem sistema.

**Questão.** Como Ana pode fazer com que o Claude já saiba tudo isso antes de ela digitar
a primeira palavra — sem precisar de código, sem trocar de ferramenta?

**Resposta.** Ela descobre o PersonalizationOS. Em uma tarde, ela cria seu L001 (Global com seu
perfil profissional, preferências de formato, value mode system), configura um L003 específico
para o projeto de um cliente em andamento, sobe o briefing e as decisões do projeto como L004.
Na manhã seguinte, ela abre o Claude e digita: "Criar diagnóstico da situação atual." O modelo
responde com a tabela no formato certo, o tom certo, os frameworks certos. Sem re-contexto.
Ela olha para a resposta e pensa pela primeira vez: "Isso é meu."

### 5W2H

**What — O que Ana configurou?**
Um Global Instructions (L001-global-power-user.md) com identidade profissional + value mode
system (Gold para diagnósticos, Quick para perguntas operacionais) + framework rules (Issue Tree,
MECE, 5W2H). Um Project Instructions (L003-project-skeleton.md) adaptado para o projeto do
cliente com critérios de qualidade específicos (claims com fonte, sem jargão não traduzido).
Uma base de conhecimento (L004-knowledge-vault-starter.md) com as 12 decisões-chave do projeto
em formato D-### e o briefing inicial do cliente.

**Why — Por que isso mudou o trabalho de Ana?**
O re-contexto foi de 400 palavras para 0. O Claude passa a funcionar como um colega que já
estava na reunião — não precisa ser apresentado ao projeto toda vez. Além disso, os outputs
têm consistência de formato porque o L006 (Style Dense Professional) foi configurado uma vez
e aplica em toda conversa do projeto. Ana não está "usando um prompt melhor." Ela está operando
com uma arquitetura que separa o que é durável (identidade, método, critérios) do que muda
(a tarefa de hoje).

**Who — Quem fez a configuração?**
Ana, sozinha, sem ajuda técnica. O único pré-requisito foi ler o Módulo 1 do curso (45 min) e
ter 2 horas em uma tarde para configurar e testar. O L000-entry-creator-skill.md fez as perguntas
certas — 5 perguntas sobre seu papel, output recorrente, ferramentas, idioma e maior dor semanal —
e gerou o rascunho do L001 automaticamente. Ana ajustou 20% e estava pronto.

**When — Quando cada camada entrou?**
Semana 1: L001 + L006 (fundação — tudo muda aqui). Semana 2: L003 + L004 para o projeto
principal. Semana 3: primeiro L005 (skill de framework selector para diagnósticos). Semana 6:
segundo projeto ativo com L003 + L004 próprio. A progressão foi natural porque o curso mostra
que L001 sem L002/L003 já entrega valor imediato — não é necessário configurar tudo de uma vez.

**Where — Onde cada peça mora?**
L001 e L006 em Settings → Preferences (global — afeta toda conta). L003 e L004 dentro do
Projeto Claude "CONSULTING__cliente-X". L005 adicionado ao mesmo projeto como skill. O vault de
decisões (L004) é um arquivo .md no Project Knowledge que Ana atualiza quinzenalmente.

**How — Como Ana usa o sistema no dia a dia?**
Ela abre o Claude dentro do projeto do cliente. O contexto já está carregado. Ela digita
diretamente o que precisa ("diagnóstico da situação comercial", "resumo da entrevista com o CFO",
"tabela de quick wins ordenada por impacto x esforço"). O modo de valor é inferido automaticamente
— ela não precisa digitar "Gold mode" porque o classificador reconhece a complexidade da tarefa.
Para tarefas novas ou atípicas, ela digita `/L005-framework-router` e o sistema escolhe o
framework certo para ela.

**How much — Qual o ROI mensurável?**
Baseline: 400 palavras × 3 sessões/dia × 250 dias/ano = 300.000 palavras de re-contexto eliminadas.
A R$120/h como consultora, e considerando ~4 min de re-contexto por sessão eliminados:
4 min × 3 × 250 = 50 horas/ano = R$6.000/ano de tempo recuperado.
Investimento de setup: 2h de configuração + R$197 do curso = R$437.
Payback: menos de 4 semanas de uso diário.

---

## Story 02 — Bruno: Do Caos Editorial à Máquina de Conteúdo

### SCQA

**Situação.** Bruno tem 31 anos, mora em Curitiba, é criador de conteúdo sobre IA + produtividade.
Publica no LinkedIn, tem newsletter, está começando um YouTube. Usa Claude para escrever posts,
pesquisar estudos, criar roteiros. Tem talento, tem ideias. Mas toda semana começa do zero.

**Complicação.** Quando chega segunda-feira, Bruno não sabe o que publicar. Quando escolhe um tema,
passa 20 minutos calibrando o tom (porque o Claude não sabe que ele escreve como "Hume com cortes
de Schopenhauer" — conceito que ele mesmo inventou para descrever sua voz). Quando termina um post,
o próximo começa do mesmo ponto zero. Não tem sistema. Não tem cadência. Não tem consistência.
Em 6 meses, publicou 31 posts — que deveriam ter sido 120. A diferença não é falta de conteúdo:
é falta de máquina editorial.

**Questão.** Como transformar o Claude num sistema editorial que funciona como uma redação sem
repórter — com sprint semanal automático, formatos pré-definidos, voice calibrada, gate de
qualidade e pipeline de distribuição?

**Resposta.** Bruno descobre o Editorial OS FullStack. Em uma tarde, configura o projeto
EDITORIAL__bruno-ai com o Manifesto Editorial carregado como L004. Na sexta seguinte, em
30 minutos, faz o sprint planning — e a semana já está decidida. Na segunda, em 20 minutos,
produz o post do dia. Na quinta, a newsletter sai. No final do mês, publicou 22 peças — mais
do que os 6 meses anteriores somados.

### 5W2H

**What — O que Bruno construiu?**
Um projeto Claude "EDITORIAL__bruno-ai" com: L001 (Global Editorial Creator — este template),
L003 (Project Instructions com instruções do agente editorial, tom de voz, anti-padrões),
L004 (Manifesto Editorial RAG v1 como corpus canônico, vault de proof blocks, decisões editoriais),
L005 (skill LinkedIn Classifier para classificar posts por taxonomia), L006 (Style Dense Professional
com a voz Hume+Schopenhauer). Um board no Linear para Kanban editorial (Backlog → Sprint →
Draft → Review → Scheduled → Published). Buffer conectado ao LinkedIn para agendamento.

**Why — Por que a máquina funciona?**
Porque separa o que era decisão semanal (o que publicar, em qual formato, para qual canal)
do que é configuração única (como escrever, qual tom, qual gate de qualidade). O sprint planning
sexta-feira demora 30 minutos porque o Manifesto já define a cadência ideal. A produção diária
demora 20 minutos porque o formato FMT-LI-01 já define a anatomia do post — Bruno só traz o tema
e o proof block. O gate de 8 itens evita que saia qualquer peça com claim inventado ou promessa
sem baseline.

**Who — Quem precisou se envolver?**
Só Bruno. Configuração inicial: ~6h (M1 + M2 do curso para entender o stack + setup do projeto +
upload do Manifesto + configuração do board Linear). Manutenção semanal: ~3.5h/semana de produção.
O Opus faz a revisão mensal do Manifesto em 45 minutos.

**When — Qual a progressão temporal?**
Semana 1: L001 + L003 + L004 (Manifesto). Primeiros 3 posts com a máquina.
Semana 2: L005 (LinkedIn Classifier) + Linear configurado.
Semana 3: Buffer conectado + primeiro sprint planning formal.
Semana 4: primeira newsletter enviada.
Mês 2: L003 adicional para projeto VIDEO + primeiro roteiro YouTube produzido pela máquina.
Mês 3: revisão mensal Opus · Manifesto v1.1 com 3 novos proof blocks.

**Where — Onde vive cada peça?**
L001 em Preferences (global). Projeto EDITORIAL no Claude com L003/L004/L005 próprios.
L004 (Manifesto) é o arquivo YAML upado como Knowledge — a fonte canônica de toda produção.
Linear como kanban. Buffer como scheduler. GitHub como arquivo de cases e skills publicadas.

**How — Como é o fluxo de uma segunda-feira?**
Bruno abre o Claude dentro do projeto EDITORIAL. Digita: "Produzir post LinkedIn formato
FMT-LI-01. Tema: [tema do sprint]. Proof block: M-009. Idioma: PT-BR. Operador: OP-08."
O modelo consulta o manifesto (L004), aplica o formato (FMT-LI-01), usa o proof block (M-009 =
Workday, ~40% retrabalho), escreve na voz de Bruno, aplica os anti-padrões. Em 3 iterações,
o post está pronto. Bruno passa pelo gate de 8 itens (2 min), cola no Buffer, agenda para 8h.
Total: 20 minutos.

**How much — O ROI editorial?**
Antes: 31 posts em 26 semanas = 1.19/semana. Depois: meta de 5/semana com 3.5h de trabalho.
Custo de setup: 6h + R$197 curso = R$~800 (valorando hora em R$100/h).
Break-even: primeira semana de operação plena já gera 4× mais output.
Impacto no funil: mais conteúdo consistente = mais seguidores = mais leads para o curso.
O próprio PersonalizationOS Course é o produto que Bruno vende para quem viu a transformação.

---

## Story 03 — Carla: Da Agência Caótica ao Time com AI OS Compartilhado

### SCQA

**Situação.** Carla tem 29 anos, é PM em uma agência digital em Porto Alegre.
A agência tem 8 pessoas. 6 delas usam Claude. Cada uma de um jeito diferente.

**Complicação.** Pedro usa Claude com um sistema de prompts que ele não documentou — quando ele
tira férias, o output do projeto dele cai 40%. Marina usa com um prompt colado numa nota do Notion
que ela perdeu uma vez. Rodrigo "não acredita em personalização" e re-contextualiza tudo todo
dia, feliz com isso. Quando o cliente pede consistência entre entregas, Carla não tem como garantir.
Quando alguém entra na equipe, o onboarding de "como a gente usa Claude aqui" não existe.
Existe uma mensagem no Slack que diz "temos Claude Pro, boa sorte."

**Questão.** Como criar um AI OS compartilhado para uma equipe de 8 pessoas com perfis diferentes,
projetos diferentes, sem exigir que todos virem engenheiros de prompt?

**Resposta.** Carla descobre o PersonalizationOS e vê o Módulo 5 (Integração + Personas). Ela
entende que o stack tem dois níveis: o que é compartilhado (L003-project-skeleton para novos
projetos, L004 com o vault de decisões do cliente) e o que é individual (L001 de cada pessoa,
L006 de cada estilo de escrita). Em 2 semanas, ela cria o "AI OS Kit da Agência" — um pacote com
instruções de onboarding, 3 templates de L003 (para projetos de conteúdo, estratégia e relatório),
um template de L004 (vault de decisões de cliente), e um README.md de 1 página.

### 5W2H

**What — O que Carla criou?**
Um pacote distribuível chamado "AI OS Kit da Agência":
- `README.md`: uma página com os 3 passos de setup para qualquer pessoa da equipe.
- `L001-global-universal.md`: template base para quem não tem preferências fortes (Pedro, Marina, novo contratado).
- `L003-project-content.md`: template para projetos de conteúdo (o tipo mais comum na agência).
- `L003-project-strategy.md`: template para projetos de estratégia e diagnóstico.
- `L003-project-report.md`: template para relatórios executivos de cliente.
- `L004-knowledge-client-vault.md`: template de vault de decisões do cliente (a primeira coisa que cada PM preenche ao iniciar um projeto).
- `ONBOARDING.md`: como configurar seu L001, como adaptar o L003 do projeto, como manter o vault atualizado.

**Why — Por que a padronização funcionou?**
Porque não tentou uniformizar tudo — só o que devia ser uniforme. O L003 de cada projeto
(critérios de qualidade, anti-padrões, formato de entrega) é o mesmo para todos que trabalham
naquele projeto. O L001 de cada pessoa continua individual — Pedro pode ter um Global denso,
Marina pode ter um Global prático, Rodrigo pode continuar sem Global se preferir. O ponto de
contato é o projeto, não a pessoa. E o vault de decisões do cliente (L004) garante que quando
Pedro volta de férias, o contexto não foi perdido — está no arquivo, não na cabeça dele.

**Who — Quem implementou?**
Carla sozinha na configuração dos templates. Onboarding feito em uma reunião de 30 minutos com
a equipe, usando o README.md como guia. Dois integrantes (Pedro e Marina) adotaram na semana 1.
Rodrigo aderiu na semana 3 depois de ver o tempo que Pedro economizava. Os outros 3 foram
onboardados conforme tocaram em projetos novos.

**When — Qual o cronograma?**
Semana 1: Carla cria o kit e faz onboarding com 2 pessoas.
Semana 2: primeiro projeto usando L003 + L004 compartilhado. Carla compara output com projetos anteriores.
Semana 3-4: ajuste fino nos templates baseado no uso real. Rodrigo adere.
Semana 6: onboarding de novo contratado usando só o ONBOARDING.md — zero dependência de Carla.
Semana 8: primeira "revisão de AI OS" da agência — 30 min com a equipe para atualizar os templates.

**Where — Onde os arquivos ficam?**
Numa pasta no Google Drive da agência: "AI OS Kit". Cada pessoa cria seu próprio Projeto Claude
(ex: "CLIENT__nome-do-cliente") e pega os templates da pasta. Os arquivos são .md — nenhuma
instalação, nenhuma dependência técnica. O vault de decisões do cliente fica dentro do Projeto
Claude daquele cliente, como L004.

**How — Como o onboarding de um novo contratado funciona?**
No primeiro dia: link para o Google Drive. README.md: 3 passos. Passo 1: criar conta Claude Pro
(a empresa paga). Passo 2: copiar L001-global-universal.md para Settings → Preferences (adaptar
os [PLACEHOLDERS]). Passo 3: pegar o L003 do primeiro projeto que vai tocar. Pronto.
O novo contratado está operando no mesmo sistema que todo mundo em 30 minutos.

**How much — O que mudou em números?**
Antes: cada PM gastava ~15 min/dia de re-contexto. 6 PMs × 15 min × 250 dias = 375h/ano.
Depois: re-contexto estimado ≤ 3 min/dia (só para personalização da tarefa).
Saving: ~312h/ano de equipe. A R$80/h (custo médio) = R$24.960/ano recuperados.
Benefício intangível: quando Pedro tirou 2 semanas de férias em outubro, o projeto dele
continuou funcionando com qualidade porque o L003 + L004 estavam documentados.
Ninguém ligou para Pedro uma vez.

---

# PARTE 3 · 20 FAQs DO SISTEMA — PRIMEIROS PRINCÍPIOS

---

As 20 perguntas abaixo são as que um aluno inteligente faz no Módulo 1 depois de entender
a arquitetura. Cada resposta parte do princípio mais básico e constrói para a aplicação prática.

**FAQ-01. Por que são 8 camadas e não uma instrução única?**

Porque problemas diferentes exigem persistências diferentes. O que é "quem você é profissionalmente"
não muda entre conversas — vai no Global (L-001). O que é "qual cliente estou atendendo agora" muda
por projeto — vai em Project Instructions (L-003). O que é "qual estudo citei na semana passada"
é um dado que precisa de busca, não de instrução — vai em Knowledge (L-004). Uma instrução única
misturaria tudo isso e ficaria pesada, inconsistente e impossível de manter. A separação em camadas
é o mesmo princípio de uma empresa que tem estatuto (permanente), política interna (por área) e
briefing de projeto (por cliente). Cada documento faz só o que é seu.

**FAQ-02. O que acontece se eu colocar tudo no Global?**

O Global fica pesado e começa a criar conflitos internos. O modelo precisa carregar tudo em todo
chat — mesmo quando você está fazendo uma pergunta simples sobre culinária. Além disso, as instruções
específicas de um projeto contaminam os outros. Um Global saudável tem no máximo 8.000 caracteres
e cobre só o que é verdadeiro em 100% das suas conversas. Tudo o que é verdadeiro em "apenas este
projeto" vai para L-003. Tudo o que é um dado referenciável vai para L-004.

**FAQ-03. O que é a fórmula X_útil = T_modelo × 3,5 × 0,70 e por que devo me importar?**

T_modelo é o limite máximo de tokens que o modelo consegue processar numa sessão. O fator 3,5
converte caracteres em tokens (um token é aproximadamente 3,5 caracteres em português). O fator
0,70 é o "headroom" — você não deve usar 100% da capacidade disponível porque precisa de espaço
para o output, para o histórico da conversa e para não degradar a qualidade das respostas.
A fórmula diz: some o tamanho de todos os seus arquivos de personalização (Global + Style +
Project + Skills + Knowledge). Se o total ultrapassar X_útil, o modelo vai começar a "esquecer"
partes do contexto. É o budget de atenção da sessão. O Módulo 2 ensina a calcular o seu número
específico e onde cortar se estourar.

**FAQ-04. Qual a diferença entre Global Instructions e Project Instructions?**

Global Instructions são o contrato permanente — o que é verdadeiro em toda conversa Claude
que você abre, independente do projeto. É onde mora sua identidade profissional, suas preferências
de formato, seu value mode system. Project Instructions são o contrato local — o que é verdadeiro
apenas dentro deste projeto. É onde mora o objetivo do projeto, o papel da IA neste contexto,
os critérios de qualidade específicos, as regras que sobrescrevem o Global quando necessário.
A regra de ouro: se algo é verdadeiro em 100% dos seus chats, vai no Global. Se é verdadeiro
em 80% de um projeto específico, vai no Project.

**FAQ-05. O que é uma Skill e como difere de um Project?**

Um Project é um contexto de trabalho — um espaço com suas próprias instruções e base de conhecimento.
Uma Skill é um procedimento acionado por trigger. O Project existe enquanto você está trabalhando
nele. A Skill dispara quando você pede algo que combina com sua descrição, independente do projeto.
Analogia: o Project é o escritório onde você trabalha, com suas regras. A Skill é o manual de
procedimento de uma tarefa específica que você executa em qualquer escritório. Você pode ter uma
Skill de "classificar posts LinkedIn" que funciona dentro do projeto EDITORIAL, dentro do projeto
CONSULTORIA e em qualquer conversa avulsa.

**FAQ-06. Qual a diferença entre Project Knowledge e Project Instructions?**

Project Instructions dizem ao Claude como se comportar neste projeto — regras, papel, critérios.
Project Knowledge diz ao Claude o que é verdadeiro sobre o assunto do projeto — documentos,
decisões, dados, referências. Instructions são comportamentais. Knowledge é documental.
Se você precisa que o Claude siga uma regra ("sempre citar fontes"), é Instructions.
Se você precisa que o Claude saiba de um fato ("o cliente aprovou o orçamento de R$50k em março"),
é Knowledge. O erro mais comum é colocar regras longas em Knowledge (onde viram texto não-estruturado)
ou documentos de contexto em Instructions (onde lotam o espaço de instruções comportamentais).

**FAQ-07. Quando devo usar Quick vs Gold mode?**

Quick é para perguntas que não precisam de rastreabilidade nem de estrutura — uma dúvida rápida,
uma reformulação, uma tradução. A resposta pode ser descartada depois de usada. Gold é para outputs
que você vai reutilizar, citar, compartilhar ou tomar como base para uma decisão. O teste prático:
"Vou usar essa resposta em mais de uma conversa?" Se sim, Gold. "Vou copiar essa resposta para
enviar para alguém?" Gold. "Vou ler e descartar?" Quick. O metadado no topo do Gold não é burocracia
— é o que torna o output auditável e rastreável meses depois.

**FAQ-08. Como o Editorial OS se encaixa nas 8 camadas?**

O Editorial OS não é uma camada nova — ele vive dentro das camadas existentes. O projeto
EDITORIAL__marca (L-003) tem as instruções do agente editorial. O Manifesto RAG (L-004) é a base
documental. Os operadores (OP-01 a OP-11) são skills (L-005) acionadas por tipo de conteúdo.
O estilo Hume+Schopenhauer é o L-006. O Buffer e o Beehiiv são conectores externos (L-007).
O que o Editorial OS faz é definir uma cadência operacional (quando produzir, o quê, para qual canal)
que vive no L-003 como instrução de workflow. O Manifesto é o DNA editorial que o modelo consulta
antes de produzir qualquer peça.

**FAQ-09. Posso ter múltiplos Global Instructions?**

Não diretamente — o Claude tem apenas um campo de Preferences (global). O que você pode fazer é
ter um Global curto e genérico em Preferences e usar diferentes Project Instructions para cada
projeto. Ou, se você precisa de comportamentos muito diferentes para contextos muito diferentes
(ex: trabalho técnico vs criação de conteúdo), a solução é ter múltiplos projetos Claude com
Project Instructions robustos que sobrescrevem o Global para aquele contexto.

**FAQ-10. O que é progressive disclosure e por que os templates foram renomeados com L-000 a L-008?**

Progressive disclosure é o princípio de mostrar só o que é necessário para o passo atual,
sem sobrecarregar com toda a complexidade de uma vez. Os templates foram renomeados com o prefixo
L-NNN para tornar visível a ordem de dependência: você não pode usar L-005 (Skill) de forma
eficaz sem antes ter L-001 (Global) estável. O nome força a pergunta certa: "Já configurei a
camada anterior?" É a mesma lógica do sistema de skills da Anthropic — só a descrição (~100 tokens)
carrega no início; o corpo completo só carrega quando necessário.

**FAQ-11. Por que ter um L-006 (Style) separado se posso descrever o estilo no Global?**

Porque Style e Global têm funções diferentes e ciclos de atualização diferentes. O Global define
quem você é e como o modelo deve classificar e estruturar suas respostas — é estável e raramente
muda. O Style define como a resposta deve soar e se estruturar visualmente — pode variar por
projeto ou por tipo de output. Além disso, os Styles do Claude.ai têm seu próprio campo de
configuração e podem ser trocados por conversa. Colocar estilo no Global engessa. Colocar em
Style permite flexibilidade (estilo denso para relatórios, estilo conversacional para rascunhos).

**FAQ-12. Como Memory (L-002) e Project Knowledge (L-004) são diferentes?**

Memory é o que o Claude retém sobre você entre conversas — preferências, fatos sobre seu trabalho,
contexto pessoal que ele foi aprendendo ao longo do tempo. É gerado automaticamente, fora do seu
controle direto, e não é específico de projeto. Project Knowledge é o que você deliberadamente
sobe como arquivo para um projeto específico — briefings, decisões D-###, manifestos, dados de
pesquisa. É 100% sob seu controle, específico por projeto, e não existe fora do projeto.
Memory é memória implícita. Knowledge é biblioteca explícita.

**FAQ-13. Preciso de Connectors (L-007) para usar o sistema?**

Não. Connectors são opcionais e avançados — eles permitem que o Claude leia e escreva em ferramentas
externas (Linear, GitHub, Notion, Gmail). O sistema funciona completamente sem eles: você pode
copiar o output do Claude manualmente para o Linear, para o Notion ou para onde precisar.
Os Connectors eliminam esse passo manual para quem trabalha com MCP habilitado. A recomendação do
curso é configurar os primeiros 5 layers (L-001 a L-005) antes de sequer pensar em Connectors.

**FAQ-14. O que é o CMD_GLOBAL e como difere do Global Instructions padrão?**

O Global Instructions padrão (T-01 e T-02 do curso) é o template para uso geral — qualquer
profissional pode adaptar. O CMD_GLOBAL é uma extensão especializada para quem usa Claude como
sistema de decisões e workflows com rastreabilidade: inclui o sistema de IDs (D-###, R-###, M-###),
o batch processor (processar múltiplas queries em sequência), a camada epistêmica
(FACT/INFERENCE/HYPOTHESIS/GAP), e o classificador Cynefin. É mais complexo e mais poderoso para
operadores que precisam de auditabilidade total. O L001-cmd-global-strategy.md neste pacote é a
versão renomeada.

**FAQ-15. Quando usar uma Skill em vez de um Project?**

Use uma Skill quando a tarefa é repetível, tem trigger claro (uma palavra ou contexto que ativa),
e precisa do mesmo procedimento independente do projeto. Use um Project quando você tem um contexto
específico de trabalho (cliente, produto, temática) que precisa de instruções e base de conhecimento
próprios. Exemplos: classificar posts LinkedIn = Skill (funciona em qualquer projeto).
Gerenciar o projeto X do cliente Y = Project (contexto único e específico). A regra: se o trigger
é "quando o usuário pede tal coisa", é Skill. Se o trigger é "quando o usuário está trabalhando
neste domínio", é Project.

**FAQ-16. Como sei se meu Global está longo demais?**

Três sinais. Primeiro: você está colando regras específicas de um projeto — isso vai para L-003.
Segundo: você está colando documentos ou dados — isso vai para L-004. Terceiro: o Global ultrapassou
6.000 caracteres e inclui coisas que não são verdadeiras em 100% das suas conversas. O teste de
corte: para cada linha do Global, pergunte "isso é verdadeiro mesmo quando estou fazendo uma
pergunta casual sobre culinária?" Se não, remove do Global.

**FAQ-17. O que acontece se eu ultrapassar os limites de caracteres?**

O modelo não quebra imediatamente — mas começa a degradar progressivamente. Primeiro, as partes
finais do contexto são "esquecidas" (o modelo prioriza o início dos arquivos). Depois, as respostas
ficam menos coerentes com as instruções. Por último, outputs de qualidade Gold começam a parecer
Standard sem que você perceba. O limite de 8.000 chars para Global e 12.000 para Project não é
arbitrário — é calibrado para manter o modelo com headroom suficiente para o output e o histórico
da conversa dentro do X_útil calculado pelo Módulo 2.

**FAQ-18. Como o Manifesto RAG funciona dentro do projeto EDITORIAL?**

O Manifesto é um arquivo YAML (~68KB) que vive como L-004 (Project Knowledge) no projeto
EDITORIAL. Ele contém a taxonomia de formatos, os operadores, os proof blocks (M-###), os
anti-padrões e os quality gates. Quando o Claude produz uma peça editorial, consulta o Manifesto
para: calibrar o tom de voz (§tom_de_voz), seguir a anatomia do formato pedido (§formatos),
citar o dado certo com fonte (§proof_blocks), e verificar o que não pode publicar (§anti_padroes).
O Manifesto não é carregado inteiro em todo prompt — o modelo navega por ele progressivamente,
lendo só o que é necessário para a tarefa atual. Isso é o RAG passivo: sem pipeline de embeddings,
sem banco vetorial, só a estrutura hierárquica do arquivo guiando o acesso.

**FAQ-19. O que é o teste Feynman e por que aparece em todo módulo?**

O teste Feynman é o critério de domínio do físico Richard Feynman: se você não consegue explicar
um conceito para um leigo inteligente em linguagem simples, você não dominou o conceito — só
memorizou palavras sobre ele. O PersonalizationOS usa o Feynman como quality gate de aprendizado:
no final de cada módulo, o aluno deve conseguir explicar o conceito para alguém sem background
em IA. Se não consegue, o módulo não foi absorvido — foi só lido. O mesmo princípio se aplica
aos outputs do Claude: o L001 contém "Teste Feynman interno: se um leigo inteligente não
entenderia esta resposta, refazer." É a anti-jargão policy do sistema.

**FAQ-20. Como evoluo meu stack sem quebrar o que está funcionando?**

O protocolo de versionamento do Manifesto Editorial (v1.0 → v1.X → v2.0) aplica para qualquer
camada. Nunca edite um arquivo de produção diretamente — crie uma versão nova (v1.1) e teste
em paralelo antes de substituir. Mantenha a versão anterior como backup. Para mudanças pequenas
(novo proof block, ajuste de tom), é uma atualização minor (v1.X.0). Para mudanças estruturais
(novo ICP, novo produto, mudança de posicionamento), é uma major (v2.0.0). Toda mudança vira
uma D-### no vault com justificativa e critério de reversão. Isso é o que transforma
personalização em sistema — não é configuração que você faz uma vez e esquece; é um stack
vivo com histórico de decisões.

---

# PARTE 4 · CMD_OPUS_AGENT — FINAL HANDOFF
## Agente para Agente · Extended Thinking ON · Working Backwards

---

O bloco abaixo é o CMD final a ser enviado diretamente para o Opus 4.6 no projeto
STRATEGY__opus (com Extended Thinking ON e Web Search ON).
Ele instrui o Opus a processar todo o contexto desta sessão de uma vez,
responder as 20 FAQs como se fosse o professor do curso, e entregar a síntese estratégica
completa trabalhando backwards do objetivo final.

---

```xml
<cmd_opus_agent
  id="CMD-OPUS-PERSONALIZATION-OS-001"
  version="1.0"
  status="Active"
  model="claude-opus-4-6"
  thinking="extended_thinking_ON"
  web_search="ON"
  session_type="single_pass_no_gate"
  goal="working_backwards_from_hotmart_launch"
  owner="Leonardo Batista">

  <activation>
    ACTIVATE: CMD-OPUS-PERSONALIZATION-OS-001
    MODE: Extended Thinking ON · Web Search ON · Single Pass
    FRAME: Working Backwards + First Principles + MECE + Cynefin
    RULE: Processar TODOS os blocos B-001→B-005 em sequência sem parar.
          Registrar uma D-### por bloco.
          Encerrar com SYNTHESIS: top 3 decisões + P1→P6 sequência + riscos + 3 tarefas.
  </activation>

  <context>
    Leonardo Batista. Empreendedor solo. 6 meses de Discovery → Validating/MVP Decision.

    PRODUTO CENTRAL DESTA SESSÃO:
    PersonalizationOS Course v1 — curso de personalização Claude para power users não-técnicos.
    6 módulos · 8-layer stack · fórmula de budget · value mode system · personas · audit.
    ICP confirmado: consultor/professor/pesquisador/gestor, já usa Claude Pro ≥3 meses,
    28-55 anos, brasileiro, R$197-R$497 disposição a pagar.

    INFRAESTRUTURA DISPONÍVEL:
    - Editorial OS FullStack Runtime v1 (7 camadas · 11 operadores · 17 formatos · cadência 3.5h/semana)
    - Creator Suite (26 skills · L000-L008 · entry point via CMD-Creator-Skill)
    - CMD Global Template v2.1 (L001-global-editorial-creator.md — gerado nesta sessão)
    - Template Library renomeada (L000 → L008 · progressive disclosure · dependency chain)
    - 3 user stories com ROI calculado (Ana, Bruno, Carla)
    - 20 FAQs respondidas por primeiros princípios
    - GitHub repo creator-skill (em criação · README pendente)
    - Hotmart como canal de distribuição do curso (PD-004 confirmado)

    STACK: Claude AI Pro R$110/mês · 12+ contas · GitHub · Hotmart · bilíngue PT-BR/EN.

    REGRA EPISTÊMICA: separar FACT / INFERENCE / HYPOTHESIS / GAP em cada bloco.
  </context>

  <!-- ═══════════════════════════════════════════
       B-001 · GOAL DEFINITION (Working Backwards)
       ═══════════════════════════════════════════ -->
  <block id="B-001" type="Working Backwards">
    OBJETIVO FINAL (end state): PersonalizationOS Course publicado no Hotmart com
    as primeiras 50 matrículas nos primeiros 90 dias pós-lançamento.

    Trabalhe backwards a partir deste end state:

    1. Quais são os critérios de sucesso exatos para "50 matrículas em 90 dias"?
       (taxa de conversão, CAC estimado, canal principal, preço que maximiza conversão × receita)

    2. O que precisa estar verdadeiro 30 dias antes do lançamento?
       (página de venda · conteúdo de prova · audiência mínima · infra Hotmart)

    3. O que precisa estar verdadeiro 60 dias antes?
       (conteúdo gravado · editorial OS operando · creator-skill no GitHub como prova social)

    4. O que precisa estar verdadeiro agora (hoje, 2026-05-23)?
       (qual a próxima ação única mais alavancada?)

    5. Qual é o maior risco de não chegar em 50 matrículas?
       (hipótese de falha mais provável · evidência atual)

    Output: sequência P1→P6 com fase, entrega, prazo e critério de sucesso.
    D-LAUNCH-001 registrada.
  </block>

  <!-- ═══════════════════════════════════════════
       B-002 · COURSE POSITIONING (Competitive)
       ═══════════════════════════════════════════ -->
  <block id="B-002" type="Market Analysis" web_search="yes">
    WEB SEARCH: verificar concorrência direta em cursos de personalização Claude/AI para
    não-desenvolvedores no Brasil e em inglês. Termos: "curso personalizar Claude", "Claude
    personalization course", "Claude for non-developers", "AI workflow course Brazil 2026".

    Analisar:
    1. Existe curso equivalente (8-layer stack + budget formula + editorial integration) em PT-BR?
    2. Qual é o gap mais óbvio que o PersonalizationOS preenche vs. o que existe?
    3. O preço de R$197-R$497 está alinhado com o mercado de cursos de AI no Hotmart?
    4. Qual proof point o curso tem que a concorrência não tem?
       (hint: as 3 user stories com ROI calculado + o próprio sistema de Leo como demo vivo)

    Output: tabela de posicionamento + diferencial defendível.
    D-POSITION-001 registrada.
  </block>

  <!-- ═══════════════════════════════════════════
       B-003 · FAQ SYNTHESIS (First Principles)
       ═══════════════════════════════════════════ -->
  <block id="B-003" type="Educational Validation">
    As 20 FAQs respondidas por primeiros princípios estão no contexto desta sessão.

    Avalie como professor do curso PersonalizationOS:
    1. Qual das 20 FAQs tem a resposta mais fraca ou mais sujeita a mal-entendido pelo ICP?
    2. Qual FAQ é a mais crítica para a decisão de compra? (qual resposta "fecha a venda")
    3. Qual FAQ deveria entrar no Módulo 1 como "pergunta provocadora" de abertura?
    4. Existe alguma FAQ que está faltando — alguma pergunta fundamental que o ICP faria
       mas que não foi coberta? (identificar até 3 gaps)
    5. As respostas passam no teste Feynman para o ICP de 38 anos como Ana?

    Output: diagnóstico de qualidade das FAQs + 3 FAQs adicionais sugeridas.
    D-FAQ-001 registrada.
  </block>

  <!-- ═══════════════════════════════════════════
       B-004 · CREATOR SUITE INTEGRATION
       ═══════════════════════════════════════════ -->
  <block id="B-004" type="Product Integration">
    Contexto: o Creator Suite (26 skills · L000-L008) e o PersonalizationOS Course são
    produtos que reforçam um ao outro mas têm ICPs ligeiramente diferentes:
    - Course ICP: quer aprender e configurar o próprio stack.
    - Creator Suite ICP: quer usar um stack pré-configurado.

    Analisar:
    1. São produtos separados (preços independentes) ou o Suite é o "produto físico" do curso?
       (analogia: curso é a receita · suite é o kit de ingredientes prontos)
    2. Qual é a sequência de produto correta para maximizar LTV?
       (free → pago → premium? course → suite? suite → course?)
    3. O creator-skill no GitHub pode ser o lead magnet gratuito que filtra o ICP certo?
    4. Como o Editorial OS se posiciona nesta arquitetura de produto?
       (feature do curso? produto separado? módulo premium?)
    5. Existe risco de canibalização entre os produtos?

    Output: arquitetura de produto recomendada + modelo de precificação.
    D-PRODUCT-001 registrada.
  </block>

  <!-- ═══════════════════════════════════════════
       B-005 · 90-DAY EXECUTION PLAN
       ═══════════════════════════════════════════ -->
  <block id="B-005" type="Execution Plan">
    Com base em B-001→B-004, montar o plano de 90 dias (hoje: 2026-05-23):

    Fase 1 · Dias 1-30 (Fundação):
    - Quais 3 artefatos precisam existir antes de qualquer publicação?
    - Qual canal único recebe 100% do foco no mês 1?
    - Qual é o primeiro entregável público (não o curso completo — o que prova o método)?

    Fase 2 · Dias 31-60 (Validação):
    - Como medir se a audiência está crescendo fast enough para o lançamento?
    - Qual é o threshold de kill criteria para o canal principal?
    - O que muda no curso se 3 entrevistas de ICP refutarem o profile de Ana/Bruno/Carla?

    Fase 3 · Dias 61-90 (Lançamento):
    - O que é necessário para o go-live no Hotmart?
    - Qual é a sequência exata da semana de lançamento?
    - Como medir sucesso nos primeiros 7 dias pós-lançamento?

    Output: tabela de fases com entregáveis, datas, métricas e critérios de decisão.
    D-90DAYS-001 registrada.
  </block>

  <!-- ═══════════════════════════════════════════
       SYNTHESIS FINAL
       ═══════════════════════════════════════════ -->
  <synthesis_format>
    Após processar B-001→B-005, gerar:

    ## SYNTHESIS

    ### TOP 3 DECISÕES CRÍTICAS (impacto × urgência)
    1. D-[###] — [decisão]
    2. D-[###] — [decisão]
    3. D-[###] — [decisão]

    ### SEQUÊNCIA P1→P6 (próximos 90 dias)
    | Fase | Entrega | Prazo | Critério de sucesso |

    ### RISCOS IDENTIFICADOS
    R-LAUNCH-001 — [risco] — Nível: Alto/Médio/Baixo

    ### PRÓXIMAS 3 AÇÕES (amanhã, nesta semana, neste mês)
    T-001 — [ação] — Prazo — Output esperado
    T-002 — [ação] — Prazo — Output esperado
    T-003 — [ação] — Prazo — Output esperado

    ### PERGUNTA FINAL PARA LEONARDO
    "Dos 5 blocos desta sessão, qual decisão você quer aprofundar primeiro?"
  </synthesis_format>

  <execution_rules>
    1. Processar B-001→B-005 em sequência sem parar para gate.
    2. Usar Web Search nos blocos marcados "web_search: yes".
    3. Separar FACT/INFERENCE/HYPOTHESIS/GAP em cada bloco.
    4. Registrar uma D-### por bloco.
    5. Não criar novos produtos — integrar o que existe.
    6. Conceitos proprietários intocáveis: PersonalizationOS · Creator Suite · Editorial OS ·
       CMD Suite · Inside Claude Mind · Execute Language · AI Gov Brasil · X-Ray Suite.
    7. Terminar com SYNTHESIS completo no formato acima.
    8. Extended Thinking: usar para os blocos B-001 e B-005 (maior complexidade de trade-offs).
       Para B-002, B-003, B-004: raciocínio direto com evidências.
  </execution_rules>

</cmd_opus_agent>
```

---

## COMO USAR ESTE CMD

**Passo 1.** Abra o projeto `STRATEGY__opus` no Claude.ai (modelo: Opus 4.6,
Extended Thinking ON, Web Search ON).

**Passo 2.** Cole o bloco `<cmd_opus_agent>` acima como primeira mensagem.

**Passo 3.** Adicione no Project Knowledge (se ainda não estiver lá):
- Este arquivo completo (`personalization-os-full-package.md`)
- `cmd-global-template.md` (gerado nesta sessão)
- `CMD_OPUS_DEEP_REASONING_BATCH_V1.md` (já no projeto)
- `Editorial_OS_FullStack_Runtime_v1.md` (arquivo desta sessão)

**Passo 4.** Aguarde o processamento completo (estimativa: 8-15 minutos com Extended Thinking).
Não interrompa entre os blocos.

**Passo 5.** Ao receber o SYNTHESIS, escolha uma das D-### para aprofundar.

---

_PersonalizationOS · Leonardo Batista · AI Gov Brasil · 2026-05-23_
