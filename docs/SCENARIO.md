# Scenario A deployment contract

## Required Nao project

```text
Project: tesis-condition-a
Repository: https://github.com/cfocoder/cube_nao_semantic_layer_a.git
Branch: main
```

## Allowed capabilities

```text
LLM: yes
PostgreSQL: no
Cube MCP: no
Business skill: no
Technical schema context: no
```

A deployment should expose no database or MCP tools in the project. The presence of `OPENAI_*` or `OPENROUTER_*` runtime variables is expected; they are model credentials, not data access.
