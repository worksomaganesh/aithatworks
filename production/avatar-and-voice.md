# Avatar and Voice Standard

## Decision

AI That Works is **AI-avatar-led**. The recurring presenter is the creator's own authorised digital likeness. The creator does not need to appear physically on camera in every video.

The avatar establishes continuity and presenter identity. It must not replace the real workflow demonstration, screen capture, test evidence, diagrams, or limitations.

## Provider order

1. **Google Flow avatar:** first option to create and test the digital twin.
2. **Creator-recorded voice:** default fallback and source of authentic narration.
3. **Flow audio likeness:** use only when pronunciation, pacing, and delivery pass quality review.
4. **ElevenLabs:** optional voice specialist when a controlled benchmark demonstrates material improvement.
5. **HeyGen:** optional avatar specialist when presenter continuity, long-form script delivery, or lip-sync quality is materially better than Flow.

Do not subscribe to ElevenLabs and HeyGen automatically. Test the same script, language, framing, and intended delivery in the available systems. Compare output quality, editing effort, cost, generation limits, rights, and repeatability before deciding.

## Digital identity capture

Use only the creator's own likeness or a person who has explicitly authorised the intended use.

Capture checklist:
- Clean, quiet recording space.
- Stable camera at eye level.
- Even front lighting; avoid strong backlight.
- Neutral, uncluttered background.
- Face clearly visible and unobstructed.
- Natural speech and facial movement.
- Follow the avatar provider's exact capture and consent instructions.
- Retain the provider's terms and consent record for the creation date.

Do not use another person's face or voice without explicit informed permission. Do not imply endorsement by another person.

## Avatar quality evaluation

Generate the same controlled test passage in several shots. Score each dimension from 1 to 5 and record examples.

| Dimension | What to inspect |
|---|---|
| Identity consistency | Face resemblance, stability between generations, unwanted drift |
| Lip synchronization | Timing and mouth shape relative to spoken words |
| Voice fidelity | Familiarity, pronunciation, tone, and absence of artefacts |
| Delivery | Natural pacing, pauses, emphasis, and conversational rhythm |
| Expression | Credible facial expression and appropriate emotional range |
| Gesture | Natural movement; no distracting or exaggerated gestures |
| Visual integrity | No distortion, flicker, asymmetry, or background instability |
| Repeatability | Quality remains acceptable across multiple clips |
| Workflow cost | Credits, generation retries, editing time, and total cost |

The result must be good enough for the intended shot. A provider feature being available does not guarantee every generated clip has perfect lip sync or supports an uninterrupted long script.

## Presenter usage rules

- Use the avatar for the hook, context, important explanations, transitions, and conclusion.
- Use screen recordings for actual product actions and proof.
- Use architecture diagrams when relationships or data flow need explanation.
- Use generated B-roll only when it adds meaning or visual continuity.
- Avoid continuous avatar talking-head footage when the viewer would benefit more from a demonstration.
- Keep framing, wardrobe style, studio setting, lighting, and presenter tone consistent.
- The avatar may be expressive, but the brand should remain practical and credible rather than theatrical.

## Voice strategy

### Primary: creator's own voice
Record the creator's natural voice for important claims, nuanced explanations, opinions, and conclusions. A clean recording is preferable to an unnatural synthetic delivery.

### Secondary: approved digital-twin voice
Use the Flow audio likeness where quality, language, pronunciation, and generation controls are adequate.

### Specialist: ElevenLabs
Consider when voice cloning or expressive narration solves a demonstrated requirement. Verify commercial rights, voice-consent rules, language support, plan limits, and generated-audio terms at the time of use.

### Voice recording checklist
- Record in a quiet, acoustically controlled environment.
- Keep microphone distance and gain consistent.
- Avoid clipping, room echo, keyboard noise, and excessive noise reduction.
- Preserve a clean master before processing.
- Check names, product terms, numbers, and acronyms manually.
- Listen to the complete final mix, not only a short sample.

## Disclosure and trust

Use platform disclosure tools when required for realistic synthetic or altered media. Do not imply that an avatar recording is a live recording. Be transparent when the nature of the presentation could materially mislead viewers.

## Versioning and asset record

For every voice/avatar asset, record:
- Content ID and asset ID.
- Provider and product/model.
- Voice/avatar identity used.
- Language and script version.
- Generation date and relevant plan/terms snapshot.
- Consent/ownership basis.
- Prompt and settings.
- QA status and reviewer.
- Corrections or known artefacts.

Keep raw capture files and generated media in controlled media storage, not Git.
