# LemonLime

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
