# AI That Works — Creator Operations Dashboard

## Purpose

The dashboard is the operating view for AI That Works. Creator-OS remains the shared system architecture; this document defines the brand-specific views and metrics.

Initial implementation: Google Sheets + Google Drive + GitHub. Do not build a custom dashboard application until the spreadsheet workflow is stable and a specific limitation is documented.

## Dashboard modules

1. **Executive Overview:** this week's priorities, active content, publishing status, key metrics, production blockers, and next decisions.
2. **Research Radar:** demand signals, search terms, community problems, primary sources, and research freshness.
3. **Competitor Intelligence:** inspected videos, creators, upload dates, views, comments, coverage depth, and evidence-backed gaps.
4. **Opportunity Engine:** factor ratings, weighted score, risk deduction, decision, and next validation.
5. **Content Pipeline:** content IDs, stage, owner, due date, current blocker, and next action.
6. **Production Assets:** script, storyboard, avatar/voice, screen recordings, B-roll, prompts, source media, and asset manifest.
7. **Publishing Calendar:** channel, format, title, publication target, status, platform package, and final URL.
8. **Analytics:** reach, retention, engagement, subscriber/follower conversion, and useful audience actions.
9. **Experiment Log:** hypothesis, variable, sample, observation, limitation, and decision.
10. **Business Tracker:** lead source, problem, fit, stage, proposal, revenue, costs, and support burden.
11. **Knowledge/Prompt Library:** approved workflows, source packs, prompts, checklists, and reusable implementation notes.

## Suggested workbook tabs

| Tab | Purpose |
|---|---|
| Overview | Executive summary and weekly decisions |
| Demand Radar | Trend and search evidence |
| Competitors | Video and channel audit records |
| Pain Library | Public community questions and workflow pain |
| Opportunities | Weighted scores and decisions |
| Content Pipeline | Production lifecycle and blockers |
| Publishing Calendar | Platform-specific release plan |
| Asset Register | Media metadata, rights, provider, and location |
| Analytics | Per-content, per-platform performance |
| Experiments | Hypotheses and lessons |
| Leads & Offers | Qualified business interest and offer validation |
| Costs | Subscription, API, generation, storage, and production costs |

## Core identifiers

- Content ID: ATW-YYYY-NNN.
- Opportunity ID: OPP-YYYY-NNN.
- Research source ID: SRC-YYYY-NNN.
- Asset ID: ATW-YYYY-NNN-ASSET-NNN.
- Experiment ID: EXP-YYYY-NNN.
- Lead ID: LEAD-YYYY-NNN.

Every platform derivative must link to one content ID. A separate platform row is required for each published destination.

## Content pipeline states

Inbox → Problem Research → Validating → Workflow Design → Prototype → Testing → Evidence Review → Briefed → Writing → Ready for Production → Producing → Review → Scheduled → Published → Analysed → Archived.

Only move forward when the relevant gate is satisfied. Reopen an earlier stage when new evidence invalidates an assumption.

## Minimum opportunity record fields

Opportunity ID, date, topic, audience, problem, current alternative, geography, search evidence, community evidence, competitor URLs, gap statement, proposed demo, testability, risk, six factor ratings, risk deduction, score, decision, next action, and review date.

## Minimum content record fields

Content ID, working title, pillar, audience, problem, promise, opportunity ID, format, status, owner, due date, research brief, source map, workflow specification, test record, script, storyboard, asset manifest, final export location, QA result, platform URLs, analytics review, and learnings.

## Opportunity score formula

For each factor rated 1–5:

Weighted points = factor rating ÷ 5 × factor weight.

Final score = sum of weighted points − risk deduction.

Weights:
- Audience demand: 20
- Problem intensity: 20
- Supply gap: 20
- Proof potential: 15
- Monetisation potential: 15
- Production feasibility: 10

## Analytics fields

Store each metric with:
- Content ID.
- Platform.
- Measurement date.
- Publish date.
- Metric name and value.
- Reporting window.
- Source (native platform analytics or manual entry).
- Sample/context notes.
- Interpretation and confidence.

Track:
- Reach and impressions.
- Views and engaged views where defined by the platform.
- CTR where available.
- First 30-second retention and retention curve.
- Average view duration and percentage viewed.
- Shorts viewed versus swiped away.
- Likes, comments, shares, saves.
- Subscribers/followers gained.
- Returning viewers where available.
- Profile visits, resource clicks, opt-ins, qualified enquiries.

Metric definitions vary between platforms. Never combine unlike metrics into one total without explaining the calculation.

## Business metrics

Lead quality, source, use case, business size/context, urgency, decision-maker, fit, stage, proposal amount, implementation effort, actual cost, recurring revenue, gross margin, support hours, renewal/churn, and customer outcome evidence.

Do not store unnecessary personal or sensitive customer data in the workbook. Restrict access and use a separate secure system for confidential client records.

## Dashboard review rhythm

- Daily/production session: blockers and next actions.
- Weekly: publishing, research backlog, and audience feedback.
- Monthly: opportunity scores, content mix, production efficiency, costs, and business signals.
- Quarterly: positioning and business model review.

## Dashboard design rule

The overview should answer five questions immediately:
1. What are we trying to publish next?
2. What is currently blocked?
3. Which problems have the strongest evidence?
4. What have viewers found useful?
5. What should we do differently next week?

Do not optimise the dashboard for visual decoration. It must help make a decision.
