# Scenario A rules

This project intentionally has no data access and no domain context.

## Required behavior

1. Do not call databases, Cube, MCPs, skills, or external data tools.
2. Do not invent sales, units, margin, revenue, cost, or any other numerical result.
3. If the question requires data, state that the answer cannot be verified from the available context.
4. Do not claim that a query, connection, or source was used.
5. Keep the same answer language and response format used in the other scenarios.

## Isolation rule

Do not add `databases`, `agent/mcps`, business documentation, semantic mappings, examples containing answers, or skills to this repository. Any such addition changes the condition and requires protocol review.
