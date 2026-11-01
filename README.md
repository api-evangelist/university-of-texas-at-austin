# University of Texas at Austin

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

The University of Texas at Austin is a flagship public research university in Austin, Texas, United States, and the largest institution in the University of Texas System. It operates no central developer portal, publishes no institution-wide API catalog, and its enterprise integration APIs (Identity and Access Management, student and financial systems) are gated behind UT EID authentication and an internal ServiceNow request process, so they are not publicly readable. What UT Austin does genuinely operate and expose publicly is narrower and more specific than a portal: the Tapis v3 research-computing platform, designed, built and run by the Texas Advanced Computing Center — an organized research unit of UT Austin — which serves five OpenAPI-described services (Systems, Files, Apps, Jobs, Notifications) on its production TACC tenant; an InCommon-registered Shibboleth identity provider publishing both SAML 2.0 metadata and an OpenID Connect discovery document; and Texas ScholarWorks, the UT Libraries DSpace repository, with a public REST API and an OAI-PMH 2.0 harvesting endpoint on the university's own host. Its research-data archive is a tenancy rather than an operation: UT Austin publishes into a Dataverse collection on the Texas Digital Library's shared instance, and the library discovery layer is Ex Libris Primo. Both are recorded here as relationships, not as UT Austin engineering.

**Areas:** University · Higher Education · Education · Public Research University · United States · Texas · Research Computing · Identity Federation · Institutional Repository · Research Data · Library · Open Data

## University of Texas at Austin on APIs.io

Everything profiled for University of Texas at Austin is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-texas-at-austin/](https://apis.io/providers/university-of-texas-at-austin/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [UT Austin Enterprise Identity Provider (SAML 2.0 + OpenID Connect)](https://apis.io/apis/university-of-texas-at-austin/enterprise-idp/) — UT Austin's Shibboleth identity provider, and the most under-catalogued class of institutional API surface. It publishes SAML 2.0 metadata at…
- [Texas ScholarWorks DSpace REST API](https://apis.io/apis/university-of-texas-at-austin/scholarworks-rest/) — Public DSpace REST API for Texas ScholarWorks, the UT Libraries institutional repository of theses, dissertations, faculty research and open-access…
- [Texas ScholarWorks OAI-PMH Endpoint](https://apis.io/apis/university-of-texas-at-austin/scholarworks-oai/) — OAI-PMH 2.0 metadata-harvesting endpoint for Texas ScholarWorks. An Identify request returns repositoryName "DSpace at UT Austin", baseURL…
- [Texas Data Repository (Dataverse) — UT Austin collection](https://apis.io/apis/university-of-texas-at-austin/texas-data-repository/) — UT Austin publishes and archives research datasets in the Texas Data Repository, a Dataverse instance operated by the Texas Digital Library and shared…
- [University of Texas at Austin Applications API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-applications-api/) — Manage Tapis application resources. Create, retrieve, update, etc.
- [University of Texas at Austin Archive transfers (Beta) API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-archive-transfers-beta-api/) — The Archive transfers (Beta) API from University of Texas at Austin — 2 operation(s) for archive transfers (beta).
- [University of Texas at Austin Child Systems API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-child-systems-api/) — A system that has *allowChildren* set to *true* allows for the creation of child systems based on it. This ability provides a way to easily clone and manage…
- [University of Texas at Austin Content API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-content-api/) — Download a file or directory. Not supported for all system types.
- [University of Texas at Austin Credentials API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-credentials-api/) — Manage Tapis system user access credentials.
- [University of Texas at Austin Events API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-events-api/) — Event publication
- [University of Texas at Austin File Operations API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-file-operations-api/) — Manage file resources on Tapis systems. List, upload, copy, native operations, etc. Note that not all operations are supported for all system types.
- [University of Texas at Austin General API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-general-api/) — General service health and readiness
- [University of Texas at Austin Jobs API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-jobs-api/) — manage job execution and data
- [University of Texas at Austin Permissions API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-permissions-api/) — The permissions model allows for fine grained access control of resources. The application owner may grant READ and MODIFY permission to specific users.…
- [University of Texas at Austin Post Its API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-postits-api/) — The PostIts API from University of Texas at Austin — 4 operation(s) for postits.
- [University of Texas at Austin Scheduler Profiles API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-scheduler-profiles-api/) — The Systems service supports managing Tapis scheduler profiles. An HPC center often has certain conventions and restrictions around the use of batch…
- [University of Texas at Austin Sharing API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-sharing-api/) — In addition to fine grained permissions support, Tapis also supports a higher level approach to granting access. This approach is known simply as *sharing*.…
- [University of Texas at Austin Subscriptions API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-subscriptions-api/) — manage job subscriptions
- [University of Texas at Austin Systems API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-systems-api/) — Manage Tapis system resources. Create, retrieve, update, etc.
- [University of Texas at Austin Test API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-test-api/) — Support for managing a sequence of test notifications.
- [University of Texas at Austin Transfers API](https://apis.io/apis/university-of-texas-at-austin/university-of-texas-at-austin-transfers-api/) — Manage file transfers between two systems. Initiate, cancel and retrieve status. Note that not all combinations of system types are supported. For example,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Texas At Austin Context](https://apis.io/jsonld/university-of-texas-at-austin/university-of-texas-at-austin-context/)

#### Examples (4)

Example requests and responses.

- [University Of Texas At Austin Idp Openid Configuration](https://apis.io/examples/university-of-texas-at-austin/university-of-texas-at-austin-idp-openid-configuration/)
- [University Of Texas At Austin Scholarworks Dspace Root](https://apis.io/examples/university-of-texas-at-austin/university-of-texas-at-austin-scholarworks-dspace-root/)
- [University Of Texas At Austin Tapis Systems Healthcheck](https://apis.io/examples/university-of-texas-at-austin/university-of-texas-at-austin-tapis-systems-healthcheck/)
- [University Of Texas At Austin Tdr Dataverse Collection](https://apis.io/examples/university-of-texas-at-austin/university-of-texas-at-austin-tdr-dataverse-collection/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Texas At Austin Authentication](https://apis.io/security/university-of-texas-at-austin/university-of-texas-at-austin-authentication/)
- [University Of Texas At Austin Domain Security](https://apis.io/security/university-of-texas-at-austin/university-of-texas-at-austin-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Texas At Austin Scopes](https://apis.io/scopes/university-of-texas-at-austin/university-of-texas-at-austin-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Texas At Austin Plans Pricing](https://apis.io/plans/university-of-texas-at-austin/university-of-texas-at-austin-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Texas At Austin Rate Limits](https://apis.io/rate-limits/university-of-texas-at-austin/university-of-texas-at-austin-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Texas At Austin Finops](https://apis.io/finops/university-of-texas-at-austin/university-of-texas-at-austin-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.utexas.edu/)
- [Documentation](https://docs.tacc.utexas.edu/)
- [API reference](https://tapis.readthedocs.io/en/latest/technical/index.html)
- [Support](https://tacc.utexas.edu/about/help/)
- [Blog](https://news.utexas.edu/)
- [Terms of service](https://www.utexas.edu/site-policies)
- [Privacy policy](https://security.utexas.edu/policies)
- [GitHub](https://github.com/TACC)

## API Evangelist rating

**Kin Score 39.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 57.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 35.7 |
| Access clarity | 39.5 |

**Agent readiness 26.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
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

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-texas-at-austin/](https://apis.io/providers/university-of-texas-at-austin/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Texas at Austin: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-texas-at-austin/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
