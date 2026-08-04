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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Yr is a weather service from the Norwegian Meteorological Institute (MET Norway) and the Norwegian Broadcasting Corporation (NRK), providing free, high-quality weather forecasts for locations worldwide via a simple REST interface. The MET Weather API offers a comprehensive suite of products including location-based forecasts, weather alerts, nowcasts, ocean forecasts, aviation weather, sunrise and sun event calculations, radar imagery, and historical meteorological observation data. All data is open under CC BY 4.0 and requires only a User-Agent identification header — no API key or account is needed.

**Website:** https://www.yr.no/en  
**Developer Portal:** https://developer.yr.no/  
**API Base URL:** https://api.met.no/  
**Terms of Service:** https://developer.yr.no/doc/TermsOfService/  
**License:** CC BY 4.0  
**GitHub (Yr):** https://github.com/YR  
**GitHub (MET Norway):** https://github.com/metno  

## APIs

| API | Description |
|-----|-------------|
| [Locationforecast 2.0](https://api.met.no/weatherapi/locationforecast/2.0/documentation) | 9-day weather forecasts for any location on Earth |
| [MetAlerts 2.0](https://api.met.no/weatherapi/metalerts/2.0/documentation) | Weather warnings and alerts from MET Norway |
| [Nowcast 2.0](https://api.met.no/weatherapi/nowcast/2.0/documentation) | Immediate short-range forecasts for the Nordic area |
| [Sunrise 3.0](https://api.met.no/weatherapi/sunrise/3.0/documentation) | Sun and moon event calculations for any location |
| [Frost 0.9](https://frost.met.no/howto.html) | Historical meteorological observation data |
| [Oceanforecast 2.0](https://api.met.no/weatherapi/oceanforecast/2.0/documentation) | Ocean forecasts for Northwestern European waters |
| [Radar 2.0](https://api.met.no/weatherapi/radar/2.0/documentation) | Radar composite images for Nordic regions |
| [Air Quality Forecast 0.1](https://api.met.no/weatherapi/airqualityforecast/0.1/documentation) | Air quality forecasts for Norway |

## Authentication

No API key or account registration is required. All requests must include a descriptive `User-Agent` header identifying your application and providing a contact email or URL:

```
User-Agent: myapp.example.com support@example.com
```

## Rate Limits

- Maximum 20 requests per second per application (aggregate across all clients)
- MetAlerts polling: no more than once per 10 minutes per client
- Coordinates must be truncated to 4 decimal places maximum
- Proper HTTP caching (Expires / If-Modified-Since) is required

## Pricing

Free. No charges, no tiers, no billing. Funded by the Norwegian government.

---

This repository is an [APIs.json](https://apisjson.org/) index profile maintained by [API Evangelist](https://apievangelist.com/).
