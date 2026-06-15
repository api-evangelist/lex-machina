# Lex Machina (lex-machina)

Lex Machina is a legal analytics platform owned by LexisNexis that transforms raw court documents and dockets into structured datasets so litigators, corporate legal teams, insurers, and judges can make data-driven decisions about cases, courts, judges, lawyers, parties, and damages. The platform covers all 94 federal district courts, the 13 federal courts of appeals, the PTAB, the ITC, bankruptcy courts, and a growing list of state courts (with 18M+ additional state cases for party analytics), and tracks 8,000+ judges, 6,000+ expert witnesses, 146M+ counsel mentions, and 149M+ party mentions across 10M+ cases and 45M+ documents. Lex Machina exposes its Legal Analytics through a public Litigation Analytics API (OAuth 2.0, JWT bearer tokens) at api.lexmachina.com with synchronous Python and Node.js client libraries plus an A2A (Agent-to-Agent) agent for AI/agent integrations. Practice area coverage includes Antitrust, Bankruptcy, Commercial, Consumer Protection, Contracts, Copyright, Employment, ERISA, Insurance, Patent, Product Liability, Securities, Tax, Torts, and Trademark litigation. Lex Machina was founded in 2010 as a Stanford University Law School spin-out and was acquired by LexisNexis (RELX) in 2015.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lex-machina/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lex-machina/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Legal
- Legal Analytics
- Legal Technology
- Litigation
- Litigation Analytics
- Court Data
- Dockets
- Judges
- Law Firms
- Attorneys
- Patents
- PTAB
- ITC
- Bankruptcy
- Appeals
- State Courts
- Federal Courts
- LexisNexis
- Data
- Analytics

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Lex Machina Litigation Analytics API

The Lex Machina Litigation Analytics API exposes the company's full legal analytics dataset over REST. It supports OAuth 2.0 client credentials (JWT bearer tokens) and provides 57 endpoints across Federal District, Federal Appeals, State, Bankruptcy, ITC, and PTAB case data; Attorneys, Judges, Magistrates, Law Firms, Parties, and Patents as first-class entities; Docket entries; substring search across attorneys, judges, law firms, and parties; saved Alerts and Alert run results; Case Query (POST) with rich filtering by participants, dates, events, resolutions, findings, remedies, and damages; and District Case Analytics from either a query or a saved alert. Reference list endpoints cover case resolutions, case tags, case types, courts, damages categories, events, and judgment sources, so clients can discover the controlled vocabularies used across the platform. Base URL is https://api.lexmachina.com; the current API version is 20260324.

- **Human URL:** [https://developer.lexmachina.com/](https://developer.lexmachina.com/)
- **Base URL:** `https://api.lexmachina.com`

#### Tags

- Legal Analytics
- Litigation
- Court Data
- Dockets
- Judges
- Law Firms
- Attorneys
- Patents
- PTAB
- ITC
- Bankruptcy
- Appeals
- State Cases
- Alerts

#### Properties

- [Documentation](https://developer.lexmachina.com/)
- [Documentation](https://developer.lexmachina.com/gettingStarted)
- [Documentation](https://api.lexmachina.com/docs)
- [OpenAPI](openapi/lex-machina-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lex-machina.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lex-machina.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.lexmachina.com/gettingStarted)
- [SDK](https://github.com/LexMachinaInc/python-lexmachina-sync-api-client)
- [SDK](https://github.com/LexMachinaInc/node-lexmachina-api-client)
- [Agent](https://github.com/LexMachinaInc/lexmachina-agent)
- [Code Sample](https://github.com/LexMachinaInc/api-alerting-example)

## Common Properties

- [Website](https://www.lexisnexis.com/en-us/products/lex-machina.page)
- [Portal](https://developer.lexmachina.com/)
- [Sign In](https://law.lexmachina.com/login)
- [Documentation](https://developer.lexmachina.com/gettingStarted)
- [Documentation](https://developer.lexmachina.com/support)
- [Documentation](https://api.lexmachina.com/docs)
- [Blog](https://www.lexisnexis.com/community/insights/legal/lex-machina)
- [Press Room](https://www.lexisnexis.com/community/amp-pressroom/)
- [Parent Company](https://www.lexisnexis.com/)
- [GitHub Organization](https://github.com/LexMachinaInc)
- [LinkedIn](https://www.linkedin.com/company/lex-machina/)
- [Twitter](https://twitter.com/LexMachina)
- [YouTube](https://www.youtube.com/@LexMachinaInc)
- [Support](https://developer.lexmachina.com/support)
- [Contact Email](mailto:support@lexmachina.com)
- [Terms of Service](https://www.lexisnexis.com/en-us/terms/general/default.page)
- [Privacy Policy](https://www.lexisnexis.com/en-us/terms/privacy-policy/default.page)
- [Trust Center](https://www.lexisnexis.com/en-us/about-us/social-responsibility/data-privacy.page)
- [SDK](https://github.com/LexMachinaInc/python-lexmachina-sync-api-client)
- [SDK](https://github.com/LexMachinaInc/node-lexmachina-api-client)
- [Agent](https://github.com/LexMachinaInc/lexmachina-agent)
- [Code Sample](https://github.com/LexMachinaInc/api-alerting-example)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
