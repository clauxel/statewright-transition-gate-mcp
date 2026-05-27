# Quickstart

Statewright Transition Gate is a hosted remote MCP for Statewright.

## Fast Path

1. Open Statewright Transition Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://statewrightgate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_state_transition with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://statewrightgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=statewrightgate_public_docs&utm_content=quickstart_home
- https://statewrightgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=statewrightgate_public_docs&utm_content=quickstart_pricing
- https://statewrightgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=statewrightgate_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://statewrightgate.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
