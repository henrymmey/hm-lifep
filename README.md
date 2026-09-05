# HM Life+

[![Static Badge](https://img.shields.io/badge/GitHub-black?logo=github)](https://github.com/henrymmey)
[![Static Badge](https://img.shields.io/badge/Website-henrymeyer.de/gaming-green)](https://henrymeyer.de/gaming)

---

This modpack aims to make Survival Let's Plays and SMP server experiences more enjoyable. It offers significantly more improvements and features than the [HM Basic Play](https://modrinth.com/modpack/hm-basic-play) modpack.

This modpack may be restricted on some public servers due to mods like MouseTweaks or ClientSort. Use it at your own risk and stay informed about server rules.

---

## Features

* **Small performance Optimizations:** Built on the latest Fabric loader with essential mods like Sodium, Lithium, and FerriteCore for a smooth experience.
* **Quality of Life:** Enhancements like dynamic crosshairs, better UI handling, Freecam, and more.
* **Visual Improvements:** Includes Iris Shaders, EuphoriaPatches, and 3D Skin Layers for a modern and polished look.
* **Vanilla-Friendly:** Subtle gameplay changes that preserve the classic Minecraft feeling you know and love.

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

Create a release with proper Tags and Name. Everything should be published automatically.
