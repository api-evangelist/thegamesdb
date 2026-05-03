# TheGamesDB (thegamesdb)
An open, online database for video game fans providing game information, artwork, and metadata via API.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Database
- Gaming
- Video Games
- Metadata
- Artwork

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-03

## APIs

### TheGamesDB API
An open, online database for video game fans providing game information, artwork, and metadata via API. Search and retrieve game details, platform information, game artwork (boxart, screenshots, fanart), genres, developers, and publishers. Requires an API key.

**Human URL:** [https://api.thegamesdb.net/](https://api.thegamesdb.net/)
**Base URL:** https://api.thegamesdb.net

#### Tags

- Database
- Gaming
- Video Games
- Metadata
- Artwork

#### Properties

- [Documentation](https://api.thegamesdb.net/)
- [OpenAPI](openapi/thegamesdb-openapi.yml)
- [Sign Up](https://api.thegamesdb.net/key.php)
- [JSON Schema - Game Schema](json-schema/thegamesdb-game-schema.json)
- [JSON Structure - Game Structure](json-structure/thegamesdb-game-structure.json)
- [JSON-LD Context](json-ld/thegamesdb-context.jsonld)

## Common Properties

- [Website](https://thegamesdb.net/)
- [Documentation](https://api.thegamesdb.net/)
- [Sign Up](https://api.thegamesdb.net/key.php)
- [GitHub Organization](https://github.com/TheGamesDB)
- [Spectral Rules](rules/thegamesdb-spectral-rules.yml)
- [Vocabulary](vocabulary/thegamesdb-vocabulary.yml)
- [Naftiko Capability - Video Game Discovery](capabilities/video-game-discovery.yaml)

## Authentication

- **API Key Query Parameter:** API key passed as 'apikey' query parameter on all requests

## Rate Limits

- **Monthly Allowance:** 1000 queries per month (20 calls per query = 20,000 total calls)

## Features

- **Game Search:** Search games by name with optional platform filtering
- **Game Details:** Retrieve complete game metadata by ID including overview, ratings, and system requirements
- **Platform Catalog:** Full catalog of all gaming platforms with hardware specifications and images
- **Game Artwork:** Boxart, screenshots, fanart, banners, and clearlogos for games and platforms
- **Game Updates:** Retrieve games updated since a given timestamp for database synchronization
- **Reference Data:** Complete lists of genres, developers, and publishers
- **Batch Requests:** Request multiple game or platform IDs in a single API call

## Use Cases

- **Gaming Applications:** Build game databases, libraries, and collection managers
- **Media Centers:** Power game scrapers for Emulation Station, Kodi, and similar media centers
- **Game Collections:** Manage personal or commercial video game collection databases
- **AI Game Assistant:** Power AI agents that answer questions about video games

## Integrations

- **EmulationStation:** Popular retro gaming frontend using TheGamesDB for scraping
- **Skraper:** Game scraper tools using the API for artwork and metadata

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
