# ocapi-shop

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

ocapi-shop is a company surfaced via the API Evangelist harvest backlog (source: mcp-registry) and added to the network as a stub for full-pipeline profiling.

**Areas:** AI catalog · No‑commission sales

## ocapi-shop on APIs.io

Everything profiled for ocapi-shop is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ocapi-shop/](https://apis.io/providers/ocapi-shop/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [ocapi-shop Account API](https://apis.io/apis/ocapi-shop/ocapi-shop-account-api/) — The signed-in user and what their token can do.
- [ocapi-shop Categories API](https://apis.io/apis/ocapi-shop/ocapi-shop-categories-api/) — Categories group products on the storefront. Products refer to their category by name, so renaming a category renames it on its products.
- [ocapi-shop Discounts API](https://apis.io/apis/ocapi-shop/ocapi-shop-discounts-api/) — Discount codes customers type at checkout or open as a link (`https://<store>/d/CODE`, or any storefront page with `?discount=CODE`), and automatic…
- [ocapi-shop Domains API](https://apis.io/apis/ocapi-shop/ocapi-shop-domains-api/) — Custom domains for the storefront. Add a domain, have its owner create the DNS record in `dns` at their domain provider, then verify it: a verified…
- [ocapi-shop Drivers API](https://apis.io/apis/ocapi-shop/ocapi-shop-drivers-api/) — The store's own riders for local deliveries. A driver has no Ocapi account: each one gets a private link to a page with the orders assigned to them for the…
- [ocapi-shop Images API](https://apis.io/apis/ocapi-shop/ocapi-shop-images-api/) — Get images into Ocapi, then use the returned `public_url` in a product's `image_urls` or a store's `logo_url` and `cover_url`. Upload a file with a…
- [ocapi-shop Insights API](https://apis.io/apis/ocapi-shop/ocapi-shop-insights-api/) — Storefront analytics and the newsletter's subscribers.
- [ocapi-shop Orders API](https://apis.io/apis/ocapi-shop/ocapi-shop-orders-api/) — Orders placed on the storefront or recorded by hand. Online payments update themselves through the payment provider; orders paid outside Ocapi…
- [ocapi-shop Partners API](https://apis.io/apis/ocapi-shop/ocapi-shop-partners-api/) — For members of the Ocapi partner program: the client stores they brought in or work on, each store's billing status and the partner's earnings. Partners see…
- [ocapi-shop Products API](https://apis.io/apis/ocapi-shop/ocapi-shop-products-api/) — The store's catalog. Products have a price, optional variants (sizes, colors...) with their own price and stock, images, deals (combos, bulk discounts, buy…
- [ocapi-shop Settings API](https://apis.io/apis/ocapi-shop/ocapi-shop-settings-api/) — How the store gets paid and ships (owners only), the greetings that start a customer's WhatsApp message, and the storefront's tracking pixels.
- [ocapi-shop Storefront API](https://apis.io/apis/ocapi-shop/ocapi-shop-storefront-api/) — The storefront's design, as the dashboard's store editor edits it: the look (colors, font, corners), the announcement bar, the home (the profile page, or a…
- [ocapi-shop Stores API](https://apis.io/apis/ocapi-shop/ocapi-shop-stores-api/) — The stores the user owns or is a member of, and their public profile. Start here: every other endpoint takes a `store_id`.
- [ocapi-shop Tables API](https://apis.io/apis/ocapi-shop/ocapi-shop-tables-api/) — Dine-in ordering for cafés and restaurants: each table (or area, like a bar or terrace) has a QR code with a signed link. Scanning it opens the storefront…
- [ocapi-shop Team API](https://apis.io/apis/ocapi-shop/ocapi-shop-team-api/) — Who can manage the store. Owners invite people by email as owners or members, change their role and take their access away.
- [ocapi-shop Webhooks API](https://apis.io/apis/ocapi-shop/ocapi-shop-webhooks-api/) — Webhooks push the store's events to a URL of yours as they happen, instead of you polling for them. Owners only. A store has up to 10 endpoints (IDs…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Ocapi Shop Webhooks](https://apis.io/asyncapis/ocapi-shop/ocapi-shop-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [ocapi-shop Agentic Access](https://apis.io/agentic-access/ocapi-shop/ocapi-shop-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CatalogImport](https://apis.io/schemas/ocapi-shop/ocapi-shop-catalog-import/)
- [CheckoutInput](https://apis.io/schemas/ocapi-shop/ocapi-shop-checkout-input/)
- [Order](https://apis.io/schemas/ocapi-shop/ocapi-shop-order/)
- [Product](https://apis.io/schemas/ocapi-shop/ocapi-shop-product/)
- [ProductInput](https://apis.io/schemas/ocapi-shop/ocapi-shop-product-input/)
- [StorefrontInput](https://apis.io/schemas/ocapi-shop/ocapi-shop-storefront-input/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ocapi Shop Context](https://apis.io/jsonld/ocapi-shop/ocapi-shop-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [ocapi-shop API Rules](https://apis.io/rules/ocapi-shop/ocapi-shop-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [ocapi-shop Authentication](https://apis.io/security/ocapi-shop/ocapi-shop-authentication/)
- [ocapi-shop Domain Security](https://apis.io/security/ocapi-shop/ocapi-shop-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [ocapi-shop Plans Pricing](https://apis.io/plans/ocapi-shop/ocapi-shop-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://ocapi.shop/)
- [Blog](https://ocapi.shop/es/blog)
- [Terms of service](https://ocapi.shop/terms)
- [Privacy policy](https://ocapi.shop/privacy)

## API Evangelist rating

**Kin Score 48.5** — developing · rubric 0.27.0 · scored 2026-11-19

| Facet | Score |
|---|---|
| Discoverability | 48.2 |
| Contract quality | 68.0 |
| Contract governance | 79.1 |
| Operational transparency | 7.9 |
| Developer ergonomics | 20.7 |
| Access clarity | 53.2 |

**Agent readiness 55.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ocapi-shop/](https://apis.io/providers/ocapi-shop/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ocapi-shop: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ocapi-shop/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
