# CargoSmart

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

CargoSmart (now operating as IQAX) is a global shipment management software provider that gives shippers, consignees, freight forwarders, and logistics service providers ocean freight booking, container tracking, vessel scheduling, and shipping documentation tools across multiple ocean carriers. CargoSmart co-founded the Global Shipping Business Network (GSBN), a blockchain-based data exchange for carriers, terminals, banks, and customs authorities, and exposes its APIs so trading partners can embed booking, visibility, schedule, and documentation workflows directly into TMS, ERP, and supply-chain platforms.

**Areas:** Booking · Containers · GSBN · IQAX · Logistics · Maritime · Ocean Freight · Schedule · Shipping · Supply Chain · Tracking · Visibility

## CargoSmart on APIs.io

Everything profiled for CargoSmart is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cargosmart/](https://apis.io/providers/cargosmart/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [CargoSmart Bookings API](https://apis.io/apis/cargosmart/cargosmart-bookings-api/) — Container booking management
- [CargoSmart Containers API](https://apis.io/apis/cargosmart/cargosmart-containers-api/) — Container tracking and event history
- [CargoSmart Documents API](https://apis.io/apis/cargosmart/cargosmart-documents-api/) — Shipping documentation
- [CargoSmart Shipments API](https://apis.io/apis/cargosmart/cargosmart-shipments-api/) — Shipment visibility and status
- [CargoSmart Vessels API](https://apis.io/apis/cargosmart/cargosmart-vessels-api/) — Vessel position and schedule

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [CargoSmart Shipment Events API](https://apis.io/asyncapis/cargosmart/cargosmart-events-asyncapi/)

#### Event channels (6)

Individual events and webhooks the provider emits.

- [booking.status](https://apis.io/channels/cargosmart/booking-status/)
- [container.event](https://apis.io/channels/cargosmart/container-event/)
- [eta.update](https://apis.io/channels/cargosmart/eta-update/)
- [shipment.milestone](https://apis.io/channels/cargosmart/shipment-milestone/)
- [vessel.arrival](https://apis.io/channels/cargosmart/vessel-arrival/)
- [vessel.departure](https://apis.io/channels/cargosmart/vessel-departure/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cargosmart Agentic Access](https://apis.io/agentic-access/cargosmart/cargosmart-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [CargoSmart Container Booking](https://apis.io/schemas/cargosmart/cargosmart-booking/)
- [CargoSmart Container Tracking](https://apis.io/schemas/cargosmart/cargosmart-container/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cargosmart Context](https://apis.io/jsonld/cargosmart/cargosmart-context/)

#### Collections (6)

Postman and Open Collection request collections.

- [CargoSmart Shipment Tracking Bookings API](https://apis.io/collections/cargosmart/open-cargosmart-bookings-api/)
- [CargoSmart Shipment Tracking Bookings Containers API](https://apis.io/collections/cargosmart/open-cargosmart-containers-api/)
- [CargoSmart Shipment Tracking Bookings Documents API](https://apis.io/collections/cargosmart/open-cargosmart-documents-api/)
- [CargoSmart Shipment Tracking API](https://apis.io/collections/cargosmart/open-cargosmart-shipment-tracking/)
- [CargoSmart Shipment Tracking Bookings Shipments API](https://apis.io/collections/cargosmart/open-cargosmart-shipments-api/)
- [CargoSmart Shipment Tracking Bookings Vessels API](https://apis.io/collections/cargosmart/open-cargosmart-vessels-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [CargoSmart — asyncapi rules](https://apis.io/rules/cargosmart/cargosmart-asyncapi-spectral-rules/)
- [CargoSmart — jsonschema rules](https://apis.io/rules/cargosmart/cargosmart-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cargosmart Authentication](https://apis.io/security/cargosmart/cargosmart-authentication/)
- [Cargosmart Domain Security](https://apis.io/security/cargosmart/cargosmart-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Cargosmart Scopes](https://apis.io/scopes/cargosmart/cargosmart-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cargosmart Plans Pricing](https://apis.io/plans/cargosmart/cargosmart-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cargosmart Rate Limits](https://apis.io/rate-limits/cargosmart/cargosmart-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cargosmart Finops](https://apis.io/finops/cargosmart/cargosmart-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cargosmart.com)
- [Documentation](https://www.cargosmart.com/)

## API Evangelist rating

**Kin Score 32.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 62.4 |
| Contract governance | 13.6 |
| Operational transparency | 5.3 |
| Developer ergonomics | 31.0 |
| Access clarity | 5.3 |

**Agent readiness 19.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cargosmart/](https://apis.io/providers/cargosmart/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for CargoSmart: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cargosmart/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
