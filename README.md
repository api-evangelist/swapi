# SWAPI - Star Wars API (swapi)

SWAPI (Star Wars API) is a free, open Star Wars REST API exposing canonical Star Wars data — films, people, planets, species, starships, and vehicles. Originally built by Paul Hallett (@phalt) at swapi.co, it is now maintained as community mirrors at swapi.dev (Python/Django, @juriy) and www.swapi.tech (Node/MongoDB, @semperry). SWAPI is one of the most widely cited "teaching APIs" in the developer ecosystem.

**APIs.json:** [https://swapi.dev/](https://swapi.dev/)

## Tags

- Star Wars
- Open Source
- Teaching API
- Public API
- REST
- GraphQL
- Entertainment
- Datasets

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### SWAPI REST API (swapi.dev)

The primary live REST mirror of SWAPI, maintained by @juriy at swapi.dev. Preserves the canonical SWAPI response shape (count / next / previous / results paginators and flat resource schemas). Six top-level resources: films, people, planets, species, starships, vehicles. Read-only, no authentication required.

- **Human URL:** [https://swapi.dev/](https://swapi.dev/)
- **Base URL:** `https://swapi.dev/api`

#### Tags

- REST
- Star Wars
- Open Source

#### Properties

- [Documentation](https://swapi.dev/documentation)
- [OpenAPI](openapi/swapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/swapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Source Code](https://github.com/Juriy/swapi)

### SWAPI REST API (swapi.tech)

The Node/MongoDB community rebuild of SWAPI, maintained by @semperry at swapi.tech. Wraps the canonical SWAPI payloads inside `result.properties` envelopes and adds Discord/Reddit community surfaces. Exposes the same six top-level resources (films, people, planets, species, starships, vehicles).

- **Human URL:** [https://www.swapi.tech/](https://www.swapi.tech/)
- **Base URL:** `https://www.swapi.tech/api`

#### Tags

- REST
- Star Wars
- Open Source

#### Properties

- [Documentation](https://www.swapi.tech/)
- [Source Code](https://github.com/semperry/swapi)
- [Postman Collection](collections/swapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://swapi.dev/)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [GitHub Organization](https://github.com/Juriy/swapi)
- [License](https://github.com/Juriy/swapi/blob/master/LICENSE)
- [Tools](https://github.com/johnpapa/mcp-starwars)
- [Tools](https://github.com/olaekdahl/swapi-mcp-server)
- [Tools](https://github.com/glaucia86/swapi-mcp-server-app)
- [Tools](https://github.com/Qwizi/swapi-mcp)
- [SDK](https://github.com/Oleur/SWAPI-Android-SDK)
- [SDK](https://github.com/bratwursted/swapi-swift)
- [SDK](https://github.com/LionyxML/r-swapi-client)
- [Code Examples](https://github.com/vininjr/starwars)
- [Code Examples](https://github.com/kranfix/flutter_graphql_swapi)
- [OpenAPI](https://github.com/kamilkodzi/oas-swapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Naftiko Vocabulary](vocabulary/swapi-vocabulary.yaml)
- [Json Ld Context](json-ld/swapi-context.jsonld)
- [Spectral Ruleset](rules/swapi-spectral-rules.yml)
- [A P I Commons Plans](plans/swapi-plans-pricing.yml)
- [A P I Commons Rate Limits](rate-limits/swapi-rate-limits.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
