# University of Texas at Austin (university-of-texas-at-austin)

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

The University of Texas at Austin is a flagship public research university ranked #65 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) profile. UT Austin has no single centralized public developer portal; its confirmed public APIs are concentrated in library and research-data infrastructure, while enterprise integration APIs remain gated behind UT EID authentication.

APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-texas-at-austin/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-texas-at-austin-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Open Data, Institutional Repository, United States, Texas

## APIs

- **Texas ScholarWorks DSpace REST API** — DSpace 8 REST API for the UT Austin institutional repository. Docs: https://repositories.lib.utexas.edu/server/api (base: `https://repositories.lib.utexas.edu/server/api`)
- **Texas ScholarWorks OAI-PMH Endpoint** — OAI-PMH 2.0 metadata harvesting for "DSpace at UT Austin". Docs: https://guides.lib.utexas.edu/metadata-basics/harvesting (base: `https://repositories.lib.utexas.edu/server/oai/request`)
- **Texas Data Repository (Dataverse) API** — Dataverse REST API (Texas Digital Library shared instance) used by UT Austin to publish research data. Docs: https://guides.dataverse.org/en/latest/api/index.html (base: `https://dataverse.tdl.org/api`)

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-texas-at-austin-plans-pricing.yml](plans/university-of-texas-at-austin-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-texas-at-austin-rate-limits.yml](rate-limits/university-of-texas-at-austin-rate-limits.yml)
- FinOps: [finops/university-of-texas-at-austin-finops.yml](finops/university-of-texas-at-austin-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.utexas.edu/
- GitHub: https://github.com/utexas
- LinkedIn: https://www.linkedin.com/school/university-of-texas-at-austin/
- Developer Portal: https://it.utexas.edu/services/web-publishing-software-development

## Notes

All cataloged APIs were verified live on 2026-06-03: the Texas ScholarWorks DSpace REST API and OAI-PMH endpoint both returned HTTP 200 with "DSpace at UT Austin" identity, and the Texas Data Repository Dataverse API returned version 6.10.1. The Texas Data Repository is a multi-institution platform operated by the Texas Digital Library, not exclusively UT Austin's own API. UT Austin's enterprise API Registry and Identity and Access Management (IAM) APIs are real but gated behind UT EID / ServiceNow and were not publicly testable. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
