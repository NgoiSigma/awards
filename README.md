# The Justin Sun Prize

A public repository for The Justin Sun Prize: recognizing mathematical breakthroughs and machine-verifiable formal proofs through a problem-list-based academic bounty mechanism.

[About the prize](docs/about.md)

## Explore

| Topic | Source |
| --- | --- |
| Purpose, scope, and governance | [About](docs/about.md) |
| Submission, challenges, claims and 14-day public review | [Award process](docs/award-process.md) |
| Award assessment | [Grading](docs/grading.md) |
| Recipients and attribution | [Attribution](docs/attribution.md) |
| Formal verification and review | [Verification](docs/verification.md) |
| Problem bank: 1,022 problems | [Problems](problems/README.md) |
| Confirmed, publicly announced awards | [Awards](awards/README.md) |
| Public candidates | [Candidates](candidates/README.md) |
| Public roles and recusals | [People](people/README.md) |
| Machine-readable data and schemas | [Data](data/README.md) |

Award entries are confirmed and publicly announced decisions; candidates are tracked separately. The repository publishes public records; detailed assessment criteria and deliberations are not included.

## Participate

Submit solution and proof evidence using the [PR template](.github/PULL_REQUEST_TEMPLATE.md).
For Lean proof submissions, we recommend checking the exact proof commit with the
repository's [`lean-verify` skill](skills/lean-verify/SKILL.md) before opening a PR.
Using this skill and sharing a self-check report are optional; other verification
methods are welcome. See the [self-check guidance](docs/verification.md#recommended-lean-pre-submission-check).
After the participant PR merges, maintainers publish candidates in `candidates/`.
**Each contribution type's 14-day public review starts when its candidate is added
to the public register and public notice begins**, provided an accepted
formalization source is available. Use the recorded public-notice start, not a
PR merge time, to calculate the period. Open a
claim-award issue and complete identity checks alongside the review. Solvers
awaiting formalization may register an application; their review starts when
maintainers publish the candidate after formalization becomes available.
Raise candidate or award challenges through the Formal dispute issue form and
ordinary record corrections through the Correction issue form. Submit replacement
proofs or catalog updates in a linked PR. Written recipient confirmation precedes announcement and delivery of prize
money and a medal. Follow the [complete award process](docs/award-process.md) and
[public notice table](candidates/README.md#candidate-register).

You can recommend a problem, claim an award for your own contribution, correct a record, or raise a dispute using the four [issue forms](.github/ISSUE_TEMPLATE/). Award claims must be submitted by the actual contributor. Read [CONTRIBUTING.md](CONTRIBUTING.md) for evidence requirements and handling steps, and follow the [Code of Conduct](CODE_OF_CONDUCT.md). Keep identity documents, private contact details and other private personal information out of public issues.

## Repository maintenance

See the [record guide](docs/records.md) for templates, validation commands, and data generation. Source records live in `awards/` and `candidates/`; `data/*.json` is generated automatically.

Code: [LICENSE](LICENSE). Documentation and data: [LICENSE-CONTENT](LICENSE-CONTENT).
