# Golden 1 Credit Union (golden-1)

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
