# Remotion + Claude Code Starter Kit

Create videos programmatically with Claude Code. No timeline editor. No After Effects. Just prompts.

**Watch the full tutorial:** [https://youtu.be/jGDy7NlRhxs](https://youtu.be/jGDy7NlRhxs)

## Quick Start (Under 10 Minutes)

### Step 1: Get Claude Code Desktop

Download the Claude desktop app from [claude.ai](https://claude.ai). You get Claude Code built in — no terminal required.

### Step 2: Skills are Already Included

When you clone this repo, three powerful skills are pre-installed and automatically loaded by Claude Code:

- **Remotion Best Practices** — Video creation expertise with 30+ rules for animations, audio, captions, and more
- **UI/UX Pro Max** — 50+ design styles, 97 color palettes, 57 font pairings for professional visuals
- **Copywriting** — Conversion-focused copy principles for compelling video text and CTAs

### Step 3: Create Your First Video

Tell Claude:

```
Using the Remotion skill, create a 10-second intro video with animated text that says "Hello World" with a gradient background.
```

Claude will set up the project, create the animation, and give you a localhost URL to preview.

## Folder Structure

```
remotion-starter-kit/
├── README.md                 # You're here
├── PROMPTS.md               # Copy-paste prompts for common workflows
├── .agents/
│   └── skills/
│       ├── remotion-best-practices/  # Remotion video creation skill
│       ├── ui-ux-pro-max/            # Design system & UI/UX skill
│       └── copywriting/              # Conversion copywriting skill
├── skills/
│   └── wavespeed-ai/        # Instructions to create the WaveSpeed skill
│       └── SETUP.md
└── assets/                  # Put your brand assets here
    ├── logos/
    ├── fonts/
    └── images/
```

## Included Skills

### Remotion Best Practices
The official Remotion skill from [remotion-dev/skills](https://github.com/remotion-dev/skills). Includes 30+ rules covering:
- Animations, transitions, and timing
- Audio, video, and image handling
- Captions and subtitles
- 3D content with Three.js
- Fonts and text measurement

### UI/UX Pro Max
Design intelligence from [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill). Includes:
- 50+ design styles
- 97 color palettes
- 57 font pairings
- 99 UX guidelines
- 25 chart types

### Copywriting
Conversion copywriting from [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills). Covers:
- Clear, compelling copy principles
- CTA best practices
- Page-specific guidance (landing pages, pricing, etc.)

## What You Can Build

- **Motion graphics** — Animated intros, outros, social clips
- **Auto-edited videos** — Pull best moments from long videos
- **Captioned content** — Word-by-word animated subtitles
- **Product videos** — Branded templates with your design system
- **AI-generated content** — Voiceovers, backgrounds, b-roll (with WaveSpeed skill)

## Adding WaveSpeed AI (Optional)

WaveSpeed gives you one API for:
- **Nano Banano** — Image generation
- **Google Veo 3** — Video generation
- **ElevenLabs** — Voiceovers

See `skills/wavespeed-ai/SETUP.md` for instructions.

## Tips

1. **Plan your scenes first** — Use Claude to break down your video into scene-by-scene prompts
2. **Iterate with screenshots** — When you see errors, screenshot and paste back to Claude
3. **Start simple** — Get one scene working before adding complexity
4. **Use your brand assets** — Point Claude at your `assets/` folder for consistent styling

## Prompts

See `PROMPTS.md` for ready-to-use prompts for:
- Motion graphics
- Video editing
- Reframing for different platforms
- Captions and subtitles
- Product videos
- AI-generated assets
- Voiceovers
- Full automation workflows

## Resources

- [Remotion Documentation](https://remotion.dev)
- [Claude Code](https://claude.ai)

---

## Want More?

- **[Join the Claude Code Community](https://claudecode.community?utm_source=github&utm_medium=repo&utm_campaign=remotion-starter)** — Connect with other builders
- **[Subscribe to Ultrathink Newsletter](https://www.tenex.co/ultrathink?utm_source=github&utm_medium=repo&utm_campaign=remotion-starter)** — Weekly AI insights
- **[Get a Free Tenex Audit](https://www.tenex.co/get-started?utm_source=github&utm_medium=repo&utm_campaign=remotion-starter)** — See how AI can 10x your workflow

---

Built by [@JJEnglert](https://twitter.com/JJEnglert)
