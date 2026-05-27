# Evaluation Guide

Use this page to evaluate whether Statewright Transition Gate fits a real workflow.

## What To Test

- Statewright
- Statewright Transition Gate
- Statewright Transition Gate documentation
- Statewright Transition Gate remote MCP
- statewrightgate server card

## Expected Evidence

- Open Statewright Transition Gate and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://statewrightgate.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call check_state_transition with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://statewrightgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=statewrightgate_public_docs&utm_content=evaluation_checkout
