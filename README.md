# HTX

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

HTX (formerly Huobi Global) is a cryptocurrency exchange founded in 2013 that offers spot trading, futures and derivatives, margin trading, trading bots, copy trading, and earn/staking products across BTC, ETH, XRP and 600+ digital assets. HTX exposes a public developer platform (HTX Open Platform) with a REST API and a WebSocket streaming API covering market data, account and wallet management, sub-user administration, spot and conditional order placement, and cross/isolated margin lending. Requests are authenticated with an AccessKey and an HMAC-SHA256 (Signature Version 2) request signature. Official client SDKs are published under the HuobiRDCenter GitHub organization for Java, Python, Go, C++ and C#, with separate contract/futures variants. HTX was surfaced as a portfolio company of Hongshan (formerly Sequoia Capital China).

**Areas:** Company · Technology · Cryptocurrency · Cryptocurrency Exchange · Trading · Digital Assets · Blockchain · Financial Services · Market Data · WebSocket

## HTX on APIs.io

Everything profiled for HTX is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/htx/](https://apis.io/providers/htx/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [HTX Spot REST API](https://apis.io/apis/htx/htx-spot-api/) — The HTX Spot REST API provides HTTP access to reference data (system status, symbols, currencies, chains), market data (klines, tickers, depth, trades, 24h…
- [HTX WebSocket API](https://apis.io/apis/htx/htx-websocket-api/) — The HTX WebSocket API provides a two-way real-time channel for subscribing to market data (klines, market depth, trade detail, best bid/offer) and to…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Huobi / HTX WebSocket API](https://apis.io/asyncapis/htx/htx-websocket-asyncapi/)

#### Event channels (19)

Individual events and webhooks the provider emits.

- [accounts.list](https://apis.io/channels/htx/accounts-list/)
- [accounts.update#{mode}](https://apis.io/channels/htx/accounts-update-mode/)
- [auth](https://apis.io/channels/htx/auth/)
- [market.{symbol}.bbo](https://apis.io/channels/htx/market-symbol-bbo/)
- [market.{symbol}.depth.{type}](https://apis.io/channels/htx/market-symbol-depth-type/)
- [market.{symbol}.detail](https://apis.io/channels/htx/market-symbol-detail/)
- [market.{symbol}.etp](https://apis.io/channels/htx/market-symbol-etp/)
- [market.{symbol}.kline.{period}](https://apis.io/channels/htx/market-symbol-kline-period/)
- [market.{symbol}.mbp.{levels}](https://apis.io/channels/htx/market-symbol-mbp-levels/)
- [market.{symbol}.mbp.refresh.{levels}](https://apis.io/channels/htx/market-symbol-mbp-refresh-levels/)
- [market.{symbol}.ticker](https://apis.io/channels/htx/market-symbol-ticker/)
- [market.{symbol}.trade.detail](https://apis.io/channels/htx/market-symbol-trade-detail/)
- [market.tickers](https://apis.io/channels/htx/market-tickers/)
- [orders.detail](https://apis.io/channels/htx/orders-detail/)
- [orders.list](https://apis.io/channels/htx/orders-list/)
- [orders#{symbol}](https://apis.io/channels/htx/orders-symbol/)
- [ping](https://apis.io/channels/htx/ping/)
- [ping-v2](https://apis.io/channels/htx/ping-v2/)
- [trade.clearing#{symbol}](https://apis.io/channels/htx/trade-clearing-symbol/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Htx Authentication](https://apis.io/security/htx/htx-authentication/)
- [Htx Domain Security](https://apis.io/security/htx/htx-domain-security/)

#### Rate limits (1)

Published request limits.

- [Htx Rate Limits](https://apis.io/rate-limits/htx/htx-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://htx.com)
- [Documentation](https://www.htx.com/en-us/opend/newApiPages/)
- [Getting started](https://www.htx.com/support/360000203002)
- [API reference](https://huobiapi.github.io/docs/spot/v1/en/)
- [Sign up](https://www.htx.com/en-us/register/)
- [Support](https://www.htx.com/support/)
- [Blog](https://www.htx.com/news/)
- [Terms of service](https://www.htx.com/support/360000298561/)
- [Privacy policy](https://www.htx.com/en-us/about/privacy/)
- [GitHub](https://github.com/HuobiRDCenter)

## API Evangelist rating

**Kin Score 44.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 43.8 |
| Contract governance | 4.5 |
| Operational transparency | 47.4 |
| Developer ergonomics | 64.3 |
| Access clarity | 34.2 |

**Agent readiness 21.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
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

**Regulatory alignment 23.1** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/htx/](https://apis.io/providers/htx/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HTX: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/htx/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
