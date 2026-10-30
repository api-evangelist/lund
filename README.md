# Lund University

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

Lund University is a public research university in Lund, Sweden, founded in 1666, with roughly 46,000 students across nine faculties and the MAX IV and ESS research infrastructures on its doorstep. Its programmable footprint is narrow, real, and almost entirely library-operated: Lund University Libraries run two self-hosted publication repositories on the university's own host — Lund University Publications (LUP) for research output and LUP Student Papers for theses and degree projects — and each exposes the same open, keyless stack of a JSON(P) search API, an OAI-PMH 2.0 repository, an SRU 1.1/CQL search service, a unAPI 1 discovery service, RSS feeds and a bulk bibliographic export. Lund also operates its own Shibboleth Identity Provider, registered in the Swedish national federation SWAMID and interfederated through eduGAIN, which is a genuinely institution-operated machine-readable surface. Outside those, there is no central developer portal, no self-service API key, no open data portal at data.lu.se, and no public JSON endpoint behind the course finder — the education search at lunduniversity.lu.se is server-rendered with nothing machine-readable underneath. The research portal at portal.research.lu.se is the LUCRIS research information system running on Elsevier Pure: the data is Lund's, the contract is Elsevier's, and its web service refuses anonymous callers. Library discovery (LUBcat, LUBsearch) and the timetable (TimeEdit) are likewise vendor platforms carrying Lund's name.

**Areas:** University · Higher Education · Education · Sweden · Europe · Research · Research Repository · Publications · Library · Open Metadata · Identity Federation · OAI-PMH

## Lund University on APIs.io

Everything profiled for Lund University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lund/](https://apis.io/providers/lund/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Lund University Publications Search API](https://apis.io/apis/lund/lund-publication-api/) — Keyless REST/JSON(P) search over the Lund University Publications (LUP) research-output database, operated by Lund University Libraries on Lund's own host.…
- [Lund University Publications OAI-PMH](https://apis.io/apis/lund/lup-oai/) — OAI-PMH 2.0 metadata-harvesting endpoint for the LUP research-output repository. Identify confirms repositoryName "Lund University Publications",…
- [Lund University Publications SRU](https://apis.io/apis/lund/lup-sru/) — SRU 1.1 Search/Retrieve via URL service over the LUP research-output database, querying with CQL and returning MODS 3.3 records in the…
- [Lund University Publications unAPI](https://apis.io/apis/lund/lup-unapi/) — unAPI 1 discovery service returning the alternate metadata formats available for LUP records, which is how reference managers such as Zotero autodiscover…
- [LUP Student Papers OAI-PMH](https://apis.io/apis/lund/lup-student-papers-oai/) — OAI-PMH 2.0 harvesting endpoint for the LUP Student Papers repository. Identify confirms repositoryName "Lund University Publications - Student Papers" and…
- [LUP Student Papers SRU](https://apis.io/apis/lund/lup-student-papers-sru/) — SRU 1.1 / CQL search service over the LUP Student Papers repository, returning MODS 3.3 records. No authentication required. Base URL is /student-papers/sru.
- [Lund University Shibboleth Identity Provider (SWAMID)](https://apis.io/apis/lund/idp-saml-metadata/) — Lund University's own SAML 2.0 / Shibboleth Identity Provider, serving machine-readable federation metadata at its entityID. The EntityDescriptor declares…
- [Lund University Research Portal (LUCRIS / Elsevier Pure)](https://apis.io/apis/lund/research-portal/) — Lund's tenant deployment of Elsevier Pure, branded LUCRIS, covering researchers, organisations, outputs, projects, datasets and activities at…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lund Agentic Access](https://apis.io/agentic-access/lund/lund-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Publication](https://apis.io/schemas/lund/lund-publication/)
- [SearchResult](https://apis.io/schemas/lund/lund-searchresult/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Lund Publication Structure](https://apis.io/json-structure/lund/lund-publication-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lund Context](https://apis.io/jsonld/lund/lund-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lund University Publications (LUP) Vocabulary](https://apis.io/vocabularies/lund/lund-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Lund Searchpublications Example](https://apis.io/examples/lund/lund-searchpublications-example/)

#### Collections (1)

Postman and Open Collection request collections.

- [Lund University Publications (LUP) Search Publication API](https://apis.io/collections/lund/open-lund-publication-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Lund University — jsonschema rules](https://apis.io/rules/lund/lund-jsonschema-spectral-rules/)
- [Lund University API Rules](https://apis.io/rules/lund/lund-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lund Authentication](https://apis.io/security/lund/lund-authentication/)
- [Lund Domain Security](https://apis.io/security/lund/lund-domain-security/)
- [Lund Vulnerability Disclosure](https://apis.io/security/lund/lund-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lund Plans Pricing](https://apis.io/plans/lund/lund-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lund Rate Limits](https://apis.io/rate-limits/lund/lund-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lund Finops](https://apis.io/finops/lund/lund-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.lunduniversity.lu.se/)
- [Documentation](https://lup.lub.lu.se/search/doc/api)
- [API reference](https://lup.lub.lu.se/search/doc/api)
- [Support](https://www.lunduniversity.lu.se/about-lund-university/contact-us/processing-personal-data-lund-university)
- [Blog](https://www.lunduniversity.lu.se/news)
- [Privacy policy](https://www.lunduniversity.lu.se/privacy-policy)

## API Evangelist rating

**Kin Score 41.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 60.5 |
| Contract governance | 28.0 |
| Operational transparency | 21.1 |
| Developer ergonomics | 45.2 |
| Access clarity | 15.8 |

**Agent readiness 31.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lund/](https://apis.io/providers/lund/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lund University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lund/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
