---
layout: default
title: PvP Settings
parent: Game Settings
nav_order: 1
---

# PvP Settings

PvP settings optimize three things: reading the fight, hitting your
inputs, and keeping frametimes flat. Everything else is cosmetic.

## Video

| Setting | Value | Why |
|---------|-------|-----|
| Graphics | Fast | Fewer distractions, higher FPS |
| Render distance | 8–12 | Servers cap it anyway; less to render |
| Entity distance | 75–100% | Keep players visible, drop the rest |
| Sim distance | Low as allowed | Less ticking overhead |
| Max FPS | Uncapped or ~1.2× refresh | Input latency drops with FPS |
| GUI Scale | 2–3 (preference) | Read HUD at a glance |
| Fullscreen | On | Lowest input latency |
| VSync | Off | VSync adds input lag |
| Bobbing | Off | Stable view |
| Clouds / particles | Minimal | Cheap, and particles get noisy in fights |

FOV: 90–110 (quirk preference). Wider FOV trades peripheral awareness for
target size — pick one and never change it mid-practice.

## Controls

- Mouse smoothing off, raw input on where the mod/option exists.
- Sensitivity fixed and written down (see [Mouse Settings](mouse-settings.html)).
- Hotbar reachable keys — see [Keybinds](keybinds.html).

## Network / game rules

- Sound: keep block-hit and bow sounds on; they're part of your timing.
- Turn music off; ambience off if it masks footsteps.
- Enable hit-delay/attack-indicator options that give clearer feedback.
- In-game name tags on, always.

## Frame discipline

- Cap FPS just above your monitor's needs, not to a round number.
- Watch frametimes, not FPS, when tuning (F3 or a HUD mod).
- If FPS tanks on a specific server, cut entity distance first — servers
  with many players or entities are the usual culprit.
