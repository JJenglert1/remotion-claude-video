# WaveSpeed AI Skill Setup

WaveSpeed AI gives you one API endpoint for multiple AI services:
- **Nano Banano** — Fast image generation
- **Google Veo 3** — Video generation
- **ElevenLabs** — Voiceovers and text-to-speech

## Step 1: Get Your API Key

1. Go to [wavespeed.ai](https://wavespeed.ai)
2. Create an account
3. Navigate to API Keys in your dashboard
4. Generate a new API key
5. Copy and save it somewhere secure

## Step 2: Create the Skill

Open Claude Code and tell it:

```
I want you to create a new skill for WaveSpeed AI. This skill should allow you to:

1. Use Nano Banano for image generation
2. Use Google Veo 3 for video generation
3. Use ElevenLabs for voiceovers and text-to-speech

The skill should:
- Accept my API key as a parameter
- Have functions for each service (generate_image, generate_video, generate_voiceover)
- Save generated assets to my project's assets folder
- Work alongside the Remotion skill for video production

Create this skill and save it to my .claude/skills folder.
```

## Step 3: Configure Your API Key

When Claude creates the skill, it will ask for your API key. You can either:

**Option A: Set as environment variable (recommended)**
```bash
export WAVESPEED_API_KEY="your-api-key-here"
```

**Option B: Pass directly in prompts**
```
Using WaveSpeed with API key [your-key], generate an image of...
```

## Using the Skill

### Generate Images (Nano Banano)

```
Using WaveSpeed, generate an image: [describe what you want]
Save it to assets/images/
```

### Generate Video (Veo 3)

```
Using WaveSpeed, generate a 5-second video: [describe the scene]
Save it to assets/videos/
```

### Generate Voiceover (ElevenLabs)

```
Using WaveSpeed, generate a voiceover for this script:
"[Your script here]"
Use a voice that sounds like [describe: professional male, friendly female, etc.]
Save it to assets/audio/
```

## Combining with Remotion

The real power is using both skills together:

```
Create a motion graphics intro for my podcast:
1. Generate a dynamic background video using Veo 3 — abstract shapes with energy
2. Generate a voiceover saying "Welcome to [podcast name]"
3. Layer my logo (assets/logos/logo.png) on top with an animated reveal
4. Sync the voiceover to the animation
5. Render the final video
```

Claude will:
1. Call WaveSpeed to generate the background
2. Call WaveSpeed to generate the voiceover
3. Use Remotion to composite everything
4. Render your final video

## Troubleshooting

**"API key not found"**
- Make sure you've set your WAVESPEED_API_KEY environment variable
- Or pass it directly in your prompt

**"Rate limit exceeded"**
- WaveSpeed has usage limits based on your plan
- Check your dashboard for current usage

**"Generation failed"**
- Try simplifying your prompt
- Check WaveSpeed status page for outages

## Security Notes

- Never commit your API key to git
- Use environment variables for sensitive data
- The skill is configured to read from env vars by default
