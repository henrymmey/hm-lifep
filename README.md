# HM Life+

A client-side Fabric modpack for Minecraft 26.2 focused on performance optimization, quality-of-life improvements, and visual enhancements. Managed with [packwiz](https://packwiz.tools/) and automatically published to [Modrinth](https://modrinth.com/).

## Features

- **Performance** — Sodium, Lithium, Iris, FerriteCore, C2ME, VMP, ImmediatelyFast, ModernFix, BadOptimizations, Entity/More Culling, and Bobby for distant-chunk caching
- **Visuals** — Complementary Reimagined/Unbound and MakeUp Ultra Fast shaders, Euphoria Patches, 3D skin layers, wavey capes, and custom green-ore resource packs
- **Quality of Life** — Zoomify, Dynamic Crosshair, dynamic FPS, Simple Voice Chat, Xaero's maps, AppleSkin, Jade, Better Advancements/Stats, mouse tweaks, shulker box tooltips, crafting tweaks, and Mod Menu integration
- **Utilities** — Litematica, MiniHUD, FreeCam, FreeLook, client sorting, command keys, and more
- **Privacy** — No Chat Reports
- **Cross-version support** — ViaFabricPlus

## Installation

Download the latest `.mrpack` from [Modrinth](https://modrinth.com/modpack/kUYTdD3h), then open it with the Modrinth App or any launcher that supports `.mrpack` files.

## Development

### Prerequisites

- [packwiz](https://packwiz.tools/) CLI

### Useful Commands

```sh
# Install a mod from Modrinth
packwiz modrinth add <mod-slug>

# Remove a mod
packwiz remove <mod-slug>

# Update all mods
packwiz update --all

# Export for distribution
packwiz modrinth export -o release.mrpack
```

### Project Structure

```
mods/            — Mod metadata (.pw.toml files)
resourcepacks/   — Resource pack metadata
shaderpacks/     — Shader pack metadata
config/          — Mod configuration files
pack.toml        — Modpack metadata (name, version, loaders)
```

## Release

Releases are built and published to Modrinth automatically via GitHub Actions (`.github/workflows/release.yml`) when a GitHub Release is published. The workflow exports the pack using `packwiz modrinth export` and uploads the resulting `.mrpack` to Modrinth, then attaches it to the GitHub Release.
