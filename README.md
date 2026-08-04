# University of Queensland (uq)

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

The University of Queensland (UQ) is a public research university in Brisbane, Australia, ranked #54 in the QS World University Rankings 2025. This repository catalogs UQ's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. UQ's verifiable API surface is concentrated in its library and research infrastructure (UQ eSpace), with broader institutional data access gated behind governance approval.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/uq/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=uq-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Institutional Repository, Open Data, Australia

## APIs

- **UQ eSpace OAI-PMH** — OAI-PMH metadata harvesting for UQ's institutional repository. Base: `https://espace.library.uq.edu.au/oai.php`. Docs: https://espace.library.uq.edu.au/about
- **UQ eSpace REST API** — REST access to research outputs and datasets, with documented executable examples. Docs: https://espace.library.uq.edu.au/view/UQ:10582
- **Central Integration Platform** — Gated API platform for transactional/business data; access via the Integration Services Team. Docs: https://data.uq.edu.au/explore-and-access-data/central-integration-platform

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/uq-plans-pricing.yml](plans/uq-plans-pricing.yml)
- Rate Limits: [rate-limits/uq-rate-limits.yml](rate-limits/uq-rate-limits.yml)
- FinOps: [finops/uq-finops.yml](finops/uq-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uq.edu.au/
- GitHub: https://github.com/uqlibrary
- LinkedIn: https://au.linkedin.com/school/university-of-queensland/
- Developer Portal: https://data.uq.edu.au/
- Review: [review.yml](review.yml)

## Notes

All entries reflect only publicly verifiable resources. UQ does not operate a single unified open developer portal. The eSpace OAI-PMH and API documentation hosts return HTTP 403 to automated requests due to a WAF/Cloudflare layer; these are live, real endpoints (accessible to standard harvesters and browsers), not dead links. The Central Integration Platform and Data Hub are gated — they require approval and contact-based onboarding and publish no open endpoints. No endpoints were invented; gated and access-controlled services are flagged as such.

## Maintainers

- Kin Lane — kin@apievangelist.com
