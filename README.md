# Remotion + Claude Code Starter Kit

Create videos programmatically with Claude Code. No timeline editor. No After Effects. Just prompts.

## Quick Start (Under 10 Minutes)

### Step 1: Get Claude Code Desktop

Download the Claude desktop app from [claude.ai](https://claude.ai). You get Claude Code built in — no terminal required.

### Step 2: Install the Remotion Skill

Open Claude Code in this project folder and tell it:

```
Help me install this skill: https://github.com/remotion-dev/remotion-claude-code-skill
```

Approve the terminal commands when prompted. That's it — Remotion is ready.

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
├── skills/
│   └── wavespeed-ai/        # Instructions to create the WaveSpeed skill
│       └── SETUP.md
└── assets/                  # Put your brand assets here
    ├── logos/
    ├── fonts/
    └── images/
```

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

1. **Plan your scenes first** — Use ChatGPT to break down your video into scene-by-scene prompts
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

- [Remotion Skill Repository](https://github.com/remotion-dev/remotion-claude-code-skill)
- [Remotion Documentation](https://remotion.dev)
- [Claude Code](https://claude.ai)

---

Built by [@JJEnglert](https://twitter.com/JJEnglert)
