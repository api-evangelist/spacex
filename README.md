# SpaceX (Community API) (spacex)

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

Community-maintained, open-source REST and GraphQL API for SpaceX data — launches, rockets, capsules, cores, crew, dragons, payloads, ships, landpads, launchpads, Starlink satellites, the Tesla Roadster ephemeris, company info, and historical events. Operated by the r-spacex community (the same group behind the r/SpaceX subreddit) and licensed Apache 2.0. The canonical hosted base URL is https://api.spacexdata.com and the canonical source repository is https://github.com/r-spacex/SpaceX-API.
The API is currently in MAINTENANCE-ONLY MODE as of 2024. New launches and missions are NOT being added to the dataset; the project remains online for historical lookups and as a teaching/sample API. This makes it an excellent fixture for SDK tutorials, MCP server demos, and API design exercises, but it is no longer a live source of upcoming SpaceX flight data.
The data is organized as a MongoDB document store with cross-resource UUID references; the /query endpoints expose mongoose-paginate-v2 with full MongoDB find()/options semantics. Authentication is only required for destructive (create/update/delete) admin routes; all read operations are public. This community project is not affiliated with, endorsed by, or officially connected to Space Exploration Technologies Corp.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spacex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spacex/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Space
- Launch
- Satellites
- Starlink
- Falcon 9
- Falcon Heavy
- Dragon
- Rockets
- Open Source
- Community
- REST
- GraphQL
- Open Data

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### SpaceX REST API (v4 + v5)

Open-source REST API exposing all SpaceX launch, rocket, capsule, core, crew, dragon, ship, landpad, launchpad, payload, Starlink, Roadster, company, and history data. v4 is the canonical resource surface; the Launches resource also has a v5 surface that omits the v4 response/query transforms. Read operations are unauthenticated; destructive operations require an x-spacex-key header.

- **Human URL:** [https://github.com/r-spacex/SpaceX-API](https://github.com/r-spacex/SpaceX-API)
- **Base URL:** `https://api.spacexdata.com`

#### Tags

- Launches
- Rockets
- Capsules
- Cores
- Crew
- Dragons
- Payloads
- Ships
- Landpads
- Launchpads
- Starlink
- Roadster
- Company
- History

#### Properties

- [Documentation](https://github.com/r-spacex/SpaceX-API/tree/master/docs)
- [Getting Started](https://github.com/r-spacex/SpaceX-API/blob/master/README.md)
- [Source Code](https://github.com/r-spacex/SpaceX-API)
- [OpenAPI](openapi/spacex-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spacex-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spacex-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman](https://app.getpostman.com/run-collection/ed4ed700dcc55b2c1f1c) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [License](https://github.com/r-spacex/SpaceX-API/blob/master/LICENSE)
- [Changelog](https://github.com/r-spacex/SpaceX-API/releases)
- [Status](https://status.spacexdata.com)
- [Backups](https://backups.spacexdata.com)
- [JSON Schema](json-schema/spacex-launch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-rocket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-capsule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-core-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-crew-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-dragon-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-ship-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-launchpad-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-landpad-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-starlink-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-roadster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-company-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spacex-history-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [SDK](https://github.com/Tearth/Oddity)
- [SDK](https://github.com/SaidBySolo/SpaceXPy)
- [SDK](https://github.com/SaiBalaji22/KSBSpacexKit)
- [SDK](https://github.com/AzuxDario/Marsy)
- [SDK](https://github.com/AkiaCode/spacex-api.js)
- [SDK](https://github.com/ahsanz024/spacex_api)
- [SDK](https://github.com/victorperez/spacex-api-ruby)
- [SDK](https://github.com/artfultom/spacex-api)

### SpaceX GraphQL API (community)

Community-maintained GraphQL gateways over the SpaceX REST data, providing typed schema access and nested-field selection across launches, rockets, missions, payloads, ships, and crew. Multiple community gateways exist; the SpaceXLand/api project is the most widely cited reference implementation. Like the REST surface, the underlying dataset is in maintenance-only mode as of 2024.

- **Human URL:** [https://github.com/SpaceXLand/api](https://github.com/SpaceXLand/api)

#### Tags

- GraphQL
- Launches
- Rockets
- Missions

#### Properties

- [Documentation](https://github.com/SpaceXLand/api)
- [Source Code](https://github.com/SpaceXLand/api)
- [Graph Q L Alternative](https://github.com/jor-dan/SpaceX-GraphQL)
- [Graph Q L Alternative](https://github.com/Kartikkumargujarati/xploration-graphql)
- [Graph Q L Alternative](https://github.com/kevinstd/spacex-graphql-gateway)
- [Postman Collection](collections/spacex-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spacex-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://github.com/r-spacex/SpaceX-API)
- [GitHub Organization](https://github.com/r-spacex)
- [Source Code](https://github.com/r-spacex/SpaceX-API)
- [License](https://github.com/r-spacex/SpaceX-API/blob/master/LICENSE)
- [Documentation](https://github.com/r-spacex/SpaceX-API/tree/master/docs)
- [Getting Started](https://github.com/r-spacex/SpaceX-API/blob/master/README.md)
- [Changelog](https://github.com/r-spacex/SpaceX-API/releases)
- [Issues](https://github.com/r-spacex/SpaceX-API/issues)
- [Pull Requests](https://github.com/r-spacex/SpaceX-API/pulls)
- [Status](https://status.spacexdata.com)
- [Backups](https://backups.spacexdata.com)
- [Docker Image](https://hub.docker.com/r/jakewmeyer/spacex-api/)
- [Clients](https://github.com/r-spacex/SpaceX-API/blob/master/docs/clients.md)
- [Apps](https://github.com/r-spacex/SpaceX-API/blob/master/docs/apps.md)
- [A P I Style Guide](https://github.com/r-spacex/api-style-guide)
- [Subreddit](https://www.reddit.com/r/spacex/)
- [Plans](plans/spacex-plans-pricing.yml)
- [Rate Limits](rate-limits/spacex-rate-limits.yml)
- [Spectral Rules](rules/spacex-rules.yml)
- [Vocabulary](vocabulary/spacex-vocabulary.yml)
- [J S O N L D Context](json-ld/spacex-context.jsonld)
- [Tools](https://github.com/fercervantesx/lnl-spacex-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
