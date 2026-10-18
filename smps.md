---
layout: default
title: SMPs
parent: Game Settings
nav_order: 3
---

# SMPs

Survival multiplayer is a different game: hours-long sessions, building,
farms, and exploring. Settings optimize comfort and view distance, not
raw latency.

## Video

| Setting | Value | Why |
|---------|-------|-----|
| Render distance | 12–16 (or server max) | View distance is the joy of SMPs |
| Entity distance | 100% | Mobs, items, animals matter |
| Graphics | Fancy is fine if FPS holds | You're not frame-starved here |
| Clouds | On if you like them | They cost little at these distances |
| Smooth lighting | Maximum | Looks matter in long builds |
| Max FPS | 60–120 cap | Frees the GPU for heat/noise; feels identical |

## Comfort

- **Music on, ambience on** — this is the mode where Minecraft's sound
  design pays off.
- GUI scale to taste; larger screens with builds benefit from 2.
- Keep shaders optional: enable for screenshots/tours, off for farm work.
  Even light shaders cut FPS on chunk-heavy farms.

## Performance for farms & chunk-heavy play

- Pre-generate the area around your base (server-side or client tools) —
  the biggest "SMP stutter" fix there is.
- Entity culling and FerriteCore-class mods matter more here than anywhere:
  farms hoard entities and items.
- If a farm tanks FPS, it's usually item entities: hopper/tuning fixes beat
  graphics tweaks.

## Social/QoL

- Keep a voice client (Discord etc.) with push-to-talk in full-duplex-free
  mode so farm AFK time doesn't spam your mic.
- Map/minimap mods are usually SMP-legal and save enormous navigation time —
  but confirm with the server's rules first.
