---
name: ozor-video-best-practices
description: "Expert guide for crafting high-quality video prompts for Ozor.ai, the AI video generation platform. Use this skill whenever the user mentions Ozor, wants to create a launch video, product demo, feature announcement, explainer video, social ad, release notes video, investor update, tutorial, or any marketing video. Also trigger when the user asks for help writing video prompts, improving video output, structuring video scenes, choosing video formats, or wants best practices for AI video creation. Trigger on phrases like 'make a video', 'create a launch video', 'video for my product', 'Ozor prompt', 'video best practices', 'explainer video', 'product demo video', 'social clip', 'announcement video', or any request involving short-form video content for products and marketing."
---

# Ozor Video Best Practices

A comprehensive guide to creating outstanding AI-generated videos with Ozor.ai. This skill encodes the principles, patterns, and prompt formulas that consistently produce professional results — so you spend fewer credits and get better output on the first try.

## What Ozor Is

Ozor is an AI video agent that turns text prompts (or uploaded documents) into fully produced, animated videos. It renders each scene as an animated React component at 30 FPS, supports real-time preview, and exports to MP4 at 720p, 1080p, or 4K. It's designed for product launches, marketing, and explainers — not talking-head or long-form content.

Key capabilities:
- Text-to-video from a single prompt
- Document-to-video from PDFs, PowerPoints, images, Google Docs, and URLs
- Brand Kit extraction from your website (logo, colors, fonts)
- Scene-by-scene editing and regeneration
- Templates for common use cases
- Landscape (16:9) and portrait (9:16) formats

## The Prompt Quality Principle

The single biggest factor in Ozor output quality is the prompt. A vague prompt forces the AI to guess — and its guesses will be generic. A specific prompt gives it constraints to work within, which is where creativity happens.

Every effective Ozor prompt answers five questions:
1. **What** — the topic, product, or message
2. **Who** — the target audience
3. **How long** — duration or scene count
4. **What it looks like** — visual style, colors, mood
5. **What it should do** — the goal (launch, explain, sell, update)

## Prompt Formulas

These are copy-and-customize templates. Replace `[brackets]` with specifics.

### Product Launch
```
Create a [duration] product launch video for [product name].
Scenes: (1) Hook — one-line problem statement, (2) Solution — show the product in action, (3) Key benefits — 3 bullet points, (4) CTA — [your call to action].
Style: [minimal / bold / dark / light]. Brand colors: [colors]. Target audience: [who].
```

### Social Short (Vertical)
```
Create a 15-second vertical video (9:16) for [platform].
Scene 1: Bold hook — "[attention-grabbing statement]".
Scene 2: Proof or punchline — [what makes it believable or interesting].
Style: [energetic / calm / funny]. Use large text and minimal background.
```

### Feature Announcement
```
Make a [duration] video announcing [feature name] for [product].
Explain the problem it solves in one sentence. Show how it works visually. Close with a short CTA.
Keep the tone [professional / casual / excited]. Use [brand color] as the primary accent.
```

### Explainer / How It Works
```
Create a step-by-step explainer for [topic or process].
Break it into [N] scenes, one step per scene. Number each step clearly.
Audience: [who this is for]. Tone: [simple and clear / technical / conversational].
Use a [light / dark] background with [color] accents.
```

### Release Notes
```
Create a release notes video for [product name] version [X.X].
One scene per feature: [feature 1], [feature 2], [feature 3].
Keep each scene to a single idea with minimal text. Close with "Try it now" CTA.
Style: [clean / playful / technical]. Duration: ~[N] seconds.
```

### Investor Update
```
Create a [duration] investor update video for [company name].
Scenes: (1) Headline metric — [e.g., MRR, users, growth %], (2) Key milestone — [what happened], (3) Product update — [what shipped], (4) Roadmap — [what's next], (5) Ask or CTA.
Tone: confident and data-driven. Style: professional, dark background, clean typography.
```

### Tutorial / Walkthrough
```
Create a step-by-step tutorial for [task or feature].
[N] scenes, one step per scene. Number each step clearly.
Use "Next:" transitions between scenes. Include annotated screenshots where possible.
Audience: [who]. Tone: [friendly / technical / conversational].
```

## Scene Structure Principles

Think in scenes, not paragraphs. Every scene should have one job:

- **Hook** — grab attention in the first 2 seconds (especially for social)
- **Problem** — state the pain point the audience recognizes
- **Solution** — show your product or concept in action
- **Proof** — metrics, testimonials, before/after, social proof
- **CTA** — tell them exactly what to do next

