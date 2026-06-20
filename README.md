# Raycast (raycast)

Raycast is a macOS (and Windows, in beta) productivity launcher that ships an extensions platform, built-in AI, and a Store. Its developer surface is the @raycast/api TypeScript/Node SDK used to build extensions with React - a client-side library, not a public HTTP REST API. Capabilities such as AI, Storage, OAuth, and Preferences are exposed as SDK modules invoked from inside extensions rather than as standalone web endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/raycast/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/raycast/refs/heads/main/apis.yml)

## Tags

- Productivity
- Launcher
- Extensions
- SDK
- AI
- macOS

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Raycast Extension API (SDK)

The primary developer interface - the @raycast/api npm package. A strongly typed TypeScript/Node SDK (installed via `npm i @raycast/api`) providing React UI components (List, Detail, Form, Grid, Action) plus modules for Storage, Cache, Clipboard, Preferences, OAuth, Environment, Keyboard, Window Management, Menu Bar Commands, and Browser Extension. This is a client-side library invoked from within extensions, not an HTTP REST API.

- **Human URL:** [https://developers.raycast.com/api-reference](https://developers.raycast.com/api-reference)

#### Tags

- SDK
- TypeScript
- React
- Extensions
- Library

#### Properties

- [Documentation](https://developers.raycast.com/)
- [API Reference](https://developers.raycast.com/api-reference)
- [GitHub](https://github.com/raycast/extensions)
- [OpenAPI](openapi/raycast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/raycast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/raycast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Raycast AI API

AI access surfaced through the SDK via `AI.ask(prompt)` - no API keys or HTTP endpoint required. Routes prompts across 80+ models from OpenAI, Anthropic, Google, Mistral, Groq, Perplexity, and xAI behind the Raycast Pro / Advanced AI subscription. Available only inside extensions through the @raycast/api library, not as a standalone REST API.

- **Human URL:** [https://developers.raycast.com/api-reference/ai](https://developers.raycast.com/api-reference/ai)

#### Tags

- AI
- LLM
- SDK

#### Properties

- [Documentation](https://developers.raycast.com/api-reference/ai)
- [GitHub](https://github.com/raycast/extensions)
- [OpenAPI](openapi/raycast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/raycast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/raycast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Raycast Store

The Raycast Store distributes community and partner extensions. Publishing is done via the `ray` CLI and a pull request to the github.com/raycast/extensions monorepo; there is no documented public REST API for programmatic store search or submission. The store is a curated marketplace fed by the open-source extensions repository.

- **Human URL:** [https://www.raycast.com/store](https://www.raycast.com/store)

#### Tags

- Store
- Marketplace
- Extensions
- Publishing

#### Properties

- [Documentation](https://developers.raycast.com/basics/prepare-an-extension-for-store)
- [Website](https://www.raycast.com/store)
- [GitHub](https://github.com/raycast/extensions)

## Common Properties

- [GitHub Organization](https://github.com/raycast)
- [LinkedIn](https://www.linkedin.com/company/raycast)
- [Website](https://www.raycast.com)
- [Documentation](https://developers.raycast.com/)
- [Plans](plans/raycast-plans-pricing.yml)
- [Rate Limits](rate-limits/raycast-rate-limits.yml)
- [Fin Ops](finops/raycast-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
