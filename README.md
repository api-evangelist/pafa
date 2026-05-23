# Pennsylvania Academy of the Fine Arts (PAFA)

The [Pennsylvania Academy of the Fine Arts (PAFA)](https://www.pafa.org) is the United States' **first museum and school of fine arts**, founded in 1805 in Philadelphia by painter and scientist Charles Willson Peale, sculptor William Rush, and other artists and business leaders. PAFA is a 501(c)(3) cultural nonprofit located at 118-128 North Broad Street, Philadelphia, PA 19102, occupying two connected historic buildings — the Frank Furness and George Hewitt-designed **Furness-Hewitt Building** (1876; designated a National Historic Landmark in 1975) and the **Samuel M. V. Hamilton Building**, joined by Lenfest Plaza.

This repository profiles PAFA in the [API Evangelist network](https://github.com/api-evangelist). PAFA is a cultural nonprofit, not a technology company — it publishes **no developer portal, no APIs, no OpenAPI specifications, no SDKs, and no institutional GitHub organization**. This profile documents the institution, its programs, and the absence of any developer surface for completeness of API Evangelist's coverage of American cultural institutions.

## Profile

- **Founded**: 1805
- **Founders**: Charles Willson Peale, William Rush, and other Philadelphia artists and business leaders
- **Status**: 501(c)(3) cultural nonprofit
- **Distinction**: First museum and school of fine arts in the United States
- **Address**: 118-128 North Broad Street, Philadelphia, PA 19102
- **Phone**: (215) 972-7600
- **Visitor services email**: visitorservices@pafa.org
- **Type**: `company` (cultural institution)
- **Tier**: 3 (no-apis)

## Museum

PAFA's permanent collection focuses on 19th- and 20th-century American art, with notable holdings tied to alumni and faculty including **Mary Cassatt**, **Thomas Eakins**, **Henry Ossawa Tanner**, **William Glackens**, **Barkley L. Hendricks**, **Violet Oakley**, **Cecilia Beaux**, **Louis Kahn**, **David Lynch**, and **Njideka Akunyili Crosby**, alongside the **Linda Lee Alter Collection of Art by Women**.

### Visit

| Field | Value |
|---|---|
| Hours (Mon, Thu, Sat, Sun) | 10 AM - 5 PM |
| Hours (Friday) | 10 AM - 8 PM (extended) |
| Closed | Tuesday and Wednesday |
| Adults (18+) | $25 |
| Seniors (65+) | $23 |
| Students | $10 |
| Youth (13-17) | $5 |
| Children (12 and under) and Members | Free |

### Current and upcoming exhibitions

- **A Nation of Artists** (April 2026 - September 2027) — "a once-in-a-generation presentation celebrating 250 years of American creativity" featuring works from PAFA, the Philadelphia Museum of Art, and the Middleton Family Collection.
- **Bodies and Souls** (March 2026 - July 2026)
- **Student Works: From the 2025-2026 Academic Year** (May 2026 - June 2026)

### Digital guide

PAFA's collection and tours are delivered through the **Bloomberg Connects** free, multi-institution mobile app operated by Bloomberg Philanthropies — PAFA's only programmatic third-party distribution surface. PAFA does not operate a first-party mobile app.

## School

In March 2025 PAFA announced a financial crisis driven by a reported roughly **$3 million annual deficit** and sharp enrollment decline. Beginning with the **2024-2025 academic year**, PAFA stopped granting its own **BFA and MFA degrees**. The institution's active educational pathways as of May 2026 are:

| Program | Format | Description |
|---|---|---|
| **Fine Arts Certificate Program** | Three-year, on-site | "Designed to prepare students for entry-level professional roles within the visual arts and related creative industries." |
| **Continuing Education** | In-person and online | "An inclusive studio arts offering for artists of all ages and skill levels, from beginners to advanced creatives." |
| **Youth & Teen Programs** | K-12, summer | Summer Art Camp, Summer Academy, field trips, family programming. |
| **PAFA Shop Memberships** | Studio access | "Affordable, self-guided access to professional-grade printmaking, papermaking, and sculpture studios." |

Bachelor's degrees offered jointly through the long-running **University of Pennsylvania partnership** continue beyond the wind-down of PAFA's own degree-granting authority.

## API surface assessment

| Surface | Status |
|---|---|
| Public developer portal | None (no developer.pafa.org) |
| Public OpenAPI / AsyncAPI specs | None published |
| Public REST or GraphQL APIs | None — ticketing, donations, and account flows are private |
| Donation platform | Routed to the third-party `community.pafa.org/give` platform |
| SDKs / CLI / webhooks | None |
| Institutional GitHub org | None — the `github.com/pafa` handle is an unrelated personal account focused on ERP and WeChat tooling |
| Status page / changelog | None |
| Sandbox / Console | None |
| Engineering blog / RSS | None |
| Third-party programmatic distribution | Bloomberg Connects mobile app only |

**Tier rationale**: Tier 3 — no-apis. Cultural nonprofit museum and school with no public developer surface. Profiled to record the institution's post-2024-2025 program restructuring, not as an API provider.

## Artifacts in this repository

| Folder | File | Purpose |
|---|---|---|
| `apis.yml` | `apis.yml` | APIs.json 0.19 institutional index with common properties, fact sheet, alumni/faculty list, active programs, exhibitions, visit terms, and API surface assessment |
| `json-ld/` | `pafa-context.jsonld` | JSON-LD context mapping PAFA's institutional vocabulary to schema.org `Museum`, `EducationalOrganization`, and `NGO` |
| `vocabulary/` | `pafa-vocabulary.yml` | Domain vocabulary covering institution, museum, school, visit, giving, and API-surface terms |

No `openapi/`, `asyncapi/`, `json-schema/`, `json-structure/`, `examples/`, `rules/`, `capabilities/`, `plans/`, `rate-limits/`, or `finops/` folders exist in this repository — PAFA publishes no API surface to back them.

## Links

- Website: https://www.pafa.org
- About: https://www.pafa.org/about
- Museum: https://www.pafa.org/museum
- School: https://www.pafa.org/school
- Visit / Tickets: https://www.pafa.org/museum/visit
- Membership: https://www.pafa.org/members
- Donate: https://community.pafa.org/give
- Planned Giving: https://www.pafa.org/support/planned-giving
- Instagram: https://www.instagram.com/pafacademy
- Facebook: https://www.facebook.com/PAFAcademy
- YouTube: https://www.youtube.com/@PAFA
- Wikipedia: https://en.wikipedia.org/wiki/Pennsylvania_Academy_of_the_Fine_Arts

## Maintainer

[Kin Lane](https://github.com/kinlane) — kin@apievangelist.com
