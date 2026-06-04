# Lund University (lund)

Lund University is a public research university in Lund, Sweden, founded in 1666 and ranked #74 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. The most substantial public surface is the Lund University Libraries' Lund University Publications (LUP) service, which exposes a JSON Search API, OAI-PMH, SRU/CQL, unAPI, and RSS feeds. The Lund University Research Portal (LUCRIS on Elsevier Pure) is documented as offering API/RSS retrieval but is largely affiliation-gated.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/lund/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=lund-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Sweden, Research, Library, Open Data, Publications

## APIs

- **Lund University Publications (LUP) Search API** — REST/JSON(P) search over the publications database. Docs: https://lup.lub.lu.se/search/doc/api
- **LUP OAI-PMH** — OAI-PMH 2.0 metadata harvesting at `https://lup.lub.lu.se/oai`. Docs: https://lup.lub.lu.se/search/doc/api
- **LUP SRU** — SRU 1.1 + CQL search at `https://lup.lub.lu.se/sru`. Docs: https://lup.lub.lu.se/search/doc/api
- **LUP unAPI** — unAPI 1 discovery for alternate record formats. Docs: https://lup.lub.lu.se/search/doc/api
- **Lund University Research Portal (LUCRIS / Pure)** — External interface to the LUCRIS research information system; documented API/RSS retrieval, gated. Docs: https://www.staff.lu.se/research-and-education/research-support/lucris/research-portal

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/lund-plans-pricing.yml](plans/lund-plans-pricing.yml)
- Rate Limits: [rate-limits/lund-rate-limits.yml](rate-limits/lund-rate-limits.yml)
- FinOps: [finops/lund-finops.yml](finops/lund-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.lunduniversity.lu.se/
- GitHub: https://github.com/lunduniversity
- LinkedIn: https://www.linkedin.com/school/lund-university/
- Developer Portal: https://lup.lub.lu.se/search/doc/api
- Review: [review.yml](review.yml)

## Notes

The LUP Search API (JSON), OAI-PMH, and SRU endpoints were verified live (HTTP 200). The documented `/search/oai` and `/search/sru` paths return 404; the working canonical paths are `/oai` and `/sru`, which is what this profile catalogs. The Research Portal runs on Elsevier Pure and is documented as offering API/RSS retrieval, but its public Pure web service OAI endpoint returned HTTP 500 and full API access is not openly self-service, so it is listed as a documented-but-gated property. No endpoints were fabricated; only live-verified or vendor-documented interfaces are included.

## Maintainers

- Kin Lane — kin@apievangelist.com
