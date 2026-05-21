# AI Gov Brasil · Project Admin Consultant — Skill Package

**ID:** SK-002  
**Versão:** V-20260521-002  
**Status:** Active  
**Formato:** Full-directory skill package

## Estrutura

```text
ai-gov-brasil-project-admin-consultant/
├── SKILL.md
├── README_INSTALL.md
├── manifest.json
├── knowledge/
├── commands/
├── templates/
├── workflows/
├── evals/
└── web/
```

## Instalação em Claude Code

```bash
cp -R ai-gov-brasil-project-admin-consultant ~/.claude/skills/
```

Teste:

```text
Use a skill ai-gov-brasil-project-admin-consultant. fase?
```

## Instalação em Claude Project

1. Cole `SKILL.md` nas instruções do projeto.
2. Faça upload dos arquivos de `knowledge/`, `commands/`, `templates/` e `workflows/`.
3. Use: `Ative SK-002. Consulte o master doc do projeto...`

## Observação

`SKILL.md` é o operador. `knowledge/` é a memória. `commands/` são blocos prontos. `templates/` padronizam saída.
