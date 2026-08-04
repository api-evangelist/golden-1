# Golden 1 Credit Union (golden-1)

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

Golden 1 Credit Union is a state-chartered, member-owned not-for-profit financial cooperative headquartered in Sacramento, California — one of the largest credit unions in the United States, serving roughly 1.1 million members with approximately 20 billion dollars in assets. Founded in 1933 and open to all Californians, it provides consumer checking, savings, credit cards, auto and home lending, and digital banking, and holds the naming rights to Golden 1 Center in Sacramento.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/golden-1/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/golden-1/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Golden 1 publishes **no public developer portal and no first-party public API**. Probes on 2026-07-23 found `developer.golden1.com` and `developers.golden1.com` do not resolve (NXDOMAIN); `api.golden1.com` exists only as a private, Akamai-fronted backend for its own mobile/web apps (returns HTTP 403, no documentation). This is the typical and honest posture for a US credit union.

US open finance is voluntary and fragmented — there is no single mandated open-banking contract as in the UK or Australia. Golden 1's digital banking runs on a core-provider platform, and consumer-permissioned account data is reachable only **indirectly through third-party aggregators** (Plaid, MX, Finicity, Akoya), not through a documented first-party open-finance API. No documented FDX (Financial Data Exchange) participation or published CFPB Section 1033 data-access posture was found for this institution.

## Tags

- Financial Services
- Banking
- Credit Union
- United States
- Consumer Finance
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Golden 1 Credit Union exposes no public, documented API. Account-data access for members occurs via third-party aggregators only.

## Common Properties

- [Website](https://www.golden1.com/)
- [LinkedIn](https://www.linkedin.com/company/golden-1-credit-union)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
