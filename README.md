# SpaceX (Community API) (spacex)

Community-maintained, open-source REST and GraphQL API for SpaceX data — launches, rockets, capsules, cores, crew, dragons, payloads, ships, landpads, launchpads, Starlink satellites, the Tesla Roadster ephemeris, company info, and historical events. Operated by the r-spacex community (the same group behind the r/SpaceX subreddit) and licensed Apache 2.0. The canonical hosted base URL is https://api.spacexdata.com and the canonical source repository is https://github.com/r-spacex/SpaceX-API.

**Status:** Maintenance-only as of 2024. New launches and missions are NOT being added to the dataset; the project remains online for historical lookups and as a teaching/sample API. This makes it an excellent fixture for SDK tutorials, MCP server demos, and API design exercises, but it is no longer a live source of upcoming SpaceX flight data.

**Disclaimer:** This community project is not affiliated with, endorsed by, or officially connected to Space Exploration Technologies Corp.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/spacex/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Space, Launch, Satellites, Starlink, Falcon 9, Falcon Heavy, Dragon, Rockets, Open Source, Community, REST, GraphQL, Open Data

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### SpaceX REST API (v4 + v5)

Open-source REST API exposing all SpaceX launch, rocket, capsule, core, crew, dragon, ship, landpad, launchpad, payload, Starlink, Roadster, company, and history data. v4 is the canonical resource surface; the Launches resource also has a v5 surface that omits the v4 response/query transforms. Read operations are unauthenticated; destructive operations require an `spacex-key` header.

