---
layout: default
title: Mod Launchers
parent: Minecraft Modifications
nav_order: 1
---

# Mod Launchers

A launcher manages your modded instances — separate Minecraft installs with
their own mods, settings, and versions. Don't mod the vanilla launcher's
install directly; you'll lose track of what changed.

## Recommended: Prism Launcher

**[Download from prismlauncher.org](https://prismlauncher.org/download/)** —
use **x86-64 → Installer (.exe)** on newer Windows systems.

Prism is the community standard:

- Unlimited instances, each with its own mods, resource packs, and settings
- One-click Modrinth/CurseForge mod downloads with dependency resolution
- Java version management per instance
- Instance import/export — share a pack as a zip

## Setup basics

1. Install Prism and let it find or download the right Java.
2. Create an instance for each target version (e.g. one 1.20.1 performance
   pack, one 1.21.11 PvP pack).
3. Install your modloader — **Fabric** for performance and PvP stacks.
4. Add mods via **Add Content → Modrinth**, so updates are one click.

## Others, for completeness

- **Official launcher** — fine for vanilla, poor for mods.
- **MultiMC forks** — Prism is the actively maintained one; the rest are
  forks of forks.
- **Modrinth App / CurseForge App** — fine for one-click pack installs,
  less control per instance than Prism.

## Rules that save headaches

- One instance per purpose. Never mix a speedrunning pack and a PvP pack.
- When a mod update breaks something, roll back that mod — don't update
  everything at once.
- Keep a plain vanilla-ish instance around for testing suspicious servers.
