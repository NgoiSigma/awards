# Public candidates

The [register below](#candidate-register) is the public notice table, maintained
by administrators after any required participant PR merges. Each contribution type's
14-day review starts when its candidate is added for public notice, once the
mathematical solution and Lean proof have passed review and verification.

Follow the [award process](../docs/award-process.md#the-14-day-public-review) for
publication, challenges, replacements and review completion. Solver applications
awaiting formalization remain in their claim issue or submission PR without an
active review clock. Both claim statuses remain **Unavailable** unless the
problem bank's shared **Eligible to claim** flag is **Yes**, requiring both a
mathematical solution and a Lean proof. Once eligible, mark each role **Unclaimed**
until its candidate is published here, then **Claimed**. Opening a claim issue
alone does not mark a role **Claimed**. These statuses do not announce awards.

## Candidate register

The two review-start columns record when each contribution type's public notice
began, using UTC. Existing date-only entries retain their recorded publication
dates; no time of day is inferred from a PR merge. Empty cells mean that no candidate for that role is
published in this register. They do not mean the problem lacks a mathematical
solution or Lean formalization. Problem IDs link to the problem bank for public
contribution attribution and evidence. Publication is not an award or recipient
identity confirmation; identity checks and written confirmation remain required.

The existing entries retain their recorded public-notice date of **2026-09-19**.

| Problem ID | Solver review start (UTC) | Mathematical solver | Lean review start (UTC) | Lean formalizer |
| --- | --- | --- | --- | --- |
| [JSP-000305](../problems/catalog-0301-0400.md#JSP-000305) | | | 2026-09-19 | Wouter van Doorn |
| [JSP-000371](../problems/catalog-0301-0400.md#JSP-000371) | | | 2026-09-19 | Wouter van Doorn |
| [JSP-000381](../problems/catalog-0301-0400.md#JSP-000381) | | | 2026-09-19 | Wouter van Doorn |
| [JSP-000526](../problems/catalog-0501-0600.md#JSP-000526) | 2026-09-19 | Wouter van Doorn; Yanyang Li; Quanyu Tang | 2026-09-19 | Wouter van Doorn |
| [JSP-000866](../problems/catalog-0801-0900.md#JSP-000866) | 2026-09-19 | Quanyu Tang | | |
| [JSP-001001](../problems/catalog-1001-1022.md#JSP-001001) | 2026-09-19 | Yanyang Li; Quanyu Tang | | |

When a role is awarded, replace its active candidate cell with a labeled link to
the award record and retain its completed review dates in that record. The other
role keeps its own clock. Keep the awarded role's claim status **Claimed** in
the problem index, including after its candidate entry is removed.
Remove a problem row once neither role remains a
candidate. If a contribution is invalidated without an accepted replacement,
remove its active candidate and review dates and retain the history. If no valid
formalization remains, retain the solver application without an active clock.
Detailed identity checks, payment/delivery information and correspondence stay
out of this public register.