**Human URL:** [https://github.com/r-spacex/SpaceX-API](https://github.com/r-spacex/SpaceX-API)

**Base URL:** `https://api.spacexdata.com`

#### Tags

Launches, Rockets, Capsules, Cores, Crew, Dragons, Payloads, Ships, Landpads, Launchpads, Starlink, Roadster, Company, History

#### Properties

- [Documentation](https://github.com/r-spacex/SpaceX-API/tree/master/docs)
- [Getting Started](https://github.com/r-spacex/SpaceX-API/blob/master/README.md)
- [Source Code](https://github.com/r-spacex/SpaceX-API)
- [OpenAPI](openapi/spacex-rest-api-openapi.yml)
- [Postman](https://app.getpostman.com/run-collection/ed4ed700dcc55b2c1f1c)
- [License (Apache 2.0)](https://github.com/r-spacex/SpaceX-API/blob/master/LICENSE)
- [Changelog](https://github.com/r-spacex/SpaceX-API/releases)
- [Status](https://status.spacexdata.com)
- [Backups](https://backups.spacexdata.com)

### SpaceX GraphQL API (community)

Community-maintained GraphQL gateways over the SpaceX REST data, providing typed schema access and nested-field selection across launches, rockets, missions, payloads, ships, and crew. Multiple community gateways exist; the SpaceXLand/api project is the most widely cited reference implementation. Like the REST surface, the underlying dataset is in maintenance-only mode as of 2024.

**Human URL:** [https://github.com/SpaceXLand/api](https://github.com/SpaceXLand/api)

#### Tags

GraphQL, Launches, Rockets, Missions

#### Properties

- [Documentation](https://github.com/SpaceXLand/api)
- [Source Code](https://github.com/SpaceXLand/api)
- GraphQL Alternative: [SpaceX-GraphQL (Jordan Owens)](https://github.com/jor-dan/SpaceX-GraphQL)
- GraphQL Alternative: [xploration-graphql](https://github.com/Kartikkumargujarati/xploration-graphql)
- GraphQL Alternative: [spacex-graphql-gateway](https://github.com/kevinstd/spacex-graphql-gateway)

## Common Properties

- [Website](https://github.com/r-spacex/SpaceX-API)
- [GitHub Organization](https://github.com/r-spacex)
- [Source Code](https://github.com/r-spacex/SpaceX-API)
- [License (Apache 2.0)](https://github.com/r-spacex/SpaceX-API/blob/master/LICENSE)
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
- [API Style Guide](https://github.com/r-spacex/api-style-guide)
- [Subreddit](https://www.reddit.com/r/spacex/)
- [Plans](plans/spacex-plans-pricing.yml)
- [Rate Limits](rate-limits/spacex-rate-limits.yml)
- [Spectral Rules](rules/spacex-rules.yml)
- [Vocabulary](vocabulary/spacex-vocabulary.yml)
- [JSON-LD Context](json-ld/spacex-context.jsonld)
- MCP Server (community): [fercervantesx/lnl-spacex-mcp-server](https://github.com/fercervantesx/lnl-spacex-mcp-server)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [SpaceX REST API](openapi/spacex-rest-api-openapi.yml) — 43 operations across 14 resource collections (capsules, company, cores, crew, dragons, history, landpads, launches v5, launchpads, payloads, roadster, rockets, ships, starlink)

### JSON Schema

- [Capsule](json-schema/spacex-capsule-schema.json)
- [Company](json-schema/spacex-company-schema.json)
- [Core](json-schema/spacex-core-schema.json)
- [Crew Member](json-schema/spacex-crew-schema.json)
- [Dragon](json-schema/spacex-dragon-schema.json)
- [History Event](json-schema/spacex-history-schema.json)
- [Landpad](json-schema/spacex-landpad-schema.json)
- [Launch](json-schema/spacex-launch-schema.json)
- [Launchpad](json-schema/spacex-launchpad-schema.json)
- [Payload](json-schema/spacex-payload-schema.json)
- [Roadster](json-schema/spacex-roadster-schema.json)
- [Rocket](json-schema/spacex-rocket-schema.json)
- [Ship](json-schema/spacex-ship-schema.json)
- [Starlink Satellite](json-schema/spacex-starlink-schema.json)

### JSON Structure

- [Capsule](json-structure/spacex-capsule-structure.json)
- [Company](json-structure/spacex-company-structure.json)
- [Core](json-structure/spacex-core-structure.json)
- [Crew Member](json-structure/spacex-crew-structure.json)
- [Dragon](json-structure/spacex-dragon-structure.json)
- [History Event](json-structure/spacex-history-structure.json)
- [Landpad](json-structure/spacex-landpad-structure.json)
- [Launch](json-structure/spacex-launch-structure.json)
- [Launchpad](json-structure/spacex-launchpad-structure.json)
- [Payload](json-structure/spacex-payload-structure.json)
- [Roadster](json-structure/spacex-roadster-structure.json)
- [Rocket](json-structure/spacex-rocket-structure.json)
- [Ship](json-structure/spacex-ship-structure.json)
- [Starlink Satellite](json-structure/spacex-starlink-structure.json)

### JSON-LD

- [SpaceX Context](json-ld/spacex-context.jsonld) — schema.org mapping for Launch, Rocket, Capsule, Core, CrewMember, Dragon, Payload, Ship, Launchpad, Landpad, StarlinkSat, Roadster, Company, HistoryEvent

### Examples

Live request/response examples captured against `https://api.spacexdata.com`:

- [Get Capsule](examples/spacex-getcapsule-example.json)
- [Get Company](examples/spacex-getcompany-example.json)
- [Get Core](examples/spacex-getcore-example.json)
- [Get Crew Member](examples/spacex-getcrewmember-example.json)
- [Get Dragon](examples/spacex-getdragon-example.json)
- [Get History Event](examples/spacex-gethistoryevent-example.json)
- [Get Landpad](examples/spacex-getlandpad-example.json)
- [Get Latest Launch](examples/spacex-getlatestlaunch-example.json)
- [Get Launchpad](examples/spacex-getlaunchpad-example.json)
- [Get Next Launch](examples/spacex-getnextlaunch-example.json)
- [Get Payload](examples/spacex-getpayload-example.json)
- [Get Roadster](examples/spacex-getroadster-example.json)
- [Get Rocket](examples/spacex-getrocket-example.json)
- [Get Ship](examples/spacex-getship-example.json)
- [Get Starlink Satellite](examples/spacex-getstarlinksatellite-example.json)

## Capabilities

Naftiko capabilities organized as workflow-oriented bundles over the SpaceX REST surface.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Launches](capabilities/spacex-launches.yaml) | SpaceX REST API | 5 | Mission analyst / launch tracker |
| [Rockets](capabilities/spacex-rockets.yaml) | SpaceX REST API | 2 | Vehicle researcher |
| [Crew & Dragon](capabilities/spacex-crew.yaml) | SpaceX REST API | 4 | Human-spaceflight analyst |
| [Starlink](capabilities/spacex-starlink.yaml) | SpaceX REST API | 3 | Satellite-orbit tracker |
| [Fleet & Pads](capabilities/spacex-fleet.yaml) | SpaceX REST API | 4 | Infrastructure researcher |

## Vocabulary

- [SpaceX Vocabulary](vocabulary/spacex-vocabulary.yml) — 18-term tag-derived vocabulary for the community SpaceX REST surface

## Rules

- [SpaceX Spectral Rules](rules/spacex-rules.yml) — 27 rules across info, paths, operations, parameters, requests, responses, schemas, security, methods, and general quality enforcing community SpaceX-API conventions

## Plans

- [SpaceX Plans](plans/spacex-plans-pricing.yml) — Two plans: Community Free (hosted, no SLA, free, unauthenticated reads) and Self-Hosted (Apache 2.0, Docker image, BYO MongoDB + Redis)

## Rate Limits

- [SpaceX Rate Limits](rate-limits/spacex-rate-limits.yml) — Per-IP 50 req/s on the hosted endpoint plus Redis cache TTLs (launches 20s; most resources 5 min; dragons/rockets 24 h)

## Known SDKs

The r-spacex community catalogs third-party clients in [docs/clients.md](https://github.com/r-spacex/SpaceX-API/blob/master/docs/clients.md). Notable v4-compatible clients:

| Language | Project | Repo |
|----------|---------|------|
| .NET | Oddity | [Tearth/Oddity](https://github.com/Tearth/Oddity) |
| Python | SpaceXPy | [SaidBySolo/SpaceXPy](https://github.com/SaidBySolo/SpaceXPy) |
| Swift | KSBSpacexKit | [SaiBalaji22/KSBSpacexKit](https://github.com/SaiBalaji22/KSBSpacexKit) |
| C++ | Marsy | [AzuxDario/Marsy](https://github.com/AzuxDario/Marsy) |
| Node.js | spacex-api.js | [AkiaCode/spacex-api.js](https://github.com/AkiaCode/spacex-api.js) |
| Dart | spacex_api | [ahsanz024/spacex_api](https://github.com/ahsanz024/spacex_api) |
| Ruby | spacex-api-ruby | [victorperez/spacex-api-ruby](https://github.com/victorperez/spacex-api-ruby) |
| Java | spacex-api | [artfultom/spacex-api](https://github.com/artfultom/spacex-api) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
