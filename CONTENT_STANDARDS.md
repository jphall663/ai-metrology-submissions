# Content standards for submitters and reviewers

## Scientific grounding & evidence *(where most submissions fall short)*

- [ ] **1–2 references are cited that are about the metric itself**, not just the general topic.
- [ ] The references are specific and ideally peer-reviewed papers (or an official NIST resource).
- [ ] The references are **not** a governance framework (e.g., the AI RMF); governance frameworks are for mapping, not grounding.
- [ ] The implementation resources point to something usable today: released software, a published dataset, or code already merged into an open-source repository, not an unmerged or draft pull request.
- [ ] The implementation resources actually support calculating the metric.
- [ ] Every link is confirmed; none are broken, moved, or redirecting.

## AI RMF alignment & metadata

- [ ] All required metadata fields are filled in. See the current [`SUBMISSION_FORMAT.md`](SUBMISSION_FORMAT.md) for the required metadata keys.
- [ ] The metric is mapped to the correct AI RMF Trustworthy Characteristic(s).
- [ ] The metric is mapped to the correct Lifecycle Stage(s).

## Usage guidance & utility

- [ ] The submission is written in English.
- [ ] The **definition is concise**. Explanation that is not needed to understand or apply the metric has been removed.
- [ ] Clear, actionable guidance is provided on how to apply and interpret the metric.
- [ ] Scope boundaries, including where the metric does and does not apply, are stated explicitly.
- [ ] The metric adds value beyond what is already in the [Metrology Center](https://airc.nist.gov/metrology/).

---

## Readiness estimate

Count the unchecked items. These map approximately to the outcomes reviewers apply (**Accept / Revise / Reject**):

- **All checked** → reviewers would likely rate all dimensions Sufficient → **Accept**. Likely ready to submit/approve.
- **A few unchecked, all fixable** → likely at least one Partial, none Insufficient → **Revise**. Address before submitting, or request revision if reviewing.
- **Missing references, no merged implementation, or out of scope** → likely an Insufficient dimension → **Reject**. Fix before submitting, or recommend closure if reviewing; these are the issues most likely to get a PR closed.

*This is an estimate. The reviewers' evaluation and the approver's decision on the PR are what determine acceptance.*

---

## Using an LLM to help prepare a submission

A submitter's own review is what matters most, and an LLM review is **not a substitute** for a careful manual self-check.

- **Verify everything an LLM says.** LLMs can miss real problems and invent ones that are not there, especially for references. Treat the output as a second opinion to check, not a verdict.
- **Confirm every citation and link.** LLMs can fabricate references or misjudge whether a source actually supports the metric. Submitters are responsible for the accuracy of what they submit.
- **Do not input anything non-public.** The submission and all review discussion are public; do not post information from an organization-internal LLM resource here; do not put proprietary or confidential material into a public LLM for this submission process.
- **A green light from an LLM is not approval.** Only the reviewers and approver decide. Passing an LLM check does not change the bar submitters will be held to.
