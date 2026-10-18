---
layout: default
title: Operating System
parent: Computer & Peripherals
nav_order: 5
permalink: /computer/os.html
---

# Operating System

Both Windows and Linux run modded Minecraft well in 2024+. Pick based on
what you need, not loyalty.

## Windows

- Broadest compatibility with launchers, mods, overlays, and anti-cheat on
  big multiplayer servers.
- Bloat is the main enemy: uninstall vendor bloatware, disable startup apps
  you don't need (Task Manager → Startup), and turn off Game Bar captures
  if you don't record (Settings → Gaming → Captures).
- Use "High performance" power plan on desktops; on laptops, plug in before
  playing — boost clocks collapse on battery.
- Keep the GPU driver current; Windows Update's driver is often months old.

## Linux

- Fully viable: Prism Launcher runs natively, and performance-focused
  distros (Bazzite, Nobara, CachyOS) ship gaming-tuned kernels and
  schedulers out of the box.
- Use the native Prism build, not the Flatpak inside a sandbox with
  restricted access, so file association and memory settings behave.
- Make sure the GPU driver stack is the distro's recommended one (Mesa for
  AMD/Intel, the vendor driver for NVIDIA) — most "Linux Minecraft stutter"
  is a driver issue, not a Minecraft issue.
- One caveat: some competitive servers' anti-cheat has poor Linux support.
  Check before committing to a server if you play daily on Linux.

## Either way

- Keep background sync clients (Drive, OneDrive, Dropbox) paused while
  playing — they spike disk and CPU mid-session.
- Fullscreen exclusive mode, always, for lowest input latency.
