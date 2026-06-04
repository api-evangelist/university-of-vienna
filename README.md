# University of Vienna (university-of-vienna)

The University of Vienna (Universität Wien), founded in 1365, is Austria's largest university and ranks #78 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an APIs.json provider profile. The institution does not operate a central branded API developer portal; its strongest verified public API surface is scholarly infrastructure — the PHAIDRA institutional repository — plus third-party institutional data via the European HEI API.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-vienna/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-vienna-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Repository, Open Data, Austria, Europe

## APIs

- **PHAIDRA REST API** — institutional repository REST(ish) API for research data and digital collections, with an OpenAPI spec. Docs: https://phaidra.org/docs/api/ | OpenAPI: https://services.phaidra.univie.ac.at/api/openapi
- **PHAIDRA OAI-PMH Endpoint** — metadata harvesting (oai_dc, oai_openaire) used by OpenAIRE, Europeana, BASE and others. Docs: https://phaidra.org/docs/api/ | Base: https://services.phaidra.univie.ac.at/api/oai/
- **HEI API (University of Vienna record)** — third-party European Higher Education Institutions API exposing University of Vienna data in JSON:API. Docs: https://hei.api.uni-foundation.eu/about

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-vienna-plans-pricing.yml](plans/university-of-vienna-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-vienna-rate-limits.yml](rate-limits/university-of-vienna-rate-limits.yml)
- FinOps: [finops/university-of-vienna-finops.yml](finops/university-of-vienna-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.univie.ac.at/en/
- LinkedIn: https://www.linkedin.com/school/univienna/
- Plans, RateLimits, FinOps, Review pointers (see files above and review.yml)

## Notes

All URLs in this profile were probed live on 2026-06-03 and returned HTTP 200; see [review.yml](review.yml) for per-endpoint status. No endpoints were fabricated. The PHAIDRA API documentation lives on the shared PHAIDRA project docs site (phaidra.org), while the live API and OAI-PMH endpoints are hosted at services.phaidra.univie.ac.at. No official University of Vienna GitHub organization was confirmed (github.com/univie resolves to a personal account). The course directory (u:find) and library discovery (u:search / Alma-Primo) are public web services but publish no open developer documentation. The HEI API is operated by the European University Foundation, not by the university.

## Maintainers

- Kin Lane — kin@apievangelist.com
