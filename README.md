# SWAPI - Star Wars API (swapi)

SWAPI (Star Wars API) is a free, open Star Wars REST API exposing canonical Star Wars data — films, people, planets, species, starships, and vehicles. Originally built by Paul Hallett (@phalt) at swapi.co, it is now maintained as community mirrors at swapi.dev (Python/Django, @juriy) and www.swapi.tech (Node/MongoDB, @semperry). SWAPI is one of the most widely cited "teaching APIs" in the developer ecosystem.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/swapi/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

 - Star Wars, Open Source, Teaching API, Public API, REST, GraphQL, Entertainment, Datasets

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## Type

- **x-type:** opensource
- **x-tier:** 2 (enriched-during-pipeline-run)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Video

## APIs (2)

### SWAPI REST API (swapi.dev)

The primary live REST mirror of SWAPI, maintained by @juriy at swapi.dev. Preserves the canonical SWAPI response shape (count / next / previous / results paginators and flat resource schemas). Six top-level resources: films, people, planets, species, starships, vehicles. Read-only, no authentication required.

**Human URL:** [https://swapi.dev/](https://swapi.dev/)

**Base URL:** `https://swapi.dev/api`

**Tags:** REST, Star Wars, Open Source

**Properties:**
- [Documentation](https://swapi.dev/documentation)
- [OpenAPI](openapi/swapi-openapi.yml)
- [SourceCode](https://github.com/Juriy/swapi)
- [Naftiko Capability](capabilities/swapi-films.yaml)
- [Naftiko Capability](capabilities/swapi-people.yaml)
- [Naftiko Capability](capabilities/swapi-planets.yaml)
- [Naftiko Capability](capabilities/swapi-species.yaml)
- [Naftiko Capability](capabilities/swapi-starships.yaml)
- [Naftiko Capability](capabilities/swapi-vehicles.yaml)

### SWAPI REST API (swapi.tech)

The Node/MongoDB community rebuild of SWAPI, maintained by @semperry at swapi.tech. Wraps the canonical SWAPI payloads inside `result.properties` envelopes and adds Discord/Reddit community surfaces. Exposes the same six top-level resources (films, people, planets, species, starships, vehicles).

**Human URL:** [https://www.swapi.tech/](https://www.swapi.tech/)

**Base URL:** `https://www.swapi.tech/api`

**Tags:** REST, Star Wars, Open Source

**Properties:**
- [Documentation](https://www.swapi.tech/)
- [SourceCode](https://github.com/semperry/swapi)

## Common Properties

- [Website](https://swapi.dev/)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [GitHubOrganization](https://github.com/Juriy/swapi)
- [License](https://github.com/Juriy/swapi/blob/master/LICENSE)
- [MCP Server (johnpapa)](https://github.com/johnpapa/mcp-starwars)
- [MCP Server (olaekdahl)](https://github.com/olaekdahl/swapi-mcp-server)
- [MCP Server (glaucia86)](https://github.com/glaucia86/swapi-mcp-server-app)
- [MCP Server (Qwizi)](https://github.com/Qwizi/swapi-mcp)
- [Android SDK (Oleur)](https://github.com/Oleur/SWAPI-Android-SDK)
- [Swift SDK (bratwursted)](https://github.com/bratwursted/swapi-swift)
- [R Client (LionyxML)](https://github.com/LionyxML/r-swapi-client)
- [Java + Spring Sample](https://github.com/vininjr/starwars)
- [Flutter + GraphQL Sample](https://github.com/kranfix/flutter_graphql_swapi)
- [Community OpenAPI (kamilkodzi)](https://github.com/kamilkodzi/oas-swapi)
- [NaftikoVocabulary](vocabulary/swapi-vocabulary.yaml)
- [JsonLdContext](json-ld/swapi-context.jsonld)
- [SpectralRuleset](rules/swapi-spectral-rules.yml)
- [APICommonsPlans](plans/swapi-plans-pricing.yml)
- [APICommonsRateLimits](rate-limits/swapi-rate-limits.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [SWAPI OpenAPI](openapi/swapi-openapi.yml) — 12 operations across 6 resources (films, people, planets, species, starships, vehicles).

### JSON Schema

- [Film](json-schema/swapi-film-schema.json)
- [Person](json-schema/swapi-person-schema.json)
- [Planet](json-schema/swapi-planet-schema.json)
- [Species](json-schema/swapi-species-schema.json)
- [Starship](json-schema/swapi-starship-schema.json)
- [Vehicle](json-schema/swapi-vehicle-schema.json)

### JSON Structure

- [Film](json-structure/swapi-film-structure.json)
- [Person](json-structure/swapi-person-structure.json)
- [Planet](json-structure/swapi-planet-structure.json)
- [Species](json-structure/swapi-species-structure.json)
- [Starship](json-structure/swapi-starship-structure.json)
- [Vehicle](json-structure/swapi-vehicle-structure.json)

### JSON-LD

- [SWAPI JSON-LD Context](json-ld/swapi-context.jsonld) — Maps SWAPI's snake_case wire format to schema.org and a dedicated `swapi:` namespace.

### Examples

- [listFilms](examples/swapi-listfilms-example.json)
- [getFilm](examples/swapi-getfilm-example.json)
- [listPeople](examples/swapi-listpeople-example.json)
- [getPerson](examples/swapi-getperson-example.json)
- [getPlanet](examples/swapi-getplanet-example.json)
- [getSpecies](examples/swapi-getspecies-example.json)
- [getStarship](examples/swapi-getstarship-example.json)
- [getVehicle](examples/swapi-getvehicle-example.json)

## Capabilities

Naftiko capabilities for SWAPI — one self-contained file per resource tag. Every file declares both a REST exposer (Spectral-compliant `/v1/...` surface) and an MCP exposer (verb-noun tools) routed inline through its own consumes block.

### SWAPI REST API (swapi.dev)

- [SWAPI — Films](capabilities/swapi-films.yaml) — 2 operations (listFilms, getFilm)
- [SWAPI — People](capabilities/swapi-people.yaml) — 2 operations (listPeople, getPerson)
- [SWAPI — Planets](capabilities/swapi-planets.yaml) — 2 operations (listPlanets, getPlanet)
- [SWAPI — Species](capabilities/swapi-species.yaml) — 2 operations (listSpecies, getSpecies)
- [SWAPI — Starships](capabilities/swapi-starships.yaml) — 2 operations (listStarships, getStarship)
- [SWAPI — Vehicles](capabilities/swapi-vehicles.yaml) — 2 operations (listVehicles, getVehicle)

## Vocabulary

- [SWAPI Vocabulary](vocabulary/swapi-vocabulary.yaml) — Controlled vocabulary covering 6 domains, 6 entities, and the in-universe terminology (BBY/ABY, MGLT, hyperdrive rating, parsec, starship/vehicle classes).

## Rules

- [SWAPI Spectral Ruleset](rules/swapi-spectral-rules.yml) — 30+ rules across 11 categories enforcing SWAPI's lowercase paths, snake_case schema properties, camelCase operationIds, plural resource nouns, and canonical envelope fields (created/edited/url).

## Plans

- [SWAPI Plans & Pricing](plans/swapi-plans-pricing.yml) — Single free tier, donation-funded, no usage cost.

## Rate Limits

- [SWAPI Rate Limits](rate-limits/swapi-rate-limits.yml) — No documented hard limits. Polite-use convention: cache aggressively, honor Retry-After if surfaced.

## MCP Servers

Several community-built MCP servers wrap the SWAPI surface. They are not official, but several are referenced in MCP tutorials:

- [johnpapa/mcp-starwars](https://github.com/johnpapa/mcp-starwars) — Tutorial-grade MCP server demonstrating how to wrap an HTTP API as MCP tools.
- [olaekdahl/swapi-mcp-server](https://github.com/olaekdahl/swapi-mcp-server) — Lightweight MCP server exposing character, planet, and film lookups via HTTP or stdio.
- [glaucia86/swapi-mcp-server-app](https://github.com/glaucia86/swapi-mcp-server-app) — TypeScript study project exploring MCP fundamentals.
- [Qwizi/swapi-mcp](https://github.com/Qwizi/swapi-mcp) — Community MCP server for SWAPI.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
