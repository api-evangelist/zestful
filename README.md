# Zestful (zestful)

Zestful provides a machine-learning-powered ingredient parser API that turns plain recipe ingredient strings into structured JSON data. The API extracts quantity, unit, product name, preparation notes, and USDA FoodData Central database matches from free-form recipe text. Designed for recipe app developers building searchable recipes, shopping lists, and ingredient databases.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Food
- Ingredients
- Parsers
- Recipes
- USDA

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-05-19

## APIs

### Zestful Ingredient Parser API

The Zestful Ingredient Parser API uses machine learning to convert plain recipe ingredient strings into structured JSON data. It parses ingredient names, quantities, units, preparation notes, and matches each ingredient against the USDA FoodData Central database. Accepts up to 100 ingredients per request. Pricing: free tier (30 parses/day), professional ($0.02 per parse), and enterprise (flat fee, private server).

- **Human URL:** [https://zestfuldata.com/docs/](https://zestfuldata.com/docs/)
- **Base URL:** `https://zestfuldata.com`

#### Tags

- Food
- Ingredients
- Parsers
- Recipes
- USDA

#### Properties

- [Documentation](https://zestfuldata.com/docs/)
- [Pricing](https://zestfuldata.com/pricing/)
- [OpenAPI](openapi/zestful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zestful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zestful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/zestful-ingredient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zestful-parse-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zestful-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/zestful-rules.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zestful)
- [Website](https://zestfuldata.com/)
- [Documentation](https://zestfuldata.com/docs/)
- [Pricing](https://zestfuldata.com/pricing/)
- [Integrations](https://rapidapi.com/zestfuldata/api/recipe-and-ingredient-analysis)
- [S D Ks](https://github.com/mtlynch/zestful-client)
- [Vocabulary](vocabulary/zestful-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
