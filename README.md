# Polygon.io (polygon-io)

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

Polygon.io (rebranded as Massive in early 2026) provides real-time and historical market data APIs across stocks, options, indices, forex, crypto, and futures via REST, WebSocket streaming, and S3-style flat files. APIs cover trades, quotes, aggregates, snapshots, ticker reference data, and corporate actions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/polygon-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/polygon-io/refs/heads/main/apis.yml)

## Tags

- Fintech
- Market Data
- Stocks
- Options
- Forex
- Crypto
- Indices
- Futures
- WebSockets
- Real-time
- Historical

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Polygon.io Stocks API

Real-time and historical US equity market data including aggregates (minute/hour/day bars), trades, NBBO quotes, snapshots, ticker reference, splits, dividends, and financials. Available via REST and WebSocket.

- **Human URL:** [https://polygon.io/docs/stocks](https://polygon.io/docs/stocks)
- **Base URL:** `https://api.polygon.io`

#### Tags

- Stocks
- Equities
- Market Data
- Real-time

#### Properties

- [Documentation](https://polygon.io/docs/stocks)
- [AsyncAPI](asyncapi/polygon-io-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polygon-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polygon-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polygon.io Options API

OPRA-licensed options market data via REST and WebSocket: aggregates, trades, quotes, snapshots, contract reference, and option chains.

- **Human URL:** [https://polygon.io/docs/options](https://polygon.io/docs/options)
- **Base URL:** `https://api.polygon.io`

#### Tags

- Options
- OPRA
- Market Data

#### Properties

- [Documentation](https://polygon.io/docs/options)
- [AsyncAPI](asyncapi/polygon-io-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polygon-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polygon-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polygon.io Indices API

Real-time and historical index values for major US and global indices via REST and WebSocket.

- **Human URL:** [https://polygon.io/docs/indices](https://polygon.io/docs/indices)
- **Base URL:** `https://api.polygon.io`

#### Tags

- Indices
- Market Data

#### Properties

- [Documentation](https://polygon.io/docs/indices)
- [AsyncAPI](asyncapi/polygon-io-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polygon-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polygon-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polygon.io Forex API

Real-time and historical FX prices for 1,000+ currency pairs via REST and WebSocket.

- **Human URL:** [https://polygon.io/docs/forex](https://polygon.io/docs/forex)
- **Base URL:** `https://api.polygon.io`

#### Tags

- Forex
- FX
- Currencies
- Market Data

#### Properties

- [Documentation](https://polygon.io/docs/forex)
- [AsyncAPI](asyncapi/polygon-io-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polygon-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polygon-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polygon.io Crypto API

Aggregates, trades, snapshots, level-2 books, and L2 streaming for crypto pairs across major exchanges.

- **Human URL:** [https://polygon.io/docs/crypto](https://polygon.io/docs/crypto)
- **Base URL:** `https://api.polygon.io`

#### Tags

- Crypto
- Cryptocurrency
- Market Data

#### Properties

- [Documentation](https://polygon.io/docs/crypto)
- [AsyncAPI](asyncapi/polygon-io-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polygon-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polygon-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polygon.io Futures API

Real-time and historical futures market data including aggregates, trades, quotes, and snapshots.

- **Human URL:** [https://polygon.io/docs/futures](https://polygon.io/docs/futures)
- **Base URL:** `https://api.polygon.io`

#### Tags

- Futures
- Market Data

#### Properties

- [Documentation](https://polygon.io/docs/futures)
- [AsyncAPI](asyncapi/polygon-io-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polygon-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polygon-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/polygon-io)
- [Portal](https://polygon.io/)
- [Documentation](https://polygon.io/docs)
- [Pricing](https://polygon.io/pricing)
- [Status Page](https://status.polygon.io/)
- [Git Hub](https://github.com/polygon-io)
- [Plans](plans/polygon-io-plans-pricing.yml)
- [Rate Limits](rate-limits/polygon-io-rate-limits.yml)
- [Fin Ops](finops/polygon-io-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
