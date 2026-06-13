# Yr

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
