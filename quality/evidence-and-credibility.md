# Evidence, Credibility, Disclosure, and Rights

## Editorial standard

AI That Works must be more trustworthy than the average tool demonstration. Claims are limited to what was researched, built, observed, and measured.

## Evidence states

| State | Meaning | Permitted language |
|---|---|---|
| Concept | Proposed design; not built | "A possible design is..." |
| Controlled demo | Demonstrated in a bounded environment, often with synthetic data | "In this controlled demo..." |
| Tested workflow | Run against a documented test set with recorded outcomes | "We tested it against..." |
| Pilot | Used in a limited real-world setting with permission and oversight | "In this pilot..." |
| Operational deployment | Used repeatedly in a real workflow with monitoring, ownership, support, and controls | "This is operating in..." |
| Measured outcome | Baseline and post-change metrics collected with a documented method | State the exact measure, period, sample, and limitations |

Never upgrade a project to a higher state because the video looks polished.

## Claim and source register

For each important claim, record:
- Claim ID.
- Exact wording planned for narration or on-screen text.
- Claim type: fact, attributed statement, analysis, estimate, or scenario.
- Source ID and URL.
- Publisher/author and publication date.
- Access date.
- Supporting passage or data.
- Limitations and conflicting evidence.
- Reviewer and verification state.

Prefer primary sources for tool capabilities, model specifications, pricing, policies, and research claims. For consequential claims, seek independent corroboration.

## Test evidence

For each implementation:
- State the test objective and success criteria.
- Describe the test data and whether it is synthetic, anonymised, or authorised.
- Record inputs, outputs, errors, retries, and manual interventions.
- Capture model/provider/version and date where relevant.
- Record actual API calls and costs where measurable.
- Report sample size and conditions.
- Distinguish observed results from estimates.
- Preserve reproducible steps where feasible.
- Document failures and what was changed after testing.

Do not infer business ROI from a small controlled demo. Do not claim time saved without measuring a defensible baseline and including human review/maintenance time.

## AI avatar and synthetic media

- Use only the creator's own authorised likeness or a person's explicitly consented likeness.
- Follow provider consent and identity verification requirements.
- Do not present generated speech as a live recording.
- Use platform disclosure controls when required for realistic synthetic or altered media.
- Label illustrative generated footage when it could be mistaken for actual product operation or real events.
- Do not fabricate customer testimonials, endorsements, case studies, or business results.
- Keep the real product screen recording separate from synthetic B-roll.

## Privacy and security

- Prefer synthetic datasets for public demos.
- Obtain permission before using business or customer data.
- Remove or blur personal information, private messages, account identifiers, credentials, and confidential records.
- Do not expose API keys, cookies, access tokens, or admin URLs.
- Apply least privilege to integrations.
- Show human approval for consequential actions.
- Record data retention, deletion, and access assumptions.
- Do not publish an insecure demo just because it works.

## Rights and licensing

For every asset, record origin, creator/provider, licence or terms, permission, attribution requirements, and allowed commercial use. Check provider terms for generated avatar/voice assets and model outputs. A public GitHub repository does not automatically grant permission to reuse code, prompts, visual assets, or model weights.

## Publication blockers

Block publication when:
- A material claim has no reliable source.
- A result is fabricated or presented beyond the evidence state.
- Customer/private data or credentials are exposed.
- An asset lacks a clear rights basis.
- A synthetic depiction could materially mislead viewers and is not disclosed appropriately.
- The workflow's risks or limitations are materially concealed.
- The final human review has not been completed.

AI-generated fact checks are advisory. Human approval is mandatory.
