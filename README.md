# Lex Machina

Lex Machina is a LexisNexis-owned legal analytics platform that turns raw court documents and dockets into structured datasets for litigators, corporate legal teams, insurers, judges, and law schools. Founded in 2010 as a Stanford Law School spin-out and acquired by LexisNexis (RELX) in 2015, the platform now covers all 94 federal district courts, the 13 federal courts of appeals, the PTAB, the ITC, bankruptcy courts, and a growing set of state courts — tracking 8,000+ judges, 6,000+ expert witnesses, 146M+ counsel and 149M+ party mentions across 10M+ cases and 45M+ documents.

This repository profiles Lex Machina's public Litigation Analytics API as an API Evangelist catalog entry following the [APIs.json](https://apisjson.org) specification.

## API

| API | Base URL | Docs |
|---|---|---|
| Lex Machina Litigation Analytics API | `https://api.lexmachina.com` | [Developer Portal](https://developer.lexmachina.com/) · [Swagger UI](https://api.lexmachina.com/docs) |

The API is OpenAPI 3.1.0, version `20260324`, with 57 endpoints across 21 tags including Federal District / Appeals / State / Bankruptcy / ITC / PTAB cases, Attorneys, Judges, Law Firms, Parties, Patents, Dockets, Case Query, Analytics, Alerts, Search, and Reference Lists. Authentication is OAuth 2.0 client-credentials with JWT bearer tokens (`POST /oauth2/token`).

## Artifacts

- [`apis.yml`](apis.yml) — APIs.json 0.20 catalog entry
- [`openapi/lex-machina-openapi.yml`](openapi/lex-machina-openapi.yml) — OpenAPI 3.1.0 specification (downloaded from `https://api.lexmachina.com/openapi.json`)

## Official Clients & Tools

- [python-lexmachina-sync-api-client](https://github.com/LexMachinaInc/python-lexmachina-sync-api-client) — Python 3.9+ synchronous client (Apache-2.0)
- [node-lexmachina-api-client](https://github.com/LexMachinaInc/node-lexmachina-api-client) — Node.js client (Apache-2.0)
- [lexmachina-agent](https://github.com/LexMachinaInc/lexmachina-agent) — Agent-to-Agent (A2A) proxy for AI agents (Apache-2.0)
- [api-alerting-example](https://github.com/LexMachinaInc/api-alerting-example) — Reference workflow using the Alerts API

## Practice Areas

Antitrust · Bankruptcy · Commercial · Consumer Protection · Contracts · Copyright · Employment · ERISA · Insurance · Patent · Product Liability · Securities · Tax · Torts · Trademark

## Maintainer

[Kin Lane](https://apievangelist.com) — API Evangelist
