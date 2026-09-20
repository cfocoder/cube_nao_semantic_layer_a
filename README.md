# Scenario A — LLM baseline without data access

This repository is the Nao Multi-project context for formal scenario **A**.

## Boundary

- No PostgreSQL connection.
- No Cube Core connection or MCP.
- No business skill, semantic documentation, table schema, or benchmark mapping.
- The agent must answer only from the user prompt and conversation state.
- The agent must not invent numerical answers or claim to have queried data.

This is a formal baseline repository, not the general Nao/Cube feature laboratory. Use the same model, prompt, question, language, and response format as B, C, and D; change only the available capabilities.

## Project mapping

- Nao project: `tesis-condition-a`
- Repository: `cfocoder/cube_nao_semantic_layer_a`
- Expected route: LLM without tools
