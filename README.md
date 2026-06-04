# University of Texas at Austin (university-of-texas-at-austin)

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
