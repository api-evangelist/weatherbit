# Weatherbit (weatherbit)

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

Weatherbit is a leading provider of weather data and forecasting services. They specialize in delivering accurate and up-to-date weather information to businesses and individuals around the world. Services include real-time current weather, 16-day daily and 240-hour hourly forecasts, historical weather data, severe alerts, air quality monitoring, agricultural weather, energy forecasts, and climate normals. Data is available globally via lat/lon, city name, postal code, and station ID.

**URL:** [https://www.weatherbit.io](https://www.weatherbit.io)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Weather, Forecasting, Historical Data, Air Quality, Alerts, Agricultural Weather

## Timestamps

- **Created:** 2023/11/20
- **Modified:** 2026-05-03

## APIs

### Weatherbit Current Weather API
Returns current weather conditions from Weatherbit's global network of sub-hourly reporting weather stations and atmospheric meso-analyses.

**Human URL:** [https://www.weatherbit.io/api/weather-current](https://www.weatherbit.io/api/weather-current)

#### Tags:

 - Weather, Current Conditions, Observations

#### Properties

- [Documentation](https://www.weatherbit.io/api/weather-current)
- [Weatherbit OpenAPI](openapi/weatherbit-current-weather-openapi-original.yml)

### Weatherbit Severe Weather Alerts API
Returns severe weather alerts issued by local meteorological agencies covering the USA, EU, Canada, and China.

**Human URL:** [https://www.weatherbit.io/api/alerts](https://www.weatherbit.io/api/alerts)

#### Tags:

 - Weather, Alerts, Emergency

#### Properties

- [Documentation](https://www.weatherbit.io/api/alerts)

### Weatherbit Weather Forecast API
Provides accurate weather forecasts using high-resolution global and regional weather models including 16-day daily and 240-hour hourly forecasts.

**Human URL:** [https://www.weatherbit.io/api/weather-forecast-api](https://www.weatherbit.io/api/weather-forecast-api)

#### Tags:

 - Weather, Forecasting, Daily, Hourly

#### Properties

- [Documentation](https://www.weatherbit.io/api/weather-forecast-api)

### Weatherbit Historical Weather API
High-resolution historical weather data backed by over 120,000 weather stations and gridded datasets including daily, hourly, and sub-hourly observations.

**Human URL:** [https://www.weatherbit.io/api/historical-weather-api](https://www.weatherbit.io/api/historical-weather-api)

#### Tags:

 - Weather, Historical, Climate

#### Properties

- [Documentation](https://www.weatherbit.io/api/historical-weather-api)

### Weatherbit Ag-Weather API
Agricultural weather data using GLDAS re-analysis with global coverage at 0.25-degree resolution including evapotranspiration and crop-specific parameters.

**Human URL:** [https://www.weatherbit.io/api/agweather-api](https://www.weatherbit.io/api/agweather-api)

#### Tags:

 - Weather, Agriculture, Evapotranspiration

#### Properties

- [Documentation](https://www.weatherbit.io/api/agweather-api)

### Weatherbit Air Quality API
High-quality air quality data from global and regional models tracking PM2.5, PM10, O3, NO2, SO2, CO, and pollen. Includes current and 72-hour forecast data.

**Human URL:** [https://www.weatherbit.io/api/air-quality-api](https://www.weatherbit.io/api/air-quality-api)

#### Tags:

 - Air Quality, AQI, Environment

#### Properties

- [Documentation](https://www.weatherbit.io/api/air-quality-api)

## Common Properties

- [Plans](https://www.weatherbit.io/pricing)
- [FAQ](https://help.weatherbit.io/faq/)
- [Status Page](https://status.weatherbit.io/)
- [Blog](https://blog.weatherbit.io/)
- [Knowledge Center](https://help.weatherbit.io/)
- [Sign Up](https://www.weatherbit.io/account/create)
- [Login](https://www.weatherbit.io/account/login)
- [Terms of Service](https://www.weatherbit.io/terms)
- [Privacy Policy](https://www.weatherbit.io/privacy)
- [Contact](https://www.weatherbit.io/contact)
- [GitHub Repository](https://github.com/weatherbit/weatherbit-python)
- [Python SDK](https://pypi.org/project/pyweatherbit/)

## Features

| Name | Description |
|------|-------------|
| Current Weather | Live observations updated every 5-30 minutes from global weather station network. |
| 16-Day Daily Forecasts | High-accuracy daily forecasts for up to 16 days ahead using state-of-the-art weather models. |
| 240-Hour Hourly Forecasts | Detailed hourly forecasts for up to 10 days (240 hours) ahead. |
| Severe Weather Alerts | Real-time severe weather alerts from official agencies in the US, EU, Canada, and China. |
| Historical Weather Data | Gap-free historical weather data going back decades using ML and statistical backfilling. |
| Air Quality Monitoring | Current and forecast air quality data tracking PM2.5, PM10, O3, NO2, SO2, CO, and pollen levels. |
| Agricultural Weather | Specialized agricultural weather data including evapotranspiration, soil moisture, and growing degree days. |
| Energy Forecasts | Energy sector weather forecasts including heating and cooling degree days. |
| Climate Normals | 1991-2020 climate normals at 9km resolution for historical comparison. |
| Multiple Lookup Methods | Access data by lat/lon, city name, city ID, station ID, ICAO code, or postal code. |

## Use Cases

| Name | Description |
|------|-------------|
| Mobile Weather Apps | Power consumer weather applications with accurate forecasts and real-time conditions. |
| Agricultural Planning | Optimize crop management with specialized agricultural weather forecasts and historical data. |
| Energy Management | Use degree-day forecasts for energy demand prediction and grid management. |
| Emergency Management | Monitor severe weather alerts for disaster preparedness and emergency response. |
| Insurance and Risk | Access historical and forecast weather data for risk assessment and claims processing. |
| Logistics and Transportation | Optimize routing and operations based on weather forecasts and real-time conditions. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Weatherbit Current Weather OpenAPI](openapi/weatherbit-current-weather-openapi-original.yml)

### JSON Schema

32 JSON Schema files extracted from the OpenAPI specification covering weather observations, forecasts, and air quality entities.

### JSON Structure

32 JSON Structure files (json-structure.org) converted from JSON Schema.

### JSON-LD

- [Weatherbit JSON-LD Context](json-ld/weatherbit-context.jsonld) — 31 type declarations and 122 property mappings

### Examples

32 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Weatherbit API](capabilities/shared/weatherbit-api.yaml) — 9 operations covering current weather, forecasts, history, alerts, air quality, and agricultural weather

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Weather Intelligence](capabilities/weather-intelligence.yaml) | Weatherbit API | 10 | Developer, Business Analyst, Agricultural Planner, Emergency Manager |

## Vocabulary

- [Weatherbit Vocabulary](vocabulary/weatherbit-vocabulary.yml) — Unified taxonomy mapping 11 resources, 3 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Weatherbit Spectral Rules](rules/weatherbit-spectral-rules.yml) — 19 rules across 8 categories enforcing Weatherbit API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
