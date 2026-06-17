# LTX-2.3 Parameter & Workflow Cheatsheet

## Core Commands

**Image-to-Video (recommended):**
`/wf /run:animate-ltx23 [prompt] /length:XXX /fps:24`

**Extend:**
Reply to a video → `/wf /run:extend-ltx23 [prompt] /length:XXX`

**Upscale:**
Reply to final video → `/wf /run:video-upscale`

## Recommended Starting Parameters

| Use Case           | Length   | FPS |
|--------------------|----------|-----|
| Quick tests        | 89-105   | 24  |
| Standard           | 120-137  | 24  |
| Erotic / detailed  | 105-121  | 24  |
| Final delivery     | Short base → upscale | 24 |

## LoRA Stacking Order (General Rule)

1. Action / Pose LoRAs first
2. Anatomy / Nudity
3. Physics & Polish
4. Finishers & Expression
5. Helpers last

Start weights at 0.65–0.75.

## Pro Workflow Pattern

1. Strong reference image
2. I2V generation
3. Multiple short tests → pick best
4. Extend chain
5. Final upscale + optional audio

Update this file with any new discoveries.