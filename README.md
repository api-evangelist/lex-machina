# Lex Machina (lex-machina)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
