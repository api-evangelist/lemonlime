# LemonLime

LemonLime is a San Francisco company (Y Combinator, Summer 2026) building an "AI knowledge
layer for business" — infrastructure that structures a company's documents, processes,
customer history, and institutional knowledge into a foundation frontier models can retrieve
and reason against. It connects to existing business systems (CRMs, document stores, ticketing,
communication, finance) over the Model Context Protocol and deploys role-specific AI agents on
top of that layer.

- Website: https://lemonlime.ai
- Pricing: https://lemonlime.ai/pricing
- Security: https://lemonlime.ai/security
- GitHub: https://github.com/lemonlime-ai

Backed by: y-combinator (Summer 2026)

## API surface

**LemonLime publishes no public developer API.** There is no OpenAPI or Swagger document, no
developer portal or API reference, no SDKs or client libraries in any public registry, no CLI,
and no documented webhook or event surface. LemonLime consumes the Model Context Protocol to
integrate with customer systems; it does **not** publish an MCP server of its own. Artifact
types that require an API contract to ground them (packages, mcp, skills, openapi, asyncapi,
scopes, authentication, errors, conventions, data-model, sandbox, overlays) are therefore
intentionally absent rather than fabricated.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/lemonlime-llms.txt` | searched (verbatim, HTTP 200) |
| Well-Known | `well-known/lemonlime-well-known.yml` | searched (all 404 — recorded negative) |
| Vulnerability disclosure | `security/lemonlime-vulnerability-disclosure.yml` | searched |
| Trust center | `security/lemonlime-trust-center.yml` | searched |
| Domain security | `security/lemonlime-domain-security.yml` | probed |
| Conformance | `conformance/lemonlime-conformance.yml` | searched |
