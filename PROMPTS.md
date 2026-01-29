# Remotion + Claude Code Prompts

Copy, paste, customize. These are the exact prompts for common video workflows.

---

## Getting Started

### Install the Remotion Skill
```
Help me install this skill: https://github.com/remotion-dev/remotion-claude-code-skill
```

### Create Your First Scene
```
Using the Remotion skill, create this scene: [paste your scene description]
```

### Fix Errors
```
I'm seeing these errors. Please fix them.
[paste screenshot or error message]
```

---

## Motion Graphics

### Basic Motion Graphics
```
Using Remotion, create a [length] motion graphics video for [purpose].
Style: [describe].
Include: [elements].
End with [logo/CTA].
```

### Animated Intro
```
Create a 5-second animated intro with:
- My logo fading in from the center
- Subtle particle effects in the background
- Text that says "[tagline]" appearing below
- Smooth easing on all animations
```

### Social Media Clip
```
Create a 10-second vertical (9:16) clip for [platform] announcing [news/feature].
Use bold text animations.
Include our logo at the end.
Keep it punchy and high-energy.
```

---

## Video Editing

### Auto-Edit Long Video
```
I have a video at [path].
Edit it down to the [number] best moments.
Each clip should be [length].
Add captions styled like [description].
```

### Extract Best Moments
```
Review this transcript and identify the 5 most engaging moments.
These should be moments with strong hooks, insights, or emotional peaks.
[paste transcript]
```

### Create Clips from Transcript
```
Create clips of each of these moments. Each clip should be 30-60 seconds.
[paste moment timestamps]
```

---

## Reframing

### Horizontal to Vertical
```
Take this [16:9] video and reframe it for [9:16] vertical format.
Keep the subject centered.
Add [zoom/motion/ken burns] to keep it dynamic.
```

### Platform-Specific Reframe
```
Reframe this video for:
- TikTok (9:16)
- Instagram Reels (9:16)
- YouTube Shorts (9:16)
- Twitter/X (16:9 or 1:1)

Keep the main subject in frame at all times.
```

---

## Captions & Subtitles

### Basic Captions
```
Add captions to this video.
Style them like [describe — bold white text with black outline, etc].
Position them in the lower third of the frame.
```

### Animated Word-by-Word Captions
```
Add word-by-word animated captions that highlight each word in sync with the audio.
Use a bold, high-contrast style.
Colors: [highlight color] for active word, [base color] for other words.
```

### TikTok-Style Captions
```
Add TikTok-style captions:
- Large, bold text
- Center of screen
- Word-by-word highlight animation
- Slight bounce effect on each word
- High contrast colors
```

---

## Brand Assets & Templates

### Connect Design System
```
I have a project at [path] with my brand assets.
Review the design system — colors, fonts, logos — and create a motion graphics template that matches our brand.
```

### Product Video
```
Create a [length] product video for [product/feature].
Show the key benefit.
Use our brand assets from [path].
End with logo and CTA.
```

### Social Media Kit
```
Create a set of 5 social media clips (9:16 format) announcing [news/feature].
Each should be 10 seconds max.
Use our brand colors and logo.
Vary the animations so they're not repetitive.
```

---

## AI-Generated Assets (Requires WaveSpeed Skill)

### Generate Background
```
For this video, generate a background using [Veo 3/Nano Banano].
Prompt: [describe what you want].
Layer it behind the main content.
```

### Generate B-Roll
```
Generate 5 seconds of b-roll footage showing [description].
Style: [cinematic/abstract/minimal/energetic]
Save to assets folder.
```

### Generate Image Asset
```
Generate an image for this video:
[describe the image]
Dimensions: [width]x[height]
Style: [photorealistic/illustrated/minimal/etc]
```

---

## Voiceovers (Requires WaveSpeed Skill)

### Basic Voiceover
```
Generate a voiceover using ElevenLabs.
Script: [your script].
Voice: [description — professional male, friendly female, etc].
Add it to the video and sync with the visuals.
```

### Voiceover with Timing
```
Generate a voiceover for this script and sync it to the video:

[0:00] "Opening line here"
[0:03] "Second line here"
[0:07] "Third line here"

Use a [voice description] voice.
```

---

## Full Production Workflows

### Complete Video from Scratch
```
Create a complete video from scratch:
- Topic: [topic]
- Length: [length]
- Style: [description]
- Generate all assets with AI
- Add voiceover
- Render final output
```

### Podcast Intro
```
Create a motion graphics intro for my podcast:
1. Generate a dynamic background video using Veo 3 — something with abstract shapes and energy
2. Layer my logo on top with an animated reveal
3. Add a voiceover saying "Welcome to [podcast name]"
4. Duration: 5 seconds
5. Render at 1920x1080
```

### YouTube Video Package
```
Create a complete YouTube video package:
1. Intro (5 seconds) — Logo animation with sound
2. Lower third template — For my name/title
3. Outro (10 seconds) — Subscribe CTA with social links
4. Thumbnail template — Bold text, my face cutout area

Use my brand assets from [path].
```

---

## Scene Planning

### Generate Scene Breakdown
Use this prompt with Claude to plan your scenes:

```
Help me create prompts that I can use to create a video.
I want each prompt to be broken down by scene.

Context: [describe your video — what it's about, who it's for, the vibe you want]

I want you to return scenes outlined for a [length] video.
Keep it [tone — fun, professional, high energy, etc].

For each scene include:
- Duration
- Visual description
- Text/copy to display
- Animation style
- Transition to next scene
```

---

## Troubleshooting

### Preview Not Loading
```
The preview isn't loading. Check the terminal for errors and fix them.
```

### Animation Timing Off
```
The animation timing is off. Adjust the [element] to start at [time] and end at [time].
```

### Wrong Aspect Ratio
```
Change the video dimensions to [width]x[height] and adjust all elements to fit.
```

### Render Failed
```
The render failed with this error: [paste error]
Please fix and try again.
```

---

## Pro Tips

1. **Be specific about timing** — "fade in over 0.5 seconds" is better than "fade in"
2. **Reference existing styles** — "like Apple product videos" or "like TikTok trends"
3. **Iterate in small steps** — Get one thing working before adding more
4. **Use screenshots** — When something looks wrong, screenshot and paste to Claude
5. **Save working prompts** — When something works, save the exact prompt for reuse

---

Made with Claude Code + Remotion
