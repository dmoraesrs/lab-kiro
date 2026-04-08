# CLAUDE.md - Lab Kiro

Sempre responda em português brasileiro (pt-BR).

## Sobre

Projeto de lab para testar o toolkit FDEV — API Python com FastAPI para demonstrar o fluxo Kiro + Claude Code.

## Stack

Python 3.12, FastAPI, SQLAlchemy, Pydantic v2, pytest, ruff, mypy.

## Comandos Disponíveis

- `/planejar` — Criar spec de feature (requirements → design → tasks)
- `/codificar` — Implementar com Context7 (docs) e Serena (navegação semântica)
- `/revisar` — Code review com classificação de severidade
- `/testar` — Criar testes baseados nos critérios de aceitação
- `/refatorar` — Refactoring seguro com Serena
- `/documentar` — Gerar documentação
- `/deploy` — CI/CD e Dockerfile
- `/setup-projeto` — Configurar guardrails
- `/secure-coding` — Review OWASP
- `/design-system` — Padrões UI (se tiver frontend)

## Convenções

- Commits: conventional commits (`feat:`, `fix:`, `test:`, `docs:`)
- Branches: `feat/descricao`, `fix/descricao`
- Testes: cobertura >= 80%
- Linter: ruff (profile recommended)
