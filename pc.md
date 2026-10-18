---
layout: default
title: PC
parent: Computer & Peripherals
nav_order: 1
---

# PC

Minecraft (even modded) is far more CPU-bound than GPU-bound. PvP servers
load hundreds of entities and particles, so single-core performance and
memory speed decide whether you get flat frametimes or stutter spikes.

## What actually matters

1. **CPU single-core speed** — Minecraft's main game loop is a single thread.
   A 6-core CPU with high boost clocks beats a 16-core with slow cores.
2. **RAM** — 16 GB is enough for most packs; 32 GB if you run big modpacks
   (Knighted, big performance+worldgen packs) or keep other apps open.
3. **GPU** — secondary. Any modern mid-range card renders vanilla easily;
   it only matters if you add shaders or want high resolution.
4. **SSD** — NVMe. World and chunk loading hangs on disk speed.

## Stable frametimes over raw FPS

A constant 240 FPS feels better than 400 FPS that swings 200–500. To get it:

- Cap your FPS slightly below your monitor's refresh rate (see
  [Monitor](monitor.html)).
- Close background apps that spike the CPU: browsers with many tabs,
  Discord hardware acceleration, RGB sync suites, game launchers.
- Update GPU drivers before tweaking anything else.
- In Prism Launcher, give the JVM 4–8 GB — more is not better; oversized
  heaps cause long garbage-collection pauses that show up as hitches.

## Quick health checklist

- Run games off an SSD, not a spinning drive.
- Keep at least ~15% of your disk free.
- Check thermals: sustained boost clocks need decent cooling; a throttling
  CPU is the most common cause of "random" FPS drops.
- Plug high-polling-rate mice into a motherboard USB port, not a hub.
