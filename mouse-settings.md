---
layout: default
title: Mouse Settings
parent: Controls & Sensitivity
nav_order: 2
---

# Mouse Settings

Mouse settings are where aim is actually made. The goal is a sensitivity
low enough for precision, high enough for fast turns — and then never
touching it again.

## DPI and in-game sensitivity

- Set the mouse's **hardware DPI** (in the driver software) — typically
  **800–1600 DPI** for PvP. Higher DPI + lower in-game sens usually gives
  cleaner sensor tracking.
- Set **in-game sensitivity** so a comfortable wrist+arm sweep does a
  ~180° turn. Write the number down; screenshot it.
- **eDPI** = DPI × in-game sensitivity. It's the number that matters —
  two players with the same eDPI have the same effective sensitivity.
  When comparing setups with others, compare eDPI, not DPI.

## Things that must be off

- **Mouse acceleration / pointer precision** (Windows "Enhance pointer
  precision" — disable it in Control Panel → Mouse).
- **In-game mouse smoothing** — check the mod/option exists and is off.
- Any driver-level "curve" or per-game sensitivity overrides.

## Polling rate & latency

- 1000 Hz is standard and fine.
- Higher polling (2K–8K) costs CPU for near-zero benefit in Minecraft;
  if your FPS dips on high polling, drop back to 1000 Hz.

## Testing & locking in

1. Play 3–4 sessions without changing anything.
2. Only if a setting is *clearly* wrong (constant over-flicking, can't
   track players), adjust in ~10% steps.
3. After every change, play at least a full session before judging it.
4. Once locked in: never change it. Sensitivity whiplash is the most common
   self-inflicted aim injury. If you must change, expect 1–2 weeks of
   adjustment.

## Consistency check

Your sensitivity should be identical in every instance (PvP, speedrun,
SMP). Prism lets you copy `options.txt` sensitivity between instances —
do that once, then forget sensitivity forever.
