# CargoSmart (cargosmart)

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

CargoSmart (now operating as IQAX) is a global shipment management software provider that gives shippers, consignees, freight forwarders, and logistics service providers ocean freight booking, container tracking, vessel scheduling, and shipping documentation tools across multiple ocean carriers. CargoSmart co-founded the Global Shipping Business Network (GSBN), a blockchain-based data exchange for carriers, terminals, banks, and customs authorities, and exposes its APIs so trading partners can embed booking, visibility, schedule, and documentation workflows directly into TMS, ERP, and supply-chain platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Booking
- Container
- Documentation
- GSBN
- IQAX
- Logistics
- Maritime
- Ocean Freight
- Schedule
- Shipping
- Supply Chain
- Tracking
- Visibility
- Vessel

## Timestamps

- **Created:** 2025-01-15
- **Modified:** 2026-05-19

## APIs

### CargoSmart Container Booking API

The CargoSmart Container Booking API enables programmatic submission of container booking requests across multiple ocean carriers. APIs support booking creation, amendment, cancellation, and confirmation workflows for shippers, NVOCCs, and logistics service providers.

- **Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)
- **Base URL:** `https://api.cargosmart.com`

#### Tags

- Booking
- Container
- Logistics
- Maritime
- Ocean Freight
- Shipping

#### Properties

- [Documentation](https://www.cargosmart.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cargosmart-shipment-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargosmart-shipment-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CargoSmart Shipment Tracking API

The CargoSmart Shipment Tracking API provides real-time container tracking and shipment visibility across ocean carriers and ports. APIs return container movement events, vessel positions, ETA predictions, and port arrival/departure data for supply chain visibility platforms. An accompanying AsyncAPI channel emits milestone events so subscribers can react without polling.

- **Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)
- **Base URL:** `https://api.cargosmart.com`

#### Tags

- Container
- Logistics
- Maritime
- Shipping
- Tracking
- Visibility

#### Properties

- [Documentation](https://www.cargosmart.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/asyncapi/cargosmart-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/cargosmart-shipment-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargosmart-shipment-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CargoSmart Vessel Schedule API

The CargoSmart Vessel Schedule API provides access to ocean carrier vessel schedules, port rotation data, and sailing frequency information. APIs support route planning, transit time calculation, and carrier selection for ocean freight shippers and forwarders.

- **Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)
- **Base URL:** `https://api.cargosmart.com`

#### Tags

- Logistics
- Maritime
- Port
- Schedule
- Shipping
- Vessel

#### Properties

- [Documentation](https://www.cargosmart.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cargosmart-shipment-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargosmart-shipment-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CargoSmart Shipping Documentation API

The CargoSmart Shipping Documentation API enables electronic exchange of shipping documents including bills of lading, cargo manifests, and customs declarations. APIs and EDI integrations support paperless documentation workflows across carriers, ports, customs authorities, and logistics service providers.

- **Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)
- **Base URL:** `https://api.cargosmart.com`

#### Tags

- Bill of Lading
- Container
- Documentation
- EDI
- Maritime
- Shipping

#### Properties

- [Documentation](https://www.cargosmart.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cargosmart-shipment-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cargosmart-shipment-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.cargosmart.com)
- [Portal](https://www.cargosmart.com/)
- [Documentation](https://www.cargosmart.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/asyncapi/cargosmart-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-container-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-booking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-ld/cargosmart-context.jsonld)
- [G S B N](https://www.gsbn.trade/)
- [I Q A X](https://www.iqax.com/)
- [LinkedIn](https://www.linkedin.com/company/cargosmart-limited/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
