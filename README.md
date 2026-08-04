# Carbon Intensity API

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

The Carbon Intensity API is the official carbon intensity forecasting service for Great Britain, developed by the National Energy System Operator (NESO) in partnership with EDF, the University of Oxford, and WWF. It provides real-time, forecast, and historical carbon intensity data alongside generation mix information for GB electricity generation.

- **API Base URL:** https://api.carbonintensity.org.uk
- **Documentation:** https://carbon-intensity.github.io/api-definitions/
- **Website:** https://carbonintensity.org.uk/
- **GitHub:** https://github.com/carbon-intensity
- **License:** CC BY 4.0
- **Authentication:** None required

## Key Capabilities

- Real-time national carbon intensity (current 30-minute settlement period)
- 96+ hour forward forecasts for carbon intensity and generation mix
- Historical data queries (up to 14-day ranges for intensity, 30-day for statistics)
- 14 regional datasets aligned to DNO boundaries across Great Britain
- England, Scotland, and Wales country-level endpoints
- Postcode-level carbon intensity queries
- Generation mix by fuel type (gas, coal, nuclear, wind, solar, hydro, biomass, imports, other)

## Pricing

The API is provided free of charge with no authentication or registration required. NESO applies rate limiting at its discretion and may block high-volume callers per its Terms of Use.

## Profile

This repository contains an APIs.json 0.19 provider profile for the Carbon Intensity API, maintained by [API Evangelist](https://apievangelist.com).
