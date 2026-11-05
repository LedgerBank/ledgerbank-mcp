# ledgerbank-mcp: scope

- Expose reviewed financial capabilities through a model-independent interface.
- Bind tools to the authenticated user, organization and granted scopes.
- Separate queries and prepared actions from approval and execution.
- Specify tool schemas, evidence references, refusals and audit events.

## Boundaries

Public interfaces must not expose provider credentials, internal operator surfaces, customer data or privileged configuration. Product agents use scoped capabilities; development-agent orchestration has a separate role.
