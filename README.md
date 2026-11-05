# ledgerbank-mcp

MCP interface design for financial assistants.

**Status: presentation preview.** This repository contains scope and design documentation. It does not contain a released implementation or a live service.

## Role in the headless platform

LedgerBank is being organized around a common financial capability layer. Applications,
accounting workflows, SDKs, the CLI and agents are intended to consume that layer through
reviewed interfaces. Financial authority and permissions remain in the platform.

**Primary audience:** agents. **Repository visibility:** public.

## Planned scope

- Expose reviewed financial capabilities through a model-independent interface.
- Bind tools to the authenticated user, organization and granted scopes.
- Separate queries and prepared actions from approval and execution.
- Specify tool schemas, evidence references, refusals and audit events.

## Read next

- [Scope and boundaries](docs/SCOPE.md)
- [First implementation acceptance criteria](docs/ACCEPTANCE.md)
- [Current repository status](STATUS.md)
- [developers](https://github.com/LedgerBank/developers) for the proposed public architecture and integration map

## Preview boundary

This is a new presentation scaffold. Existing repositories, branches, services and
documents have not been migrated here. Package names, hosted endpoints, releases and
support commitments will be documented only when they exist and have been verified.
