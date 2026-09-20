# Record maintenance

[Home](../README.md)

Maintain public records in Markdown through reviewed PRs. The
[award process](award-process.md) defines submission, public review, challenges,
identity checks and award confirmation.

## Where to record information

| Location | Purpose |
| --- | --- |
| [Problem bank](../problems/README.md) | Original problems, mathematical solutions, pinned Lean proof sources and attribution. |
| [Candidate register](../candidates/README.md#candidate-register) | Public candidates and each contribution type's public-review start. |
| Claim issues and submission PRs | Applications, review evidence and public conclusions, including solver applications awaiting formalization. |
| [Awards](../awards/README.md) | Confirmed, publicly announced awards and supporting evidence. |

## Maintaining the records

Identify contributions by JSP problem ID and contribution type. Keep contributor
names, accepted PRs, proof references and public-review dates consistent with the
[award process](award-process.md). Record public challenge outcomes in the relevant
PR or issue and update the candidate register accordingly.

Before concluding review, use the optional [citation template](templates/citation.md)
to record the check for relevant pending PRs and its outcome. Record candidate
start and end dates in UTC; retain date-only precision for historical entries.

For an announced award, record the problem, contribution type, recipients,
published level, announcement link, completed review dates and public evidence
in English Markdown under `awards/`. Update the register for that contribution;
the other contribution type keeps its own review period. The optional
[attribution template](templates/recipients.md) helps record contributors and
supporting sources.

## Verification evidence and private information

Follow the [verification guide](verification.md) for the original problem,
pinned proof commit, statement correspondence, reproduction results and public
evidence links. Reports may be included in the PR or linked from the proof
repository or a stable public archive. Keep Lean source and build artifacts out
of this repository.

Keep private identity documents, correspondence, payment and delivery details,
and internal assessment materials out of repository files and commits. Reviewers
check mathematical content, attribution and award eligibility.
