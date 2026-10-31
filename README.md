# Rentals.ca

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

Rentals.ca is a Toronto-headquartered residential rental marketplace and the flagship brand of the Rentals.ca Network, which also operates Rentfaster.ca, Louer.ca, Rentboard.ca, RentCanada.com and TorontoRentals.com across more than 100 Canadian cities. The network is owned and operated by Rentsync (formerly Landlord Web Solutions Inc.), which also acquired the research firm Urbanation in January 2026 and co-publishes the monthly Rentals.ca / Urbanation National Rent Report; Rentals.ca listing data also feeds a Statistics Canada rental housing index. In the Canadian real estate value chain it sits on the rentals side of the market, outside CREA's REALTOR.ca and Data Distribution Facility, which syndicate member boards' for-sale listings. Its API posture is honest but closed: rentals.ca itself publishes no developer portal, no OpenAPI, and no documented public endpoint, and the entire consumer site sits behind a Cloudflare managed challenge that returns HTTP 403 to anonymous clients. The real developer surface belongs to the parent, at the Rentsync Partners portal (partners.rentsync.ca, branded "LIFT System API"), which publicly names a REST API, an Ad Syndication API and a Search API but places all documentation behind an account whose registration form requires a written application explaining what you intend to build. There is no RESO Web API or Data Dictionary certification, no OData $metadata document, no Universal Property Identifier, and no open dataset published by the company.

**Areas:** Real Estate · Canada · Rentals · Property Listings · Rental Marketplace · PropTech · Listing Syndication · Market Data

## Rentals.ca on APIs.io

Everything profiled for Rentals.ca is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rentals-ca/](https://apis.io/providers/rentals-ca/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Rentsync Partners REST API](https://apis.io/apis/rentals-ca/rentsync-partners-rest-api/) — REST API described on the public Rentsync Partners portal (branded "LIFT System API") as giving partners "access to the underlying data structures of the…
- [Rentsync Ad Syndication API](https://apis.io/apis/rentals-ca/rentsync-ad-syndication-api/) — Ad syndication API described on the public Rentsync Partners portal as programming interfaces used to "interact with rental industry professionals using…
- [Rentsync Search API](https://apis.io/apis/rentals-ca/rentsync-search-api/) — Search API described on the public Rentsync Partners portal as a way to "query the LIFT platform for specific information", positioned by the vendor as "a…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Rentals Ca Domain Security](https://apis.io/security/rentals-ca/rentals-ca-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://rentals.ca/)
- [Documentation](https://rentsync.com/integrations)
- [Blog](https://rentals.ca/blog/)
- [Terms of service](https://rentsync.com/terms-of-use)
- [Privacy policy](https://rentsync.com/privacy-policy)
- [Status](https://status.rentals.ca/)

## API Evangelist rating

**Kin Score 16.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 21.4 |
| Access clarity | 27.6 |

**Agent readiness 0.0** — human-only

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
| Rate Limit Signal | — |
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

**Regulatory alignment 13.0** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rentals-ca/](https://apis.io/providers/rentals-ca/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rentals.ca: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rentals-ca/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
