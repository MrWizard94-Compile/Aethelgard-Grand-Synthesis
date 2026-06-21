# Aethelgard: The Grand Synthesis

> A cohesive kitchen-sink RPG that balances sprawling industrial automation, deep magical lore, and terrifying dungeon crawling — tied together by guided FTB Quests progression.

**Minecraft 1.20.1 · Forge 47.x · CurseForge-format modpack**

## Overview

| Spec | Detail |
|------|--------|
| Title | Aethelgard: The Grand Synthesis |
| Version | Minecraft 1.20.1 |
| Loader | Forge 47.x |
| Primary focus | Kitchen-sink / guided progression / RPG |
| Difficulty | Scaling — peaceful automation early, brutal boss encounters late |
| Pack version | 0.1.0 (foundation) |

The pack strikes a balance between industrial automation (Create → Mekanism → AE2), deep magic (Ars Nouveau, Iron's Spells, Botania), and dungeon crawling (Apotheosis, Cataclysm, Alex's Mobs), with FTB Quests as the connective tissue.

## Repository layout

| Path | Purpose |
|------|---------|
| `manifest/manifest.json` | CurseForge manifest (Forge 1.20.1). `files[]` resolved at packaging time. |
| `overrides/config/` | Pack configs (committed) |
| `overrides/mods/` | Local mod jars (gitignored; `.gitkeep` tracked) |
| `docs/CONCEPT.md` | Original design vision |
| `docs/MODLIST.md` | Curated, categorized mod roster + Forge 1.20.1 availability notes |

## Status

🌱 **Foundation scaffolded.** Directory structure, manifest, and curated mod roster are in place. Mod `files[]` are not yet resolved to CurseForge project/file IDs — see `docs/MODLIST.md` for the roster and availability flags.

## Building / CurseForge export

1. Drop mod jars into `overrides/mods/` to test in a local Forge 1.20.1 instance.
2. Resolve each mod's `projectID` / `fileID` into `manifest/manifest.json` `files[]`.
3. Zip `manifest.json` + `overrides/` per the CurseForge modpack spec; publish via the CurseForge author dashboard.

## Related

- [JanusPrime orchestration](https://github.com/MrWizard94-Compile/JanusPrime)
- Sibling concept packs: Aetheria, Aetherial Convergence, Chronicles of the Shattered Cosmos, Omniverse Odyssey
