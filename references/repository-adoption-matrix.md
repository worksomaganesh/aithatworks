# External Repository Evaluation for AI That Works

**Purpose:** Re-evaluate the 22 repositories recorded in the TechEnigma / Creator-OS repository landscape specifically for AI That Works. This is an adoption decision register, not an installation list.

**Source register:** [TechEnigma repository landscape](https://github.com/worksomaganesh/techenigmastudios/blob/main/references/repository-landscape.md) and the more detailed [Creator-OS evaluated repository register](https://github.com/worksomaganesh/Creator-OS/blob/main/references/evaluated-repositories.md).

**Review limitation:** This AI That Works review reuses the existing documented repository inspections, architecture notes, licence findings, and dependencies in those registers. It is not a fresh clone, runtime test, complete dependency/security audit, legal opinion, or guarantee that upstream status has not changed. Recheck upstream source, current licence, model/asset terms, security, maintenance, platform rules, and commercial-use conditions before installing or reusing anything.

## Executive decision

### Most useful patterns for AI That Works
- **Vox Director:** staged creative pipeline, beat/scene planning, asset generation gates, and review checkpoints.
- **anything2explainer:** research → narration → storyboard → scenes → frame-level QA. Architecture reference only; do not reuse its non-commercial code/template for commercial work without permission.
- **Bang Motion:** style brief before code, continuous motion design, reusable scene patterns, deterministic browser-frame export.
- **diagram-design:** semantic-pattern-first diagrams, brand profiles, and HTML/SVG outputs.
- **Ghost Editor:** selected talking-head audio/caption/B-roll/export QA ideas; not the application to adopt on our Windows workflow.
- **LangChain Social Media Agent:** human-in-the-loop approval pattern only.

### Useful later, not launch dependencies
OpenSEO, WeKnora, VoiceStudio, OpenCreator, Podcastfy, OpenHiggsfield, paint-mv-skills, MotionClone.

### Do not adopt
OpenProject, InstaPy, GramAddict, Claudegram, Instagram scraper/InstaTouch, InstaLooter, instagrapi, FluxCD.

## Repository-by-repository decisions

| # | Repository | Existing review summary | AI That Works decision |
|---:|---|---|---|
| 1 | [wide-trace/open-higgsfield](https://github.com/wide-trace/open-higgsfield) | Multi-provider media studio with model catalog, provider adapters, run history, asset library, and retries. Licence was not located in the earlier review; separate generation provider credentials and storage dependency. | **Reference only / later.** The provider-catalog and asset-run history patterns may help if ATW eventually builds a multi-provider media console. It does not replace Google Flow or provide Flow access/credits. No code reuse until licence and security are verified. |
| 2 | [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) | Local-first speech studio with engine adapters, model management, batch jobs, transcription, voice design/cloning, API and MCP. Application is AGPL-3.0; model/weight terms are separate and the default OmniVoice weights were identified as non-commercial. | **Defer.** Flow audio likeness and a specialist hosted voice service are simpler for launch. Revisit only if local privacy, voice workflow control, or cost justifies it; verify every model's commercial licence and hardware needs. |
| 3 | [every-app/open-seo](https://github.com/every-app/open-seo) | MCP/skill interface for keyword research, competitor insights, rank tracking, backlinks, audits, and AI visibility; depends on separate paid DataForSEO/reseller access. | **Revisit after launch.** Could enhance search-demand research if manual Google Trends/YouTube/Google research becomes a bottleneck and data spend is justified. Not required for the initial five-source research system. |
| 4 | [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | RAG/knowledge platform with hybrid retrieval, citations, knowledge curation/versioning, MCP, RBAC, and tracing; multi-service deployment. | **Architecture reference; no deployment now.** Borrow source traceability, document versioning, citations, and access-control ideas for future business-assistant demonstrations. NotebookLM + Drive + GitHub are sufficient for the creator knowledge library. |
| 5 | [opf/openproject](https://github.com/opf/openproject) | Enterprise project/portfolio management, roadmaps, Gantt, task and time tracking; GPLv3 and substantial deployment overhead. | **Do not adopt.** Creator-OS already owns the shared content lifecycle and approvals. A second work-management control plane would add overhead without solving a specific gap. |
| 6 | [InstaPy/InstaPy](https://github.com/InstaPy/InstaPy) | Selenium-based Instagram likes, comments, and follows automation; documented account-ban history. | **Reject.** No engagement automation or growth bots. Use platform-native analytics and permitted workflows. |
| 7 | [GramAddict/bot](https://github.com/GramAddict/bot) | Android/ADB automation for likes, follows, comments, DMs, and scraping modes. | **Reject.** Creates platform/account risk and is not a legitimate audience-research strategy. |
| 8 | [karthiktadepalli1/claudegram](https://github.com/karthiktadepalli1/claudegram) | Claude-powered browser extension for AI-text detection; requires a separate Claude workflow and outputs heuristic classifications. | **Do not adopt.** AI-detector labels are not proof of authorship or quality. ATW needs evidence, editing standards, and human review rather than detector scores. |
| 9 | [drawrowfly/instagram-scraper](https://github.com/drawrowfly/instagram-scraper) | Unofficial Instagram scraping for posts, comments, likers, followers, and media; session/rate-limit/proxy handling appears in project documentation. | **Reject.** Do not scrape accounts, harvest followers/likers, bypass limits, or download third-party media. Use public manual research and official permitted APIs. |
| 10 | [althonos/InstaLooter](https://github.com/althonos/InstaLooter) | Legacy API-less Instagram media downloader; GPLv3+ and old Python compatibility targets. | **Reject.** No role in original ATW asset creation. Use owned, licensed, or generated assets. |
| 11 | [Alisa0808/vox-director](https://github.com/Alisa0808/vox-director) | Staged media-generation pipeline with topic/beat maps, visual keyframes, narration/captions, FFmpeg assembly, and approvals; depends on Atlas Cloud and other providers. | **Adopt workflow patterns, not its full stack.** Use gates between research, script, scene plan, avatar/voice, generated clips, assembly, and QA. Do not add Atlas Cloud just because it is in the reference. |
| 12 | [lintsinghua/paint-mv-skills](https://github.com/lintsinghua/paint-mv-skills) | Director/storyboard/animation/render skill separation, chapter decomposition, asset continuity, contact sheets, and resumable renders; music-video use case and an upstream engine without a declared licence. | **Borrow generic orchestration/QC only.** Chapter decomposition, stable asset IDs, contact sheets, and resumable render ideas are useful. Do not reuse the downloaded unlicensed PDoomVideo engine or music-video-specific assets. |
| 13 | [Vincentwei1021/anything2explainer](https://github.com/Vincentwei1021/anything2explainer) | Remotion/React/TypeScript explainer pipeline with source-backed research, narration timing, storyboard, scene components, parallel work, approval gates, and rendered-frame QA. Toolkit uses PolyForm Noncommercial. | **High-value architecture reference; no commercial code/template reuse without prior written permission.** Independently implement the general research → script → storyboard → production-plan → rendered scene → frame QA sequence for ATW. Avoid recreating its distinctive expression. |
| 14 | [bangtutorial/bang-motion](https://github.com/bangtutorial/bang-motion) | Motion-design skill for HTML/CSS/GSAP with a style brief, continuous visual worlds, explicit timeline, browser capture, and FFmpeg export; MIT. | **Adopt as a design reference.** Use its general motion principles for ATW workflow diagrams, product callouts, kinetic typography, and transitions, with an original ATW visual system. |
| 15 | [kurbaitaev/ghost-editor](https://github.com/kurbaitaev/ghost-editor) | Talking-head short-form editor with take selection, captions, B-roll, and QA. MIT, but its documented workflow is Mac-focused and has platform/tool assumptions. | **Borrow selected QA ideas only.** ATW is avatar-led, so audio, caption, B-roll and talking-head timing checks are relevant; do not adopt the app as-is on the current Windows setup. Test portable ideas independently. |
| 16 | [LPengYang/MotionClone](https://github.com/LPengYang/MotionClone) | Research motion-transfer implementation using Stable Diffusion 1.5/AnimateDiff and specialised checkpoints; top-level licence not located in the earlier review. | **Research only / not needed.** Flow and conventional motion graphics cover current requirements. Revisit only for a concrete motion-transfer use case after model and licence review. |
| 17 | [krillinai/OpenCreator](https://github.com/krillinai/OpenCreator) | Codex-native runtime/workspace with shared state, skills, MCP, approvals, and local execution; Apache-2.0. Substantial desktop/runtime project. | **Revisit later.** Study capability permissions, local workspace, run-state, and approval design if Creator-OS develops a runtime gap. Do not replace or duplicate Creator-OS now. |
| 18 | [fluxcd/flux2](https://github.com/fluxcd/flux2) | Kubernetes GitOps controllers and declarative cluster reconciliation; Apache-2.0. | **Not relevant now.** No ATW production requirement justifies Kubernetes or GitOps infrastructure. |
| 19 | [souzatharsis/podcastfy](https://github.com/souzatharsis/podcastfy) | Converts multimodal sources into multi-speaker AI audio conversations; Apache-2.0, but voice and model providers have separate costs/terms. | **Future repurposing experiment.** Consider only after a library of substantial long-form implementations exists and there is evidence of audience demand for audio. Not a launch dependency. |
| 20 | [langchain-ai/social-media-agent](https://github.com/langchain-ai/social-media-agent) | LangGraph workflow that drafts posts from a URL and uses an Agent Inbox for edit/accept/reject, with several external dependencies. | **Adopt human-approval pattern only.** Draft platform-specific packages and require manual approval. Do not install its entire dependency stack or automate posting/engagement at launch. |
| 21 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | Semantic-pattern-first diagram selection, brand profiles, and HTML/SVG output; MIT. | **Adopt as a primary diagram-design reference.** Use semantic patterns for workflow, architecture, decision, sequence, comparison, and data-flow diagrams. Create original assets using ATW brand rules once the visual identity is approved. |
| 22 | [subzeroid/instagrapi](https://github.com/subzeroid/instagrapi) | Unofficial Instagram private/mobile API wrapper with session, interaction, insight, DM, and upload capabilities; README warns private-API automation is fragile. | **Reject for ATW automation.** Do not store sessions/passwords or use private endpoints. Use official account-owned APIs where permitted and native platform tools otherwise. |

## Patterns to add to the AI That Works workflow

1. **Staged production and approvals:** inspired by Vox Director and the approval patterns in LangChain Social Media Agent. Research, workflow design, script, scene plan, first visual pilot, final export, and publishing each have a gate.
2. **Research-to-storyboard traceability:** inspired by the architecture of anything2explainer. Each narration segment and on-screen claim maps to a source or test evidence record.
3. **Provider-neutral media manifests:** informed by OpenHiggsfield. Record provider/model, generation ID where available, prompt, settings, credit/cost estimate, asset path, and QA result.
4. **Original motion system:** informed by Bang Motion. Define visual style before coding; use deliberate continuous motion and deterministic output where useful.
5. **Semantic workflow diagrams:** informed by diagram-design. Select diagram grammar based on meaning, then style it for ATW.
6. **Avatar/media quality checks:** borrow selected caption, audio, pacing, and B-roll QA ideas from Ghost Editor, independently implemented for Windows and our Flow/Resolve pipeline.
7. **Contact sheets and resumable production:** borrow generic chapter/asset continuity and render-review ideas from paint-mv-skills without using its unlicensed external engine.
8. **Source-grounded knowledge:** borrow WeKnora's traceability/versioning concepts without deploying a separate knowledge platform now.
9. **Human-approved publishing:** draft with AI if useful, but publish through native tools or approved official APIs after a human review.

## Adoption priority

| Priority | Pattern / project | Next action |
|---|---|---|
| P0 | Vox Director stage gates | Add to the episode production checklist |
| P0 | anything2explainer architecture | Define our own structured research/script/storyboard/QA handoff |
| P0 | diagram-design | Define an ATW diagram grammar and sample library |
| P0 | Bang Motion | Create original motion prototypes after ATW visual identity approval |
| P1 | Ghost Editor QA ideas | Add audio/caption/B-roll checks to the Resolve export checklist |
| P1 | Provider manifest | Add provider and asset metadata to the production manifest |
| P2 | OpenSEO | Reassess when search research scale or evidence gaps justify paid data |
| P2 | WeKnora / VoiceStudio / OpenCreator | Reassess only against an explicit documented requirement |
| P3 | Podcastfy / MotionClone / OpenHiggsfield | Future experiments, not core production |

## Licensing and safety rules

- A repository's software licence does not automatically cover models, checkpoints, datasets, fonts, music, templates, or third-party assets.
- Public visibility is not permission for commercial reuse.
- The earlier review identified PolyForm Noncommercial for anything2explainer; do not reuse its code/template for monetised work without the author's permission.
- The earlier review found no top-level licence for OpenHiggsfield and MotionClone and no declared licence for the downloaded PDoomVideo engine; do not treat them as reusable dependencies.
- VoiceStudio is AGPL-3.0 and individual speech models have separate terms; the previously reviewed default OmniVoice weights were marked non-commercial.
- Do not install scraping, private-API, engagement-bot, or account-growth automation tools.
- Re-check every upstream licence and security posture before adoption.

## Review status

This document recontextualises all 22 entries from the existing repository landscape for AI That Works. It does not assert that any repository has been installed, tested, or approved as a dependency. The first implementation should use the existing Google-first stack, OBS, DaVinci Resolve, Creator-OS shared conventions, and original ATW assets.
