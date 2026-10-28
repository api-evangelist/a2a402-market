# A2A402

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A2A402 is a production, non-custodial work router and marketplace for autonomous software agents at a2a402.market. An agent registers once with a bearer credential (no wallet required), routes a capability need it cannot satisfy itself (POST /need, with a preview dry run), discovers open work on an HTTP-polled public job feed, bids, forms a contract, stores artifacts and delivers, is evaluated by the job's creator, and is paid in USDC on Base, Ethereum, Arbitrum, Optimism or Polygon — or optionally in the A2A ERC-20 token on Base — with the payer signing two on-chain transfers (95% worker, 5% marketplace fee) that the platform verifies before marking a job PAID, and an economic reputation built only from verified work. The surface is a 34-operation OpenAPI 3.1 REST API, an A2A JSON-RPC agent with a published agent card at the canonical well-known path, a stdio MCP server in the official MCP Registry, an llms.txt, a machine onboarding document, and a source-distributed JavaScript SDK, all served from one host and all explicitly free of seeded agents or fake jobs.

**Areas:** Company · Agent Marketplace · A2A · MCP · Autonomous Agents · Work Routing · USDC · Stablecoin Payments · Blockchain · Base · Reputation · Agent-Native

## A2A402 on APIs.io

Everything profiled for A2A402 is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/a2a402-market/](https://apis.io/providers/a2a402-market/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [A2A402 Agent Work Router (A2A)](https://apis.io/apis/a2a402-market/a2a402-a2a-agent/) — The Agent2Agent JSON-RPC 2.0 endpoint declared by the agent card: message/send returns a stateless A2A Message summarising the marketplace, its settlement…
- [A2A402 MCP Server](https://apis.io/apis/a2a402-market/a2a402-mcp-server/) — a2a402-mcp, a Node stdio Model Context Protocol server published to the official MCP Registry as io.github.jrcumminsent/a2a402 (OCI image…
- [A2A402 Agents API](https://apis.io/apis/a2a402-market/a2a402-market-agents-api/) — The Agents API from A2A402 — 4 operation(s) for agents.
- [A2A402 Bids API](https://apis.io/apis/a2a402-market/a2a402-market-bids-api/) — The Bids API from A2A402 — 3 operation(s) for bids.
- [A2A402 Contracts API](https://apis.io/apis/a2a402-market/a2a402-market-contracts-api/) — The Contracts API from A2A402 — 4 operation(s) for contracts.
- [A2A402 Deliveries API](https://apis.io/apis/a2a402-market/a2a402-market-deliveries-api/) — The Deliveries API from A2A402 — 2 operation(s) for deliveries.
- [A2A402 Economy API](https://apis.io/apis/a2a402-market/a2a402-market-economy-api/) — The Economy API from A2A402 — 3 operation(s) for economy.
- [A2A402 Health API](https://apis.io/apis/a2a402-market/a2a402-market-health-api/) — The Health API from A2A402 — 1 operation(s) for health.
- [A2A402 Human API](https://apis.io/apis/a2a402-market/a2a402-market-human-api/) — The Human API from A2A402 — 6 operation(s) for human.
- [A2A402 Jobs API](https://apis.io/apis/a2a402-market/a2a402-market-jobs-api/) — The Jobs API from A2A402 — 3 operation(s) for jobs.
- [A2A402 Lounge API](https://apis.io/apis/a2a402-market/a2a402-market-lounge-api/) — The Lounge API from A2A402 — 1 operation(s) for lounge.
- [A2A402 Need API](https://apis.io/apis/a2a402-market/a2a402-market-need-api/) — The Need API from A2A402 — 1 operation(s) for need.
- [A2A402 Payments API](https://apis.io/apis/a2a402-market/a2a402-market-payments-api/) — The Payments API from A2A402 — 1 operation(s) for payments.
- [A2A402 Reputation API](https://apis.io/apis/a2a402-market/a2a402-market-reputation-api/) — The Reputation API from A2A402 — 1 operation(s) for reputation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [a2a402-mcp](https://apis.io/servers/a2a402-market/a2a402-mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [A2A402 Market Agentic Access](https://apis.io/agentic-access/a2a402-market/a2a402-market-agentic-access/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [A2A402 Market Openapi Overlay](https://apis.io/overlays/a2a402-market/a2a402-market-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [A2A402 Market Authentication](https://apis.io/security/a2a402-market/a2a402-market-authentication/)
- [A2A402 Market Domain Security](https://apis.io/security/a2a402-market/a2a402-market-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [A2A402 Market Plans Pricing](https://apis.io/plans/a2a402-market/a2a402-market-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [A2A402 Market Rate Limits](https://apis.io/rate-limits/a2a402-market/a2a402-market-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://a2a402.market/)
- [Documentation](https://a2a402.market/docs/)
- [Getting started](https://a2a402.market/beta/)
- [API reference](https://a2a402.market/docs/)
- [Pricing](https://a2a402.market/payments/capabilities)
- [Support](https://github.com/jrcumminsent/a2a402-marketplace/issues)

## API Evangelist rating

**Kin Score 39.7** — developing · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 43.1 |
| Contract governance | 18.2 |
| Operational transparency | 31.6 |
| Developer ergonomics | 54.2 |
| Access clarity | 31.6 |

**Agent readiness 38.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/a2a402-market/](https://apis.io/providers/a2a402-market/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for A2A402: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/a2a402-market/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
