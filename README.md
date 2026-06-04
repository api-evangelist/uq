# University of Queensland (uq)

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
