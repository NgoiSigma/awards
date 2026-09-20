## Submission type

- [ ] Mathematical solver information
- [ ] Lean proof or formalization author information

Select both when applicable. Remove sections that do not apply.

To report a problem with a recorded result, proof, attribution or priority, use
the [Correction issue form](https://github.com/TheJustinSunPrize/awards/issues/new?template=correction.yml).
For challenges to a public candidate or announced award, including priority,
identity or eligibility objections, use the
[Formal dispute issue form](https://github.com/TheJustinSunPrize/awards/issues/new?template=dispute.yml).
Use this PR template when submitting a solution or proof reference or making a
supported catalog update, and link any related issue below.
See the [submission requirements](https://github.com/TheJustinSunPrize/awards/blob/main/CONTRIBUTING.md#external-solver-and-lean-submissions).

The mathematical solution must pass review. Lean verification and candidate
registration do not require the solver to have registered or claimed an award.
The two contribution types can be registered independently.
Each contribution type's 14-day public review starts when its candidate is added
to the public register in `candidates/` and public notice begins, provided the
problem has an accepted formalization source. The recorded public-notice start,
not a PR merge time, determines the period. Solver-only
submissions without formalization are retained without starting public review.
Claims and identity checks can proceed alongside public review. See the
[award process](https://github.com/TheJustinSunPrize/awards/blob/main/docs/award-process.md).

**Only complete solutions to the original problem are accepted. Do not submit
partial mathematical results or incomplete Lean formalizations.**

**For Lean proof submissions, we recommend using the repository's
[`lean-verify` skill](https://github.com/TheJustinSunPrize/awards/blob/main/skills/lean-verify/SKILL.md)
to check the exact proof commit before opening the PR.** Using this skill and
providing a self-check report are optional; other verification methods are welcome.
If you perform a self-check, you may summarize it in the optional section below.
See the [self-check guidance](https://github.com/TheJustinSunPrize/awards/blob/main/docs/verification.md#recommended-lean-pre-submission-check).
This recommendation concerns Lean proofs only. Mathematical solvers submitting
only a solution, publication or solver information need no Lean self-check.

## Problem

- Problem ID(s): JSP-______
- Original problem source and exact location (page, section or problem number): REPLACE_WITH_LINK_AND_LOCATION
- Current entry and proposed change: REPLACE_WITH_DETAILS
- Related issue, if any: REPLACE_WITH_LINK_OR_NONE

For mathematical solver or publication updates, also provide:

- Public mathematical proof or publication: REPLACE_WITH_HTTPS_LINK
- Relevant pages, theorem, version or date: REPLACE_WITH_DETAILS

For a solver-only submission, update the catalog's **Current status** (including
**Proof contributors:**), **Publication details** and supporting **Attribution basis**
as applicable. Complete Problem and Attribution; remove the Lean-only sections.
Maintainers review the complete result and attribution before merging and reconcile
the problem index and eligibility fields.

## Formal statement

Required for Lean contributions; otherwise remove this section.

- Accepted mathematical solution and review reference (or mathematical solution evidence in this PR, to be reviewed first): REPLACE_WITH_LINKS
- Challenge file or equivalent statement location (link pinned to a full commit SHA): REPLACE_WITH_LINK
- Fully qualified target theorem name: REPLACE_WITH_THEOREM_NAME
- Statement origin (maintainer-approved reference with link, or submitter-proposed statement requiring review): REPLACE_WITH_DETAILS
- Correspondence to the original problem, including definitions, assumptions, quantifiers, conclusion and all required cases: REPLACE_WITH_EXPLANATION

`Challenge.lean` is an optional filename convention. The statement and proof may
be in the same file or separate files. Identify their exact locations either way.
If a maintainer-approved formal statement exists, identify its fixed version and
explain any differences. Otherwise, reviewers must assess the proposed statement
against the original problem before accepting the proof.

## Proof submission

**Do not submit Lean source code here; provide the public repository URL, branch and full commit SHA instead.**

Required for Lean contributions; otherwise remove this section.
Use the full 40-character commit SHA of the proof version selected for
review. Add an object for each additional proof repository.

Use your own original proof repository. The GitHub account submitting this PR
must own the repository; do not register another person's proof, a mirror or a
copy on their behalf. The selected commit is the verification target and the time
anchor for priority comparison, independent of when this PR is opened.

```json
[
  {
    "repository": "https://github.com/OWNER/REPOSITORY",
    "branch": "REPLACE_WITH_BRANCH",
    "commit": "REPLACE_WITH_FULL_COMMIT_SHA"
  }
]
```

- Submission file or equivalent proof entry (path at the commit above): REPLACE_WITH_PATH
- Fully qualified theorem name providing the complete proof: REPLACE_WITH_THEOREM_NAME
- Connection to the formal statement above (same declaration, or verification entry such as `Solution.lean`): REPLACE_WITH_DETAILS

`Submission.lean` and `Solution.lean` are optional filename conventions. Existing
project layouts are accepted if the statement, complete proof and verification
entry are clearly identified. Explain how the proof establishes the stated target
without missing cases, proof steps or additional unproved assumptions.

## Reproduction

Required for Lean contributions; otherwise remove this section.

- Exact Lean version and `lean-toolchain` path: REPLACE_WITH_VERSION_AND_PATH
- Pinned dependency versions (including mathlib, if used) and dependency manifest path: REPLACE_WITH_DETAILS
- Build instructions (link at the selected commit): REPLACE_WITH_LINK
- Commands to build and check the target proof from a clean checkout, including any setup steps: REPLACE_WITH_COMMANDS
- Command and output for the target theorem's axiom audit (for example, `#print axioms Fully.Qualified.theoremName`): REPLACE_WITH_COMMAND_AND_OUTPUT
- Statement-to-proof verification command or entry, if separate from the build command: REPLACE_WITH_COMMAND_OR_EXPLANATION

A successful build alone is insufficient. Review must check both correspondence
to the original problem and the final theorem's transitive axiom dependencies.
A designated challenge template may contain `sorry` or `admit` as an unfilled
target; the submitted proof must not depend on that placeholder (`sorryAx`) or
on unproved assumptions added to replace missing proof steps. Report all axiom
dependencies for review; standard Lean axioms are not automatically disqualifying.

## Pre-submission Lean verification (optional)

We recommend `lean-verify` for a self-check of a submitted Lean proof. You may use
another method or omit this section if no self-check is supplied. This also applies
to replacement proofs and combined submissions.

If sharing a self-check, include the available details below and remove unused fields:

- Verification tool or method (and version, if available): REPLACE_WITH_METHOD
- Proof repository and full commit SHA checked (identify any difference from Proof submission above): REPLACE_WITH_REPOSITORY_AND_FULL_COMMIT_SHA
- Verification date and actual conclusion, including limitations: REPLACE_WITH_DATE_AND_CONCLUSION
- Short result summary (statement correspondence, coverage, Lean checks and trust dependencies): REPLACE_WITH_SUMMARY
- Report pasted into this PR or linked externally: REPLACE_WITH_LINK_OR_REPORT
- Target manifest, build/axiom logs and checker evidence links: REPLACE_WITH_EVIDENCE_LINKS

Recheck an updated proof commit before presenting a report as verification of that
version. A build, CI run or audit-script exit code alone does not establish a complete
proof. Keep proof source and large artifacts in the external proof/evidence repository.
Maintainers independently check the statement and reproduce verification before
acceptance, whether or not a self-check report is supplied.

## Attribution

- Mathematical solver(s) and contribution, if applicable: REPLACE_WITH_NAMES_AND_CONTRIBUTIONS
- Lean formalization author(s) and contribution, if applicable: REPLACE_WITH_NAMES_AND_CONTRIBUTIONS
- Independent verifier(s), if any: REPLACE_WITH_NAMES_AND_ROLES_OR_NONE
- Public authorship evidence (paper author list, author/project announcement, or another public attribution source): REPLACE_WITH_LINKS_AND_EXPLANATION

Distinguish the mathematical solver, Lean formalization author and independent
verifier. A repository owner or PR submitter is not automatically the solver.
Explain any mismatch between paper authors, repository accounts and proposed
credits. Do not include private identity documents or contact/payment information.

## Submission checklist

- [ ] I changed only solver attribution, Lean proof information or supporting sources in the relevant catalog.
- [ ] I supplied the evidence required for the type of change above.
- [ ] Any solution submitted for acceptance fully solves the original problem. Any submitted Lean proof is complete at the specified commit and does not depend on `sorry`, `admit` or added unproved assumptions, including placeholders in challenge files.
- [ ] For a Lean contribution, I identified the formal statement and proof entry, explained their correspondence to the original problem, and supplied reproduction commands and the target theorem's axiom audit.
- [ ] This PR contains no proof source files, archives, binaries or vendored dependencies.
- [ ] Any Lean reference identifies a commit contained in the named branch and the exact version for review.
- [ ] For a Lean submission, I am the contributor using my own GitHub account and original proof repository, not registering someone else's proof or a mirror on their behalf.

For unrelated corrections, use an issue.
