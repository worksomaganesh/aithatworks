# Editing and Visual Production Standard

## Editing philosophy

The video must show the work, not merely describe it. The AI avatar is the recurring presenter; the real workflow, actual interface, diagrams, and test evidence carry the explanation.

DaVinci Resolve is the primary finishing editor. OBS Studio captures real demonstrations. Google Flow generates selected supporting video. Remotion or original HTML/CSS/GSAP scenes may be introduced for repeatable motion graphics when the need justifies a code-based renderer.

## Long-form and short-form masters

Maintain clean masters for:
- **YouTube long-form:** 16:9, with resolution and frame rate chosen for the actual capture and delivery requirements.
- **Short-form:** 9:16, composed for mobile viewing and safe areas.
- **LinkedIn:** native video or document/carousel adapted to the professional insight.
- **Instagram:** vertical Reel and supporting carousel where useful.

Do not crop a single edit blindly into every aspect ratio. Prepare platform-specific framing and on-screen text.

## Recommended story allocation

The following is a starting editorial guide, not a rigid timing formula:
- Hook and problem: immediately establish the outcome or tension.
- Context: identify the workflow and audience.
- Presenter: explain decisions and transitions.
- Screen recording: demonstrate actual steps and product behaviour.
- Diagram/motion: explain architecture, sequence, or comparison.
- Test evidence: show normal and failure cases.
- Conclusion: state the result, limits, cost, and intended user.

Use the avatar as a guide through the story, not as a substitute for evidence.

## Editing rules

1. The first seconds must establish a meaningful problem, result, or question.
2. Remove dead air, repeated phrases, unnecessary intros, and filler.
3. Keep narration conversational and specific.
4. Use actual screen recordings for product behaviour and tested outputs.
5. Use B-roll only when it adds context, emotion, or clarity.
6. Use diagrams for system relationships and data flow; do not use decorative diagrams that add no information.
7. Use readable captions with accurate timing and safe margins.
8. Use consistent typography, colour roles, transitions, and sound identity after brand assets are approved.
9. Keep music below narration and use properly licensed or original audio.
10. Do not use flashy transitions to hide unclear explanation or weak evidence.
11. Show relevant errors, uncertainty, and human approval steps.
12. Avoid making every scene the same presenter shot or the same motion template.

## Screen recording standard

OBS Studio is the default desktop capture tool.

- Record at a consistent, suitable resolution and frame rate.
- Use a clean browser profile or test account.
- Close private notifications and unrelated tabs.
- Use synthetic or authorised data.
- Zoom to the relevant UI and move the pointer deliberately.
- Capture a clean take; keep a separate narration track when helpful.
- Record the exact application/model version and date for time-sensitive demos.
- Preserve source recordings until the final export passes QA.

For important implementations, capture the input, intermediate steps, output, errors, logs, and human review—not only the successful final result.

## Motion graphics

Motion should make the workflow easier to understand:
- Show the flow of information between components.
- Reveal a decision or approval gate when it occurs.
- Animate a metric only when it is tied to a measured source.
- Use consistent timing and meaningful movement.
- Keep small-screen readability in mind.
- Prefer reusable, deterministic compositions for repeated scenes.

A generated visual must not falsely depict an interface or capability as an actual product screen. Label illustrative visuals where needed.

## Audio and captions

- Listen to the complete mix on headphones and ordinary speakers.
- Check clipping, abrupt loudness changes, background noise, and music masking.
- Verify product names, numbers, acronyms, and technical terminology.
- Check automated captions against the final spoken track.
- Do not trust auto-captioning without review.
- Keep captions within platform safe areas and readable at phone size.

## Export and quality checklist

Before approval:
- Correct aspect ratio, dimensions, frame rate, and codec.
- No missing media, freeze frames, black frames, or corrupt sections.
- Audio and narration are intelligible and not clipped.
- Captions are synchronised and correctly spelled.
- On-screen claims match the evidence log.
- Screenshots do not reveal credentials, private data, or confidential records.
- Generated footage is not misrepresented as actual system operation.
- Avatar identity and lip sync are acceptable.
- Thumbnail/title accurately represent the video.
- Human editor approves the final master and platform files.

Keep source media, caches, proxies, and exports outside ordinary Git. Store manifests, edit notes, small approved templates, and QA records in the repository.
