# Recipient eligibility and contribution attribution

Public records credit mathematical and formalization contributions using their published sources. These contributions may come from different people or teams.

For solver and Lean credits in the problem bank, see the [attribution conventions](../problems/README.md#attribution-conventions). Each **Attribution basis** row links to the evidence supporting those credits.

Keep identity documents, private contact details, written agreements and private payment arrangements out of public issues and repository files. Public identity attestations and contribution descriptions must be authorized for publication.

A contribution credit or candidate record does not announce an award. Confirmed recipients appear in the relevant [award record](../awards/README.md).

## Claiming an award

Apply after the relevant contribution PR has merged. Each contribution type's
14-day public review starts when its candidate is added to the public register
in `candidates/` and public notice begins, provided an accepted formalization
source is available. Use the recorded public-notice start, not a PR merge time. Claim and identity checks proceed alongside that review;
they do not set its start time. Follow the [award process](award-process.md).

Mathematical review remains required, but Lean verification and candidate
registration do not depend on the solver having registered or submitted a claim.
The two contribution types may be registered independently; no prior solver
candidate or award record is required for a Lean claim.

Use the [award claim form](../.github/ISSUE_TEMPLATE/claim-award.yml) only for your
own contribution using your own GitHub account. Proxy applications and collection
on another person's behalf are not accepted. Include the problem-bank link, JSP
number in the title, merged PR, contribution role and public follow-up email.
Update an existing application instead of submitting duplicates.

For Lean or both-role claims, supply your own original proof repository already
recorded as the formalization source. It must belong to your submitting GitHub
account. For mathematical solution only, the repository field is optional:
leave it blank or link the recorded formalization source, even if it belongs to
someone else. Maintainers use the catalog's existing source when available;
`None` is also accepted while awaiting formalization. For Lean or both-role
claims, request a missing repository URL before approval even though the form
permits a blank field. An accepted solver may register an application before formalization is
available, regardless of the catalog's current **Eligible to claim** flag; retain
the application time, but do not start public review or pay an award. Notify the
solver and start their review once an accepted formalization source is available.

Only complete solutions and complete Lean proofs of the original problem are
accepted. Use the evidence already in the catalog; applicants do not need to
repeat branch, commit or theorem details. Resolve missing or incorrect attribution
through a linked correction or PR before claim approval.

The follow-up email is public and is the correspondence address for the claim;
no extra comment is needed to designate it. Use the GitHub account as the public
applicant identity. Send private identity materials,
payment network/address and medal delivery address only by email to
**thejustinsunprize@hejustinsun.com**. Official email comes only from
**@hejustinsun.com**; we never request private keys or seed phrases.

Every applicant must send an identity-verification email from the follow-up
address in their claim issue to **thejustinsunprize@hejustinsun.com**, linking the
claim issue and merged PR using the [email template](award-process.md#email-template).
This applies to mathematical-solution-only, Lean-only and both-role claims, even
when source attribution already establishes the account-to-author connection.
A supplied contact email, sent message, form declaration or checkbox alone does
not establish identity or contribution. All recipients still require written
confirmation before an award.

### Mathematical solver verification

Use the complete proof or publication and attribution evidence already linked in
the problem-bank entry, including the recorded co-contributions. Do not ask the
applicant to duplicate those references. A new GitHub account is permitted; prior
GitHub activity is not a condition for a mathematical claim.

Maintainers assess whether the result solves the full original problem and whether
the evidence supports the claimed contribution. They independently locate an
established author contact channel in the publication, institutional profile or
historical project, and ask the author to confirm their connection to the applicant
account, the issue and the contribution description. Do not rely solely on a new
contact address supplied by the applicant. Where such a channel is unavailable,
use additional historical evidence and independent corroboration; the identity
remains pending until the evidence is sufficient. Co-authorship alone does not
establish sole credit or resolve competing claims.

Applicants must propose an independently verifiable way to confirm their identity.
No single verification method is mandatory.
Possible methods include:

- Send confirmation to `thejustinsunprize@hejustinsun.com` from an author email
  independently located in the paper. Maintainers verify control of that established
  mailbox through a fresh reply or challenge; a displayed sender name, forwarded
  message or screenshot alone is insufficient.
- Respond to a fresh challenge through an established institutional or author
  website already publicly linked to the author.
- Sign a fresh challenge using a historical key already independently associated
  with the author. A newly created key with only a self-declared name is insufficient.
- Propose another verifiable method or a combination of historical records and
  independently contacted corroborators for maintainer review.

The identity confirmation must bind the applicant to the GitHub account, claim
issue, problem ID and claimed role(s). Maintainers assess whether the evidence
establishes the identity connection and may request additional
verification. A claimed affiliation, profile link or proposed method alone does
not verify identity. Describe the method and provide private evidence by email to
the official address. A public method-only note in the issue is optional. Using an established
author mailbox is one verification option, not a requirement to regain access to
a particular mailbox; a follow-up email can coordinate website, historical-key or
other independent checks. If the author mailbox differs from the follow-up
address, independently verify the connection between those channels.

### Lean contributor verification

For a Lean or both-role claim, check the original proof repository URL. Its owner must
be the issue author's GitHub account; a mirror or collection of someone else's
proof is not an acceptable original source. Compare it with the pinned proof
version, theorem and attribution references in the problem-bank entry. Applicants
do not need to repeat branch, commit or theorem details already recorded there.
Resolve missing or conflicting references through a linked catalog correction.
Keep proof source and build artifacts in the external repository.

The applicant must be the actual contributor using their own account associated
with the proof contribution. Repository ownership, being the last committer, or
uploading someone else's code does not establish authorship. Commit author text
and screenshots alone are insufficient. Work committed through a bot, shared
account or another contributor requires a documented connection to the actual
applicant and manual review; it does not permit someone else to claim for them.

Submitting the issue confirms control of the submitting GitHub account. Maintainers
must separately match that account to the formalization author identified in
source records such as `sources.yaml` or the original repository's authorship
credits. A catalog display credit based on repository ownership is insufficient.
Lean applicants must also send the identity-verification email required above;
source attribution supports the review but does not replace that step.
If source attribution does not establish the account-to-author connection, use
the independent identity-verification process described for mathematical solvers;
the claim remains pending until that connection is verified. Posting the issue
does not by itself establish authorship or mathematical correctness. The issue's
identity-verification-method field is an optional public note;
required identity details are supplied by email. Applicants claiming both roles
must still complete mathematical solver identity verification.

### One person claiming both contributions

Use one issue with both roles selected. Review the mathematical and Lean evidence
from the catalog separately; approval of one role does not approve the other. Once identity is
confirmed, associate both contributions with the same recipient rather than
creating duplicate identities. Each role has an independent public-review clock
and contribution record, so one may be confirmed while the other remains a
candidate. If one role is displaced by a verified challenge, explain the outcome
in the issue and retain the other active claim; close the issue only when no
active claim remains. If no claim issue exists yet, explain the replacement in
the dispute issue and update the candidate record and public notice. Check duplicate
claims before payment.

### Payment arrangements

After the applicable 14-day public review has ended with no unresolved challenges
or relevant pending PR reviews under the
[review-completion rules](award-process.md#the-14-day-public-review),
complete written recipient confirmation and identity checks by email. The record
remains a candidate until confirmation is complete. Collect outstanding payment
network/address and medal delivery address through the official email only.
Then announce the award, move the contribution record into its monthly award
batch, send the prize money and medal, and confirm delivery.

Maintainers privately link the verified recipient, claim and approved contribution
roles to the agreed payment arrangements. Changes require fresh confirmation
through the verified recipient channel. Each approved contribution remains
recorded separately.

### Maintainer review record

The process is: verify and accept the submission; merge the contribution PR;
maintainers publish the candidate in `candidates/` when formalization is
available; start each contribution type's 14-day review when its candidate is
added to the public register and public notice begins, alongside
self-application and identity checks; resolve challenges and relevant pending PR
reviews for the same problem and contribution type; obtain written recipient
confirmation; announce the award; deliver prize money and a medal. A successful
priority challenge restarts the affected contribution type's public review when
the replacement candidate is added to `candidates/` for public notice.
A solver awaiting formalization is registered without starting the review clock.
Record mathematical and Lean review outcomes separately, including not applicable
where appropriate. Retain the catalog revision and proof references used in the
review so later catalog changes do not silently change the reviewed claim. Use
the public notice table for role-specific dates and authorized candidate
identities. Explain a displaced claim in its issue; keep detailed challenge
handling notes, identity checks, application-time records and correspondence in
the private review records. Private identity and payment materials travel only
through the official email.

Only maintainer-reviewed outcomes establish verification. Applicant edits and
checkboxes cannot mark a claim verified. An issue form cannot technically prevent
impersonation or proxy submissions; maintainers reject those claims during review.
These review notes are not new award-record lifecycle values and do not change
the existing requirements for confirmed recipients or published award records.
