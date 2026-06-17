# LTX-2.3 LoRA Library — Triggers, Weights & Stacks

**Tested on Pirate Diffusion / Graydient.ai and local ComfyUI.**

## General Rules
- Append to end of prompt: `<lora_name:weight> TRIGGER_WORDS`
- Sweet spot weights: **0.6 – 0.9**
- Max \~4-5 LoRAs stacked reliably
- Action/pose LoRAs first, then anatomy, then finishers

## Core LoRAs

### Realism + Action
- **dreamlay2-ltx23** (or similar)
  - Weight: 0.65 – 0.8
  - Triggers: `bl0wj0b`, `d0gg1e`, `c0wg1rl`, etc.

### Nudity + Anatomy
- **sexgod-ltx23-nudity-v2**
  - Weight: 0.7 – 0.85
  - Trigger: `LTXNUDES`

### Physics & Polish
- **ltx23-better-physics**
  - Weight: 0.65 – 0.8
  - Token: `BetterPhysics`

### Orgasm / Expression / Cum
- **org