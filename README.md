# NetherGames Network - World & Map Assets

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.nethergames.org/img/logo/one-line-non-flush-light.png">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.nethergames.org/img/logo/one-line-non-flush-dark.png">
  <img alt="NetherGames" src="https://cdn.nethergames.org/img/logo/one-line-non-flush-dark.png" width="450">
</picture>

<br><br>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Plugins Repo](https://img.shields.io/badge/Plugins%20Repo-NetherGamesMC%2Fplugins-blue.svg)](https://github.com/NetherGamesMC/plugins)
[![Minecraft Bedrock](https://img.shields.io/badge/Minecraft%20Bedrock-v1.20.0--v1.26.30-brightgreen.svg)](https://minecraft.net)

**Official world maps, game arenas, waiting lobbies, and configuration data for the NetherGames Network.**

[Closure Announcement](https://support.nethergames.org/closure-announcement) • [Closure FAQ & Info](https://support.nethergames.org/closure-info) • [Plugins Repository](https://github.com/NetherGamesMC/plugins) • [License](LICENSE)

</div>

---

## About

This repository contains the complete collection of world files, custom maps, waiting lobbies, and arena coordinate configurations (`arenas.yml`) used across all minigames and lobbies on NetherGames.

Following the closure of the server on **June 28th, 2026**, these assets have been released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. Anyone is free to use, modify, and host these worlds for their own servers, matches, and events.

---

## Usage with NetherGames Plugins

These map assets are designed to work directly with the open-source plugins in the **[NetherGamesMC/plugins](https://github.com/NetherGamesMC/plugins)** repository.

When configuring server directories or running Docker containers, asset paths map to the following locations:

- **Hub Server**: `Lobby/worlds` -> `/home/worlds`
- **Minigame Arenas**: `<Game>/arenas` and `<Game>/arenas.yml` -> `/home/plugin_data/x<Game>/`
- **Waiting Lobbies**: `<Game>/WaitingLobby` -> `/home/worlds/Hub`

---

## License

All map and world assets in this repository are licensed under the **[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE)** license.

You are free to:
- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

Under the condition that you give appropriate credit to **NetherGames** and provide a link to the license.
