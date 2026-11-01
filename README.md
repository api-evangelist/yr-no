# Yr

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

Yr is a weather service from the Norwegian Meteorological Institute (MET Norway) and the Norwegian Broadcasting Corporation (NRK), providing free, high-quality weather forecasts for locations worldwide via a simple REST interface. The MET Weather API offers a comprehensive suite of products including location-based forecasts, weather alerts, nowcasts, ocean forecasts, aviation weather, sunrise and sun event calculations, radar imagery, and historical meteorological observation data. All data is open under CC BY 4.0 and requires only a User-Agent identification header — no API key or account is needed.

**Areas:** Weather · Forecast · Meteorology · Climate · Norway · Nordic · Open Data · Aviation Weather · Marine Weather · Alerts

## Yr on APIs.io

Everything profiled for Yr is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/yr-no/](https://apis.io/providers/yr-no/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Frost API](https://apis.io/apis/yr-no/frost-api/) — REST API for historical meteorological observation data from weather stations worldwide, maintained by MET Norway. Access time-series temperature,…
- [Air Quality Forecast API](https://apis.io/apis/yr-no/air-quality-forecast-api/) — Forecasts of air quality for locations in Norway, including concentrations of PM2.5, PM10, NO2, and ozone, with daily and hourly granularity.
- [Yr Alerts API](https://apis.io/apis/yr-no/yr-no-alerts-api/) — Weather alert endpoints
- [Yr Data API](https://apis.io/apis/yr-no/yr-no-data-api/) — Forecast data endpoints
- [Yr Metadata API](https://apis.io/apis/yr-no/yr-no-metadata-api/) — Service metadata endpoints

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Yr No Agentic Access](https://apis.io/agentic-access/yr-no/yr-no-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [MET Norway MetAlerts GeoJSON Schema](https://apis.io/schemas/yr-no/yr-no-alert/)
- [MET Norway Forecast Response Schema](https://apis.io/schemas/yr-no/yr-no-forecast/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Yr No Context](https://apis.io/jsonld/yr-no/yr-no-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Yr / MET Norway API Vocabulary](https://apis.io/vocabularies/yr-no/yr-no-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Yr No Compact Forecast Example](https://apis.io/examples/yr-no/yr-no-compact-forecast-example/)
- [Yr No Metalert Example](https://apis.io/examples/yr-no/yr-no-metalert-example/)
- [Yr No Oceanforecast Example](https://apis.io/examples/yr-no/yr-no-oceanforecast-example/)
- [Yr No Sunrise Example](https://apis.io/examples/yr-no/yr-no-sunrise-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [Locationforecast alerts API](https://apis.io/collections/yr-no/open-yr-no-alerts-api/)
- [Locationforecast alerts data API](https://apis.io/collections/yr-no/open-yr-no-data-api/)
- [Locationforecast alerts metadata API](https://apis.io/collections/yr-no/open-yr-no-metadata-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Yr — jsonschema rules](https://apis.io/rules/yr-no/yr-no-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Yr No Domain Security](https://apis.io/security/yr-no/yr-no-domain-security/)
- [Yr No Vulnerability Disclosure](https://apis.io/security/yr-no/yr-no-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Yr No Plans Pricing](https://apis.io/plans/yr-no/yr-no-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Yr No Rate Limits](https://apis.io/rate-limits/yr-no/yr-no-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Yr No Finops](https://apis.io/finops/yr-no/yr-no-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.yr.no/en)
- [Documentation](https://developer.yr.no/)
- [Getting started](https://developer.yr.no/doc/GettingStarted/)
- [Pricing](https://developer.yr.no/doc/TermsOfService/)
- [Blog](https://developer.yr.no/)
- [Terms of service](https://developer.yr.no/doc/TermsOfService/)
- [Privacy policy](https://www.met.no/en/About-us/privacy)

## API Evangelist rating

**Kin Score 36.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 53.5 |
| Contract governance | 9.8 |
| Operational transparency | 5.3 |
| Developer ergonomics | 23.8 |
| Access clarity | 36.8 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/yr-no/](https://apis.io/providers/yr-no/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Yr: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/yr-no/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
