# LTX-2.3 Troubleshooting Guide

## Weak or Static Motion
- Lead with strong camera directives
- Add subtle continuous actions ("subtle breathing", "fabric shifting")
- Use BetterPhysics LoRA
- Use extend workflow instead of very long generations

## Prompt Not Followed
- Shorten prompt and focus on one main action + camera
- Use strong I2V reference image
- Reduce number of LoRAs stacked

## Anatomy / Quality Issues (NSFW)
- Use dedicated anatomy/pose LoRAs at good weights (0.65–0.85)
- Strong reference image + IC-LoRA
- Be explicit in prompt + use physics LoRAs
- Generate multiple short clips and pick the best

## LoRAs Ignored
- Check exact token name and syntax
- Lower weights of other LoRAs
- Make sure the LoRA is preloaded

## Audio Problems
- Explicitly describe sounds and dialogue in the prompt
- Use dedicated audio workflow after picture lock

## General Tips
- Always reply to the generation you want to improve
- Keep a log of what worked
- Test small changes one at a time

Add your own discoveries to this file over time.