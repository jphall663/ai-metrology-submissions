# Content standards

## Scientific grounding & evidence *(where most submissions fall short)*

- [ ] I cite **1–2 references that are about the metric itself**, not just the general topic.
- [ ] The references are specific and ideally peer-reviewed papers (or an official NIST resource).
- [ ] I am **not** citing a governance framework (e.g., the AI RMF) as the metric's reference. Governance frameworks are for mapping, not grounding.
- [ ] My implementation resources point to something usable today — released software, a published dataset, or code already merged into an open-source repository — not an unmerged or draft pull request.
- [ ] The implementation resources actually support calculating the metric, at least indirectly.
- [ ] I have clicked every link to confirm that none are broken, moved, or redirecting.

## AI RMF alignment & metadata

- [ ] All mandatory metadata fields are filled in. See the current [`SUBMISSION_FORMAT.md`](SUBMISSION_FORMAT.md) for the mandatory metadata keys.
- [ ] I have mapped the metric to the correct AI RMF Trustworthy Characteristic(s).
- [ ] I have mapped the metric to the correct Lifecycle Stage(s).

## Usage guidance & utility

- [ ] My submission is written in English. 
- [ ] My **definition is concise**. I have removed explanation that is not needed to understand or apply the metric.
- [ ] I provide clear, actionable guidance on how to apply and interpret the metric.
- [ ] I state explicit scope boundaries, including where the metric does and does not apply.
- [ ] The metric adds value beyond what is already in the [Metrology Center](airc.nist.gov/metrology).

---

## Readiness estimate

Count your unchecked items. These map approximately to the outcomes reviewers apply (**Accept / Revise / Reject**):

- **All checked** → reviewers would likely rate all dimensions Sufficient → **Accept**. Likely ready to submit.
- **A few unchecked, all fixable** → likely at least one Partial, none Insufficient → **Revise**. Address them, then submit.
- **Missing references, no merged implementation, or out of scope** → likely an Insufficient dimension → **Reject**. Fix before submitting; these are the issues most likely to get a PR closed.

*This is your own estimate. The reviewers' evaluation and the approver's decision on the PR are what determine acceptance.*

---

## Using an LLM to help prepare a submission

Your own review is what matters most, and an LLM review is **not a substitute** for a careful manual self-check.

- **Verify everything it says.** LLMs can miss real problems and invent ones that are not there, especially for references. Treat the output as a second opinion to check, not a verdict.
- **Confirm every citation and link yourself.** LLMs can fabricate references or misjudge whether a source actually supports the metric. You are responsible for the accuracy of what you submit.
- **Do not paste anything non-public.** Your submission and all review discussion are public; do not post information from an organization-internal LLM resource here; do not put proprietary or confidential material into a public LLM for this submission process. 
- **A green light from an LLM is not approval.** Only the reviewers and approver decide. Passing an LLM check does not change the bar you will be held to.
