# Public candidates

The [candidate register below](#candidate-register) is the public notice table.
Adding a candidate to this register for public notice starts that contribution
type's 14-day public review; no second publication is required.

- `verified-pending/`: formal candidates under verification, in public review, or awaiting written recipient confirmation. Consult each record's status and evidence; the pool name alone does not establish successful verification.
- `observation/`: preliminary candidates, including accepted solver applications awaiting formalization. These applications are retained without starting public review.

Neither category is an award. Both use the award record layout, including
`verification/`. A formal evidence reference requires `statement.yaml` even while
review is pending.

After the participant PR merges, maintainers publish the candidate in the register
below, once the mathematical solution has passed review and its Lean proof has
passed verification. **The 14-day public review starts when the candidate is added
to this register and public notice begins.** The recorded public-notice start is
the basis for calculating the period, not a PR merge time. A solver awaiting
formalization is notified once formalization becomes available and enters public
review when that candidate is added to the register for public notice. The claim issue and identity checks proceed alongside public
review; they do not determine its start time.

Mathematical review remains required, but the two contribution types can be
registered independently. Lean verification and candidate publication do not
require the solver to have applied or a solver candidate record to exist.
Retain a solver awaiting formalization in observation records without a review
start time; publish that candidate once formalization is available.
Link related candidate or award records when available.

Each role has its own record and clock. An accepted priority replacement replaces the
affected candidate and starts a new 14-day period when the replacement is added
to the register and its public notice begins; an unaffected role keeps its clock. Challenges raised during a period must be resolved before it ends.
If a correctness challenge invalidates a contribution without a replacement,
withdraw it from active public review and stop the affected award process. Routine
record corrections do not restart an unchanged candidate's clock.
Before concluding public review, maintainers check for pending PRs for the same
problem and contribution type (mathematical solution or Lean formalization),
regardless of submitter. If a PR could affect correctness, contribution attribution
or priority, wait for its review to finish. Unrelated PRs do not block completion;
waiting alone does not restart the clock.
Records remain candidates until public review and written recipient confirmation
are complete. See the [award process](../docs/award-process.md).

Use the [dispute issue form](../.github/ISSUE_TEMPLATE/dispute.yml) for candidate
challenges, including result, priority, identity or eligibility objections. Submit
replacement proofs or catalog updates through a linked PR using the
[normal submission template](../.github/PULL_REQUEST_TEMPLATE.md).
Private evidence goes only by email to
**thejustinsunprize@hejustinsun.com**.

The problem bank's **Eligible to claim** flags are screening markers. They do not
create candidate records or announce awards. A solver may register an accepted
solution while awaiting formalization even when the flag is not Yes.

Keep each contribution record's ID stable when moving it. An ID can occur only
once across candidates and awards. See [record maintenance](../docs/records.md).

## Candidate register

This register is the public notice of candidates. The listed contribution type's
14-day public review starts when the candidate is added here and public notice
begins. There is no separate intake-only table or later publication step.
Submitting a claim issue alone does not publish a candidate or start the clock.

The two review-start columns record when each contribution type's public notice
began, using UTC. Existing date-only entries retain their recorded publication
dates; no time of day is inferred from a PR merge. Empty cells mean that no candidate for that role is
published in this register. They do not mean the problem lacks a mathematical
solution or Lean formalization. Problem IDs link to the problem bank for public
contribution attribution and evidence. Publication is not an award or recipient
identity confirmation; identity checks and written confirmation remain required.

The existing entries retain their recorded public-notice date of **2026-09-19**.
Completion requires the full 14-day period, resolution of challenges, completion
of relevant pending PR reviews and the award requirements. Clarifying the
recorded dates does not restart their clocks.

This Markdown register is the public notice even when no structured candidate
records have been created. `data/candidates.json` indexes only the structured
records in the candidate pools; an empty index does not mean the register is empty.

| Problem ID | Solver review start (UTC) | Mathematical solver | Lean review start (UTC) | Lean formalizer |
| --- | --- | --- | --- | --- |
| [JSP-000305](../problems/catalog-0301-0400.md#JSP-000305) | | | 2026-09-19 | Wouter van Doorn |
| [JSP-000371](../problems/catalog-0301-0400.md#JSP-000371) | | | 2026-09-19 | Wouter van Doorn |
| [JSP-000381](../problems/catalog-0301-0400.md#JSP-000381) | | | 2026-09-19 | Wouter van Doorn |
| [JSP-000526](../problems/catalog-0501-0600.md#JSP-000526) | 2026-09-19 | Wouter van Doorn; Yanyang Li; Quanyu Tang | 2026-09-19 | Wouter van Doorn |
| [JSP-000866](../problems/catalog-0801-0900.md#JSP-000866) | 2026-09-19 | Quanyu Tang | | |
| [JSP-001001](../problems/catalog-1001-1022.md#JSP-001001) | 2026-09-19 | Yanyang Li | | |

When a role is awarded, replace its active candidate cell with a labeled link to
the award record and retain its completed review dates in that record. The other
role keeps its own clock. Remove a problem row once neither role remains a
candidate. If a contribution is invalidated without an accepted replacement,
remove its active candidate and review dates and retain the history. If no valid
formalization remains, retain the solver application without an active clock.
Detailed identity checks, payment/delivery information and correspondence stay
out of this public register.
