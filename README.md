# Zestful (zestful)
Zestful provides a machine-learning-powered ingredient parser API that turns plain recipe ingredient strings into structured JSON data. The API extracts quantity, unit, product name, preparation notes, and USDA FoodData Central database matches from free-form recipe text. Designed for recipe app developers building searchable recipes, shopping lists, and ingredient databases.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Food, Ingredients, Parsers, Recipes, USDA

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-05-03

## APIs

### Zestful Ingredient Parser API
Machine-learning ingredient parser that converts plain recipe text into structured JSON data with USDA FoodData Central matches. Accepts up to 100 ingredients per request.

- **Human URL:** [https://zestfuldata.com/docs/](https://zestfuldata.com/docs/)
- **Base URL:** https://zestfuldata.com

**Tags:** Food, Ingredients, Parsers, Recipes, USDA

**Properties:**
- [Documentation](https://zestfuldata.com/docs/)
- [Pricing](https://zestfuldata.com/pricing/)
- [OpenAPI](openapi/zestful-openapi.yml)
- [JSON Schema - Ingredient](json-schema/zestful-ingredient-schema.json)
- [JSON Schema - Parse Response](json-schema/zestful-parse-response-schema.json)
- [JSON-LD Context](json-ld/zestful-context.jsonld)
- [Spectral Rules](rules/zestful-rules.yml)
- [Naftiko Capabilities](capabilities/recipe-data-enrichment.yaml)

## Artifacts

| Type | File |
|---|---|
| OpenAPI Spec | [openapi/zestful-openapi.yml](openapi/zestful-openapi.yml) |
| JSON Schema | [json-schema/zestful-ingredient-schema.json](json-schema/zestful-ingredient-schema.json) |
| JSON Schema | [json-schema/zestful-parse-response-schema.json](json-schema/zestful-parse-response-schema.json) |
| JSON Structure | [json-structure/zestful-ingredient-structure.json](json-structure/zestful-ingredient-structure.json) |
| JSON-LD Context | [json-ld/zestful-context.jsonld](json-ld/zestful-context.jsonld) |
| Examples | [examples/zestful-parse-ingredients-example.json](examples/zestful-parse-ingredients-example.json) |
| Spectral Rules | [rules/zestful-rules.yml](rules/zestful-rules.yml) |
| Naftiko Capabilities | [capabilities/recipe-data-enrichment.yaml](capabilities/recipe-data-enrichment.yaml) |
| Naftiko Shared | [capabilities/shared/zestful.yaml](capabilities/shared/zestful.yaml) |
| Vocabulary | [vocabulary/zestful-vocabulary.yml](vocabulary/zestful-vocabulary.yml) |

## Common Properties

- [Website](https://zestfuldata.com/)
- [Documentation](https://zestfuldata.com/docs/)
- [Pricing](https://zestfuldata.com/pricing/)
- [RapidAPI](https://rapidapi.com/zestfuldata/api/recipe-and-ingredient-analysis)
- [GitHub - Zestful Client](https://github.com/mtlynch/zestful-client)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
