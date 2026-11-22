# Market Intelligence and Opportunity Scoring

## Research objective

Find problems where:
- People or businesses have a real, repeated need.
- Existing solutions or explanations leave meaningful friction.
- AI is appropriate or worth testing against simpler alternatives.
- We can build and demonstrate a credible implementation.
- The result can create audience value and a possible business path.

We are not trying to find topics with the largest view counts. We are trying to find useful problems with evidence of demand and an explainable supply gap.

## Five primary research sources

### 1. Google Trends
Use [Google Trends](https://trends.google.com/trends/) to compare topic interest by geography and time:
- Compare India and worldwide interest separately.
- Review the last 12 months for current movement and up to five years for longer-term direction.
- Compare related queries and rising topics.
- Record the search term, geography, date range, capture date, and observations.

**Interpretation rule:** Trends reports relative search interest, not absolute monthly search volume. A peak score is not a count of searches. Treat it as a comparative signal.

### 2. YouTube Search
Use [YouTube](https://www.youtube.com/) to inspect the current video supply:
- Search the exact problem and several natural variants.
- Review the first 20 relevant results, recording the date and search context.
- Capture title, creator, upload date, views, comments, format, demonstration depth, and unanswered questions.
- Compare views per day and, where possible, video performance against that creator's normal baseline.
- Identify whether the video proves a workflow or only describes a tool.

A high view count alone does not mean a topic is underserved.

### 3. Google Search
Use [Google Search](https://www.google.com/) to find:
- Autocomplete and People Also Ask questions.
- Practitioner articles, independent reviews, and case studies.
- Official product documentation, pricing, API references, and changelogs.
- Repeated complaints, implementation barriers, and non-AI alternatives.
- Evidence that a claimed business problem is material.

Prefer primary documentation for product capabilities, pricing, and limitations.

### 4. Reddit and practitioner communities
Use [Reddit](https://www.reddit.com/) and relevant public communities to discover:
- Repeated questions and unresolved problems.
- Failed attempts and workarounds.
- Objections about reliability, cost, privacy, and setup.
- The words people actually use to describe their pain.
- What a useful outcome would look like.

Communities are qualitative discovery sources, not representative market surveys. Do not infer market size from votes or a small number of comments. Do not scrape private data, harvest personal information, or download other creators' media.

### 5. YouTube Studio
Use [YouTube Studio](https://studio.youtube.com/) after the channel starts publishing:
- Trends tab and available search insights.
- Impressions and click-through rate.
- First 30-second retention and audience-retention graph.
- Average view duration and average percentage viewed.
- Shorts viewed versus swiped away and engaged views.
- Returning viewers and subscribers gained.
- Search terms, comments, and recurring follow-up questions.

Before the channel has sufficient data, mark this source as **not yet available**. Do not fabricate Studio insights. As data accumulates, use our own audience response to reprioritise the backlog.

## Competitive gap analysis

For each shortlisted topic:
1. Search the exact viewer question, not only a generic keyword.
2. Inspect up to 20 relevant videos and record their upload dates.
3. Note the creator's channel size or normal baseline when available.
4. Score coverage depth: concept only, tool walkthrough, partial workflow, end-to-end implementation, or tested deployment.
5. Record what is missing: data flow, integrations, error handling, human approvals, cost, security, maintenance, reproducibility, or proof.
6. Identify comments that reveal confusion or unmet questions.
7. Write a precise gap statement, for example: "Existing results show an AI reply demo, but do not demonstrate consent, CRM handoff, duplicate detection, failure recovery, or operating cost."

The gap statement must be supported by inspected examples. Do not claim that no one covers a topic without a sufficiently broad review.

## Opportunity scoring model

Rate each factor from 1 to 5. Convert the rating into weighted points.

| Factor | Weight | A high rating means |
|---|---:|---|
| Audience demand | 20 | Multiple credible search/community signals or strong first-party interest |
| Problem intensity | 20 | Frequent, costly, slow, risky, or frustrating problem |
| Supply gap | 20 | Existing content leaves important implementation questions unanswered |
| Proof potential | 15 | We can build, test, and show a credible result |
| Monetisation potential | 15 | A plausible path to a useful resource, service, or product exists |
| Production feasibility | 10 | We can make the content with available time, tools, skills, and budget |

**Formula**

Opportunity score = sum of (factor rating ÷ 5 × factor weight) − risk deduction.

Apply a separate risk deduction of 0–10 points for unresolved rights, privacy, safety, reliability, evidence, or production risks. Do not use this penalty to hide a low factor score.

### Decision bands

| Final score | Decision |
|---:|---|
| 80–100 | Prioritise for build and production |
| 70–79 | Strong candidate; validate with a prototype |
| 60–69 | Small test, short-form experiment, or more research |
| Below 60 | Hold or reject |

Scores are decision aids, not objective market facts. Record the evidence and rationale behind each rating.

## Research record fields

Every opportunity record should contain:
- Opportunity ID and date.
- Topic and exact audience question.
- Primary audience and workflow context.
- Problem statement and current alternative.
- Evidence links from each available source.
- Competitor videos and coverage-depth notes.
- Supply-gap statement.
- Proposed implementation and proof plan.
- Six factor ratings, weighted score, and risk deduction.
- Decision, owner, next action, and review date.

## Validation rules

- Separate measured evidence from assumptions and estimates.
- Use more than one independent source for high-impact demand claims.
- Interview or observe real workflow owners before claiming willingness to pay.
- Check whether a non-AI or simpler automation is better.
- Verify tool capabilities, pricing, permissions, and model terms at production time.
- Re-score an idea when material new evidence appears.

## Working research tools

Google Trends, YouTube Search, Google Search, Reddit/public practitioner communities, YouTube Studio, Gemini Deep Research, NotebookLM, Google Sheets, and source-backed research briefs. Additional paid SEO data services are not required for the initial launch.
