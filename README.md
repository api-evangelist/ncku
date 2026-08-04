# National Cheng Kung University (ncku)

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

National Cheng Kung University (NCKU) is a public research university in Tainan, Taiwan, ranked #215 in the QS World University Rankings 2025. This repository catalogs NCKU's public, machine-readable footprint as an [APIs.json](https://apisjson.org) profile. NCKU does not run a single consolidated developer portal; the entries below are platform-standard interfaces (CKAN, Ex Libris Primo/Alma, DSpace) that were confirmed live, not bespoke documented university APIs.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ncku/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ncku-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Library, Taiwan

## APIs

- **NCKU Open Data Platform (CKAN Action API)** — CKAN-powered open data platform exposing the standard CKAN Action API (e.g. `/api/3/action/package_list`). Verified live with valid JSON. Docs: https://docs.ckan.org/en/latest/api/ — Portal: https://data.ncku.edu.tw/
- **NCKU Library Discovery (Ex Libris Primo)** — Library catalog/discovery on Primo backed by Alma. Discovery view: https://ncku.primo.exlibrisgroup.com/discovery/search?vid=886NCKU_INST:NCKU
- **NCKU Institutional Repository (DSpace 7)** — Scholarly repository (NCKUR) on DSpace 7; REST/OAI-PMH typically available but a working base URL was not confirmed. Docs: https://nckur.lib.ncku.edu.tw/

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/ncku-plans-pricing.yml](plans/ncku-plans-pricing.yml)
- Rate Limits: [rate-limits/ncku-rate-limits.yml](rate-limits/ncku-rate-limits.yml)
- FinOps: [finops/ncku-finops.yml](finops/ncku-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://web.ncku.edu.tw/index.php?Lang=en
- Developer Portal (Open Data): https://data.ncku.edu.tw/
- GitHub: https://github.com/ncku-csie
- LinkedIn: https://www.linkedin.com/school/national-cheng-kung-university/

## Notes

- All endpoints were probed on 2026-06-03; see [review.yml](review.yml) for HTTP statuses.
- The CKAN Action API was verified returning valid JSON; Primo and the DSpace repository were verified live.
- A DSpace OAI-PMH/REST base URL did not resolve at probe time and is therefore not asserted as a `baseURL`.
- No NCKU-specific API key program or developer documentation was found. No endpoints were fabricated.
- `github.com/ncku-csie` (Dept. of CSIE) is academic, not a central API org; `gdsc-ncku` returned 404.

## Maintainers

- Kin Lane — kin@apievangelist.com
