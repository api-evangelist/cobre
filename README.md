# Cobre

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

Cobre is a Latin American B2B payments and treasury platform that gives finance teams, fintechs, PSPs and banks a single API and portal to move money in and out of Colombia and Mexico (and via Fedwire in the United States) and across borders. Its modular products cover Local Payments (Bre-B, Fast Pay, ACH and PSE in Colombia; SPEI and CLABEs in Mexico), Cross Border Payments with FX quotes, Global Payouts in stablecoins, and Connect for centralizing and reconciling bank accounts. The developer API is a REST platform (v1) with bearer-JWT auth via a credential exchange, required idempotency on money movements, page-based pagination, a 30 TPS rate limit, HMAC-signed webhook notifications, and a full portal for maker-checker approvals, reconciliation and reporting. Cobre is a QED Investors portfolio company.

**Areas:** Company · Fintech · Payments · Treasury · Money Movement · Cross-Border Payments · Foreign Exchange · Stablecoins · Banking · Latin America · Colombia · Mexico

## Cobre on APIs.io

Everything profiled for Cobre is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cobre/](https://apis.io/providers/cobre/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Cobre Platform API](https://apis.io/apis/cobre/cobre-platform-api/) — Cobre's REST API (v1) for local and cross-border money movements, accounts and balances, counterparties, Bre-B keys, FX quotes, stablecoin payouts,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (2)

Event-driven and webhook contracts.

- [Cobre Notifications & Subscriptions](https://apis.io/asyncapis/cobre/cobre-events-asyncapi/)
- [Cobre Events Webhooks](https://apis.io/asyncapis/cobre/cobre-events-webhooks/)

#### Event channels (35)

Individual events and webhooks the provider emits.

- [accounts.balance.credit](https://apis.io/channels/cobre/accounts-balance-credit/)
- [accounts.balance.debit](https://apis.io/channels/cobre/accounts-balance-debit/)
- [accounts.linked_wallets.created](https://apis.io/channels/cobre/accounts-linked-wallets-created/)
- [alerts.fx_rate.triggered](https://apis.io/channels/cobre/alerts-fx-rate-triggered/)
- [bulk_money_movements.status.canceled](https://apis.io/channels/cobre/bulk-money-movements-status-canceled/)
- [bulk_money_movements.status.completed](https://apis.io/channels/cobre/bulk-money-movements-status-completed/)
- [bulk_money_movements.status.failed](https://apis.io/channels/cobre/bulk-money-movements-status-failed/)
- [bulk_money_movements.status.pending_approval](https://apis.io/channels/cobre/bulk-money-movements-status-pending-approval/)
- [bulk_money_movements.status.processing](https://apis.io/channels/cobre/bulk-money-movements-status-processing/)
- [bulk_money_movements.status.validating](https://apis.io/channels/cobre/bulk-money-movements-status-validating/)
- [cobre_keys.status.disabled](https://apis.io/channels/cobre/cobre-keys-status-disabled/)
- [cobre_keys.status.failed](https://apis.io/channels/cobre/cobre-keys-status-failed/)
- [cobre_keys.status.processing](https://apis.io/channels/cobre/cobre-keys-status-processing/)
- [cobre_keys.status.registered](https://apis.io/channels/cobre/cobre-keys-status-registered/)
- [cobre_keys.status.unregistered](https://apis.io/channels/cobre/cobre-keys-status-unregistered/)
- [counterparty.status.failed](https://apis.io/channels/cobre/counterparty-status-failed/)
- [counterparty.status.processing](https://apis.io/channels/cobre/counterparty-status-processing/)
- [counterparty.status.verified](https://apis.io/channels/cobre/counterparty-status-verified/)
- [cross_border_money_movements.status.completed](https://apis.io/channels/cobre/cross-border-money-movements-status-completed/)
- [cross_border_money_movements.status.initiated](https://apis.io/channels/cobre/cross-border-money-movements-status-initiated/)
- [cross_border_money_movements.status.processing](https://apis.io/channels/cobre/cross-border-money-movements-status-processing/)
- [cross_border_money_movements.status.rejected](https://apis.io/channels/cobre/cross-border-money-movements-status-rejected/)
- [evidence-request.ask](https://apis.io/channels/cobre/evidence-request-ask/)
- [money_movements.status.canceled](https://apis.io/channels/cobre/money-movements-status-canceled/)
- [money_movements.status.completed](https://apis.io/channels/cobre/money-movements-status-completed/)
- …and 10 more published on APIs.io

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Cobre API Documentation](https://apis.io/servers/cobre/cobre-api-documentation/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cobre Authentication](https://apis.io/security/cobre/cobre-authentication/)
- [Cobre Domain Security](https://apis.io/security/cobre/cobre-domain-security/)

#### Rate limits (1)

Published request limits.

- [Cobre Rate Limits](https://apis.io/rate-limits/cobre/cobre-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cobre.com/en-us)
- [Documentation](https://docs.cobre.com/get-started-1737317m0)
- [Getting started](https://docs.cobre.com/get-started-1737317m0)
- [API reference](https://docs.cobre.com/quick-start-1886551m0)
- [Support](https://docs.cobre.com/troubleshooting-support-1886537m0)
- [Blog](https://www.cobre.com/blog)
- [Compliance](https://docs.cobre.com/security-at-cobre-1737320m0)
- [Status](https://status.cobre.co/)

## API Evangelist rating

**Kin Score 39.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 40.6 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 64.3 |
| Access clarity | 7.9 |

**Agent readiness 31.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 17.3** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cobre/](https://apis.io/providers/cobre/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cobre: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cobre/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
