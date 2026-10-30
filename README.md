# National Cheng Kung University

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

National Cheng Kung University (NCKU, 國立成功大學) is a public research university in Tainan, Taiwan, founded in 1931 and the second-largest comprehensive university in the country. Its programmable footprint is narrow and almost entirely accounted for by one surface: the NCKU Open Data Platform at data.ncku.edu.tw, a CKAN 2.0 deployment NCKU runs on its own host and its own domain, carrying 108 datasets and two NCKU-authored CKAN extensions (nckumetadata, nckutemplatehelper), released under Taiwan's Open Government Data License v1. Its Action API answers anonymous callers with valid JSON and is the only endpoint in this profile that returns machine-readable institutional data without credentials. Everything else is either a vendor tenancy or barely reachable. Library discovery is Ex Libris Primo VE under an NCKU tenant view (886NCKU_INST) and is recorded as a relationship, not as NCKU's engineering — no Ex Libris contract is saved here. The NCKU institutional repository (NCKUR) at nckur.lib.ncku.edu.tw is NCKU's own DSpace, confirmed live and self-identifying as "Powered By DSPACE, MIT" Version 7.0 during one of only three responsive windows in roughly thirty probes on 2026-09-01 — the host refuses TCP the rest of the time. No OAI-PMH or REST interface survived probing: /oai/request?verb=Identify returns a genuine 404 and every other candidate path fell inside a refusal window, so the 2026-06 profile's DSpace REST and OAI-PMH claims stay unverified. NCKU's Shibboleth identity provider resolves in DNS at idp.ncku.edu.tw but its ports do not answer from outside Taiwan, and Taiwan has no federation in eduGAIN, so the IdP is named as an unverified lead rather than credited as a surface. NCKU registers no DOI prefix with either DataCite or Crossref. There is no central developer portal, no API key program and no institution-authored OpenAPI anywhere on the ncku.edu.tw estate.

**Areas:** University · Higher Education · Education · Taiwan · Asia · Public Research University · Open Data · CKAN · Research Data · Library · Course Catalog · Institutional Repository

## National Cheng Kung University on APIs.io

Everything profiled for National Cheng Kung University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ncku/](https://apis.io/providers/ncku/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [NCKU Open Data Platform (CKAN Action API)](https://apis.io/apis/ncku/opendata/) — NCKU's institutional open data portal, a CKAN 2.0 deployment on NCKU's own host publishing 108 datasets from the university and its affiliated units —…
- [NCKU Library discovery (Ex Libris Primo VE tenancy)](https://apis.io/apis/ncku/library-discovery/) — NCKU Library's catalog and discovery layer runs on Ex Libris Primo VE backed by Alma, under the NCKU tenant view 886NCKU_INST. The search interface is a…
- [NCKU Institutional Repository (NCKUR, DSpace)](https://apis.io/apis/ncku/institutional-repository/) — NCKUR is NCKU's institutional repository — theses, dissertations and university scholarly output under handle prefix 987654321, with roughly 294 handle…
- [ROR organization record (01b8kcc49)](https://apis.io/apis/ncku/ror-registration/) — NCKU's Research Organization Registry record — ror.org/01b8kcc49, established 1931, status active, declared domain ncku.edu.tw — and the canonical…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ncku Context](https://apis.io/jsonld/ncku/ncku-context/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Ncku Domain Security](https://apis.io/security/ncku/ncku-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ncku Plans Pricing](https://apis.io/plans/ncku/ncku-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ncku Rate Limits](https://apis.io/rate-limits/ncku/ncku-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ncku Finops](https://apis.io/finops/ncku/ncku-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ncku.edu.tw/index.php?Lang=en)
- [Terms of service](https://data.ncku.edu.tw/zh_TW/about)
- [GitHub](https://github.com/ncku-csie)

## API Evangelist rating

**Kin Score 14.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 9.5 |
| Access clarity | 10.5 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 12.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ncku/](https://apis.io/providers/ncku/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for National Cheng Kung University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ncku/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