The classic flow that works for almost any video: **Intro → Problem → Solution → CTA**

For longer videos, extend the middle: **Intro → Problem → Solution → Benefits → Proof → CTA**

Scene count guidelines by use case:
- Social ads: 2–3 scenes
- Product launches: 4–5 scenes
- Explainers: 5–7 scenes
- Investor updates: 5–6 scenes
- Release notes: 1 scene per feature
- Tutorials: 1 scene per step

## Format Selection

Choose before you start — changing aspect ratio later regenerates all scenes.

**Landscape (16:9)** — 1920×1080px
Best for: YouTube, LinkedIn, website embeds, presentations, investor decks, webinars, conference screens.

**Portrait (9:16)** — 1080×1920px
Best for: Instagram Reels & Stories, TikTok, YouTube Shorts, Pinterest video pins, Snapchat.

Rule of thumb: if it's going on a phone feed, go portrait. If it's going on a screen or webpage, go landscape.

## Brand Consistency

Set up a Brand Kit before creating videos. Ozor can auto-extract brand assets from your URL (logo, colors, fonts). Once set, every video inherits them automatically.

Upload assets *before* writing your prompt — the AI can only use what's already available. Reference uploaded assets by name in your prompt: "use the product screenshot I uploaded."

## Editing Workflow

Ozor is conversational — you refine by chatting, not by dragging timelines.

The most effective editing pattern:
1. **Start broad** — get the structure and flow right first
2. **Target one scene at a time** — click the scene thumbnail, then ask for changes
3. **One change per message** — stacked requests lead to mixed results
4. **Ask for alternatives** — "give me 3 headline options for this scene"
5. **Save what works** — save good scenes as templates for reuse

Useful editor commands:
- `"Edit scene 2 to..."` — target a specific scene
- `"Add a new scene after scene 3"` — insert at a position
- `"Make the text larger in scene 1"` — adjust visual details
- `"Change the color palette to..."` — restyle the whole video
- `"Regenerate scene 2"` — redo one scene, keep the rest
- `"Make this scene shorter"` — trim duration
- `"Save this as a template"` — reuse later
- `"Export at 1080p"` — trigger export

## Common Mistakes to Avoid

1. **Being too vague** — "make a cool video" gives generic results. Always specify duration, audience, style, and scene structure.
2. **Not targeting a scene** — click the scene thumbnail before asking for changes, otherwise the AI may regenerate the whole video.
3. **Uploading assets after the prompt** — upload images and brand assets first, then reference them.
4. **Requesting too many changes at once** — one change per message. Get the text right, then refine animation.
5. **Skipping the Brand Kit** — set it once, benefit forever.
6. **Wrong aspect ratio** — pick 16:9 or 9:16 at the start. Changing later means regenerating everything.

## Export Reference

| Quality | Available on | Best for |
|---------|-------------|----------|
| 720p | Free | Drafts, previews, internal sharing |
| 1080p | Pro ($29/mo) | Social media, landing pages, presentations |
| 4K | Business ($69/mo) | Conference screens, broadcast, premium campaigns |

Exports render server-side in 2–5 minutes depending on length and complexity.

## When Helping Users Write Ozor Prompts

When a user asks for help creating a video with Ozor, follow this process:

1. **Clarify the use case** — what type of video? (launch, explainer, social ad, etc.)
2. **Identify the audience** — who will watch this?
3. **Determine the format** — landscape or portrait? What platform?
4. **Draft a structured prompt** using the appropriate formula above
5. **Include specific visual direction** — colors, style, mood, background
6. **Suggest a scene count** based on the use case guidelines
7. **Remind about Brand Kit and assets** — upload before prompting

Always produce a complete, copy-pasteable prompt the user can drop directly into Ozor. Don't give abstract advice — give them the actual prompt text.

## Example: From Vague to Great

**User says:** "I need a video for my app"

**You produce:**
```
Create a 45-second launch video for [App Name], a [one-line description].
4 scenes:
(1) Hook — "[pain point the audience feels]"
(2) Solution — show the app's main screen with [key feature] in action
(3) Benefits — 3 short bullet points: [benefit 1], [benefit 2], [benefit 3]
(4) CTA — "Try it free at [url]"

Style: dark background, clean typography, [brand color] accents.
Audience: [target audience].
Tone: confident and modern.
```

Then ask the user to fill in the brackets — or help them fill them in based on what you know about their product.
