# National Cheng Kung University (ncku)

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
