# CargoSmart (cargosmart)
CargoSmart (now operating as IQAX) is a global shipment management software provider that gives shippers, consignees, freight forwarders, and logistics service providers ocean freight booking, container tracking, vessel scheduling, and shipping documentation tools across multiple ocean carriers. CargoSmart co-founded the Global Shipping Business Network (GSBN), a blockchain-based data exchange for carriers, terminals, banks, and customs authorities, and exposes its APIs so trading partners can embed booking, visibility, schedule, and documentation workflows directly into TMS, ERP, and supply-chain platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
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

## Overview

CargoSmart Limited has been a long-running provider of shipment management services and is the technology partner behind the Global Shipping Business Network (GSBN) - a blockchain data exchange initially backed by nine shipping industry leaders including COSCO, OOCL, CMA CGM, Hapag-Lloyd, and major port terminals. The company has rebranded several of its offerings under IQAX for digital trade and cargo release applications. CargoSmart's platform surfaces four related API areas: container booking, real-time shipment tracking (with an AsyncAPI event stream), vessel schedules, and shipping documentation exchange. The repo ships OpenAPI, AsyncAPI, JSON Schema, and JSON-LD artifacts that downstream consumers can use to model container and booking entities.

## APIs

### CargoSmart Container Booking API
The CargoSmart Container Booking API enables programmatic submission of container booking requests across multiple ocean carriers. APIs support booking creation, amendment, cancellation, and confirmation workflows for shippers, NVOCCs, and logistics service providers.

**Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)
**Base URL:** https://api.cargosmart.com

#### Features
- Multi-carrier container booking submission
- Booking creation, amendment, and cancellation
- Acknowledgment and confirmation callbacks
- Shipper, NVOCC, and LSP role support
- Integration with carrier back-ends via CargoSmart

#### Use Cases
- Shipper TMS booking automation
- NVOCC consolidation booking
- Freight forwarder tender flow
- Enterprise ERP-to-carrier booking integration

### CargoSmart Shipment Tracking API
Real-time container tracking and shipment visibility across ocean carriers and ports. Returns container movement events, vessel positions, ETA predictions, and port arrival/departure data. An accompanying AsyncAPI channel emits milestone events so subscribers can react without polling.

**Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)

#### Features
- Real-time container movement events
- Vessel position and ETA predictions
- Port arrival/departure milestones
- AsyncAPI event channel for push delivery
- Cross-carrier normalized schema
- Exception and delay detection

#### Use Cases
- Supply-chain visibility platforms
- Customer self-service tracking portals
- Proactive exception management and ETA-based allocation
- Carrier performance analytics

### CargoSmart Vessel Schedule API
Ocean carrier vessel schedules, port rotation data, and sailing frequency information. Supports route planning, transit time calculation, and carrier selection.

**Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)

#### Features
- Carrier vessel schedule lookup
- Port rotation and sailing frequency data
- Transit time calculation by lane
- Multi-carrier normalized schema

#### Use Cases
- Route planning and carrier selection
- Transit time SLAs for customer quotes
- Sailing calendar feeds in TMS platforms

### CargoSmart Shipping Documentation API
Electronic exchange of shipping documents including bills of lading, cargo manifests, and customs declarations via API and EDI.

**Human URL:** [https://www.cargosmart.com/](https://www.cargosmart.com/)

#### Features
- Bill of lading and manifest exchange
- Customs declaration integration
- API plus EDI support
- GSBN-aligned document workflows

#### Use Cases
- Paperless carrier documentation
- Port and customs authority integration
- LSP document hub aggregation

## Common Properties

- [Website](https://www.cargosmart.com)
- [Portal](https://www.cargosmart.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/asyncapi/cargosmart-events-asyncapi.yml)
- [Container JSON Schema](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-container-schema.json)
- [Booking JSON Schema](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-booking-schema.json)
- [JSON-LD Context](https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-ld/cargosmart-context.jsonld)
- [GSBN](https://www.gsbn.trade/)
- [IQAX](https://www.iqax.com/)
- [LinkedIn](https://www.linkedin.com/company/cargosmart-limited/)

## Timestamps

- **Created:** 2025-01-15
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
