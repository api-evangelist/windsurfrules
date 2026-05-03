# Windsurf

Windsurf (formerly Codeium) is an AI-native code editor featuring Cascade, an autonomous AI agent that can plan multi-step code changes, execute terminal commands, read linter output, and modify files across entire projects. The .windsurfrules file format provides project-specific configuration for the Cascade AI assistant, defining coding conventions, standards, and behavioral instructions. Windsurf offers an Enterprise API for querying code completion analytics, Cascade AI usage, billing configuration, and team management.

**URL:** [https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Agents
- AI Copilot
- Coding Standards
- Developer Workflow
- IDE
- Windsurf

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Windsurf Enterprise API
The Windsurf Enterprise API provides analytics, usage data, billing configuration, and team management for enterprise customers. Authentication uses service keys in the request body. Available at `https://server.codeium.com/api/v1`.

**Human URL:** [https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction](https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction)

| Type | URL |
|------|-----|
| Documentation | https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction |
| OpenAPI | [windsurf-enterprise-openapi.yml](openapi/windsurf-enterprise-openapi.yml) |
| Spectral Rules | [windsurf-enterprise-rules.yml](rules/windsurf-enterprise-rules.yml) |

## Common Properties

| Type | URL |
|------|-----|
| Website | https://windsurf.com |
| Documentation | https://docs.windsurf.com |
| Changelog | https://windsurf.com/changelog |
| Blog | https://windsurf.com/blog |
| Pricing | https://windsurf.com/pricing |
| GitHub Org | https://github.com/Exafunction |

## Artifacts

### OpenAPI Specification
- [windsurf-enterprise-openapi.yml](openapi/windsurf-enterprise-openapi.yml) — 6 endpoints for analytics and billing

### Spectral Rules
- [windsurf-enterprise-rules.yml](rules/windsurf-enterprise-rules.yml)

### Naftiko Capabilities

#### Shared Definitions
- [capabilities/shared/windsurf-enterprise.yaml](capabilities/shared/windsurf-enterprise.yaml)

#### Workflow Capabilities
- [capabilities/analytics-and-billing.yaml](capabilities/analytics-and-billing.yaml) — Analytics + Billing (6 tools)

### JSON Schema
- [windsurf-analytics-request-schema.json](json-schema/windsurf-analytics-request-schema.json)

### JSON-LD Context
- [windsurfrules-context.jsonld](json-ld/windsurfrules-context.jsonld)

### Examples
- [windsurf-query-analytics-example.json](examples/windsurf-query-analytics-example.json)

### Vocabulary
- [windsurfrules-vocabulary.yml](vocabulary/windsurfrules-vocabulary.yml)

## Maintainers

**Kin Lane** — kin@apievangelist.com
