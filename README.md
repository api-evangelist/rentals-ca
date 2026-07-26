# Rentals.ca (rentals-ca)

Rentals.ca is a Toronto-headquartered residential rental marketplace and the flagship brand of the Rentals.ca Network, which also operates Rentfaster.ca, Louer.ca, Rentboard.ca, RentCanada.com and TorontoRentals.com across more than 100 Canadian cities. The network is owned and operated by Rentsync (formerly Landlord Web Solutions Inc.), which also acquired the research firm Urbanation in January 2026 and co-publishes the monthly Rentals.ca / Urbanation National Rent Report; Rentals.ca listing data also feeds a Statistics Canada rental housing index. In the Canadian real estate value chain it sits on the rentals side of the market, outside CREA's REALTOR.ca and Data Distribution Facility, which syndicate member boards' for-sale listings. Its API posture is honest but closed: rentals.ca itself publishes no developer portal, no OpenAPI, and no documented public endpoint, and the entire consumer site sits behind a Cloudflare managed challenge that returns HTTP 403 to anonymous clients. The real developer surface belongs to the parent, at the Rentsync Partners portal (partners.rentsync.ca, branded "LIFT System API"), which publicly names a REST API, an Ad Syndication API and a Search API but places all documentation behind an account whose registration form requires a written application explaining what you intend to build. There is no RESO Web API or Data Dictionary certification, no OData $metadata document, no Universal Property Identifier, and no open dataset published by the company.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rentals-ca/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rentals-ca/refs/heads/main/apis.yml)

## Tags

- Real Estate
- Canada
- Rentals
- Property Listings
- Rental Marketplace
- PropTech
- Listing Syndication
- Market Data

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

### Rentsync Partners REST API

REST API described on the public Rentsync Partners portal (branded "LIFT System API") as giving partners "access to the underlying data structures of the LIFT System" with "detailed Canadian rental information". This is the API layer behind the Rentals.ca Network's rental listing data. Documentation is not public — https://partners.rentsync.ca/documentation returns HTTP 302 to /users/sign_in — and no base URL, endpoint list, or authentication scheme is disclosed anonymously. Access requires registering and submitting a written application describing what you plan to build.

- **Human URL:** [https://partners.rentsync.ca/](https://partners.rentsync.ca/)

#### Tags

- Rentals
- Property Listings
- Canada

#### Properties

- [Portal](https://partners.rentsync.ca/)
- [Signup](https://partners.rentsync.ca/users/sign_up)
- [Login](https://partners.rentsync.ca/users/sign_in)

### Rentsync Ad Syndication API

Ad syndication API described on the public Rentsync Partners portal as programming interfaces used to "interact with rental industry professionals using Rentsync's Ad Syndication to manage their online advertising". This is the machine interface to the listing-distribution business that pushes property advertising into the Rentals.ca Network and partner portals. Documentation sits behind the same approved-account gate; no base URL, feed schema, or auth model is published anonymously.

- **Human URL:** [https://partners.rentsync.ca/](https://partners.rentsync.ca/)

#### Tags

- Listing Syndication
- Advertising
- Rentals

#### Properties

- [Portal](https://partners.rentsync.ca/)
- [Signup](https://partners.rentsync.ca/users/sign_up)

### Rentsync Search API

Search API described on the public Rentsync Partners portal as a way to "query the LIFT platform for specific information", positioned by the vendor as "a great way to get data for mapping applications" — the geospatial and query surface over Canadian rental listings. Documentation is gated behind an approved partner account; no base URL, query grammar, or rate limits are published anonymously.

- **Human URL:** [https://partners.rentsync.ca/](https://partners.rentsync.ca/)

#### Tags

- Search
- Geospatial
- Rentals

#### Properties

- [Portal](https://partners.rentsync.ca/)
- [Signup](https://partners.rentsync.ca/users/sign_up)

## Common Properties

- [Website](https://rentals.ca/)
- [Portal](https://partners.rentsync.ca/)
- [Signup](https://partners.rentsync.ca/users/sign_up)
- [Login](https://partners.rentsync.ca/users/sign_in)
- [StatusPage](https://status.rentals.ca/)
- [Blog](https://rentals.ca/blog)
- [LinkedIn](https://ca.linkedin.com/company/rentals.ca)
- [Website](https://rentsync.com/)
- [Documentation](https://rentsync.com/integrations)

## RESO Posture and Access Gate

- **RESO posture:** no RESO reference found. No Web API or Data Dictionary certification, no `$metadata` document, no Universal Property Identifier. RESO is a US MLS/NAR artifact; Canadian for-sale listings run through CREA's REALTOR.ca DDF (itself a RESO Web API implementation), and Rentals.ca is a rentals marketplace outside that seam entirely.
- **RESO certified:** false
- **Access gate:** `application-approval` — register at partners.rentsync.ca and submit a written application ("Tell us why you want access to the LIFT API. What are you planning to build?"). No MLS or board membership, no IDX/VOW data licence, no real-estate licence required — and no self-serve key issuance either.
- **Open data:** none published by the company.
- **Auth model:** not publicly documented; the partner portal itself is a Rails/Devise username-and-password login. No OIDC discovery document (`/.well-known/openid-configuration` returns 404).
- **Home market:** Canada.

See [review.yml](review.yml) for every URL probed, its HTTP status, and the full evidence trail.

## Maintainers

- Kin Lane — kin@apievangelist.com
