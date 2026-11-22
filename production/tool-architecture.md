# Production Tool Architecture

## Design principle

Google AI Pro is our initial production infrastructure, not a claim that every department is solved by one subscription. Use Google products first where they meet the quality bar. Add specialist software only when a demonstrated limitation justifies it.

Tool access, model availability, Flow credits, API quotas, commercial-use terms, and pricing change. Verify them in the relevant product account and current official documentation before production. Do not hard-code monthly credit counts or assume subscription access makes API use unlimited.

## Department map

| Department | Primary tool | Role | Status / rule |
|---|---|---|---|
| Research | Gemini Deep Research, Google Trends, YouTube/Google Search, Reddit | Discover business problems, demand, competitors, official capabilities, and evidence | Core |
| Knowledge | NotebookLM, Google Drive, Docs, GitHub | Organise source-grounded research, project records, workflow specs, and production journals | Core |
| Scripting | Gemini, Google Docs | Briefs, narrative, presenter script, screen-recording plan, short-form adaptations | Core; script after prototype evidence |
| Avatar | Google Flow personal avatar | Recurring digital-twin presenter using the creator's own authorised likeness | First system to test |
| Video | Google Flow / Veo | Supporting generated scenes, B-roll, and visual metaphors | Selective; not the source of truth for product demos |
| Images | Nano Banana Pro | Original supporting visuals, thumbnail concepts, infographics, scene assets | Core where useful; verify every factual diagram |
| Voice | Creator-recorded voice and approved Flow audio likeness | Presenter narration and consistent spoken identity | Default; quality-test first |
| Voice specialist | ElevenLabs | Higher control over voice cloning, expressive narration, or language-specific voice work | Optional paid specialist; adopt only after comparison |
| Avatar specialist | HeyGen | Script-driven presenter production or digital-twin capabilities when Flow is insufficient | Optional paid specialist; same-script benchmark required |
| Screen recording | OBS Studio | Real UI/product demonstrations, workflow evidence, coding and browser capture | Core; free |
| Editing | DaVinci Resolve | Editorial assembly, pacing, audio, captions, finishing, exports | Primary finishing editor |
| Thumbnails | Nano Banana Pro + Canva | Image concepts, typography, layout, variants, platform packaging | Core |
| Publishing | YouTube Studio, LinkedIn native tools, Meta Business Suite | Human-reviewed upload, scheduling, descriptions, captions, and platform-native publishing | Core; human approved |
| Distribution | Platform-specific edits and content packages | Adapt one verified story into distinct platform formats | Core; no engagement bots |
| Analytics | YouTube Studio, native LinkedIn/Instagram insights, Google Sheets | Measure reach, retention, engagement, qualified interest, and learning | Core |

## Google AI Pro as the initial backbone

Use the subscription as a coordinated set of capabilities:

- **Gemini:** research synthesis, ideation, reasoning, script drafting, review, and structured analysis.
- **Deep Research:** multi-source investigations and market/problem research. Verify primary evidence independently.
- **NotebookLM:** source-grounded analysis of approved documents, product documentation, research reports, and project notes.
- **Google Flow / Veo:** personal avatar experiments and generated supporting footage when a shot benefits from it.
- **Nano Banana Pro:** original image assets, thumbnail concepts, diagrams, and visual explanations.
- **Google Docs:** briefs, scripts, research memos, and review records.
- **Google Sheets:** opportunity scoring, competitor tracking, publishing calendar, budget, and analytics.
- **Google Drive:** source documents and large media storage, with an explicit folder and backup policy.
- **Google AI Studio:** optional API/model prototyping; API usage and billing are separate from consumer subscription entitlements where applicable.
- **Google Colab:** optional Python experiments and technical prototypes.
- **Google Antigravity:** optional development environment for building creator utilities and prototypes; it is not a publishing or media-management substitute.

NotebookLM is for grounded knowledge work, not a replacement for a primary-source audit. Gemini-generated summaries and scripts must be checked against source material.

## Core versus optional tool policy

### Core at launch
Google AI Pro products available in the user's account, OBS Studio, DaVinci Resolve, Canva, Google Sheets/Drive/Docs, GitHub, and native platform publishing tools.

### Optional after a measured need
ElevenLabs, HeyGen, paid SEO data services, additional video/image providers, specialist media orchestration, or a custom creator dashboard.

### Do not add yet
- A second project-management platform that duplicates Creator-OS.
- Multiple overlapping avatar or voice subscriptions without comparative tests.
- Unofficial Instagram automation/scraping packages.
- A self-hosted RAG platform solely to manage creator documents.
- Expensive orchestration software before the manual production workflow is stable.

## Asset and data boundaries

- Keep source citations and claim IDs with every material factual claim.
- Keep raw video, voice masters, Flow generations, proxies, cache, and finished exports outside ordinary Git history.
- Store small manifests, prompts, scripts, schemas, QA reports, and lightweight approved assets in Git.
- Keep API keys, authentication cookies, private messages, personal data, and customer records out of prompts, screenshots, and Git.
- Use synthetic or explicitly authorised test data for public demonstrations.

## Provider independence

Do not make the content workflow depend on one media provider. Record which provider/model generated an asset and keep replaceable input/output manifests. Flow is an asset-generation option; the actual workflow proof should come from screen capture, logs, test results, and reproducible documentation.
