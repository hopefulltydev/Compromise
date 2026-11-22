<div align="center">

# Compromise

[![CI](https://github.com/hopefulltydev/Compromise/actions/workflows/rust.yml/badge.svg)](https://github.com/hopefulltydev/Compromise/actions/workflows/rust.yml)
[![Discord](https://img.shields.io/discord/1543361023850053702.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/hopefullty)
[![License: GPL](https://img.shields.io/badge/License-GPLv3-yellow.svg)](https://opensource.org/licenses/gpl-3-0)

[Website](https://compromise.hopefullty.com/) • [Download](https://github.com/hopefulltydev/Compromise/releases/latest) • [Docs](https://compromise.hopefullty.com/docs) • [Discord](https://discord.gg/hopefullty) • [PumpkinMC](https://github.com/Pumpkin-MC/Pumpkin)

</div>

[Compromise](https://compromise.hopefullty.com/) is a Minecraft server based on PumpkinMC built entirely in Rust, offering a fast, efficient,
and customizable experience. It prioritizes performance and player enjoyment while adhering to the core mechanics of the game while support Legacy Console Edition clients, specializing in supporting [neoLegacy](https://neolegacy.dev/) Clients, LCE Revelations, and LCEMP. Compromise also supports Eaglercraft, Java, and Bedrock Clients. 
<div align="center">

![Pumpkin Chunk Loading](./assets/pumpkin-chunk-loading.webp)

</div>

> [!IMPORTANT]
> Compromise is currently under heavy development.
>
> Currently in Nightly Updates.

## Quick Start

Install on Linux / macOS:

```sh
curl -sSfL https://github.com/hopefulltydev/Compromise/releases/latest/install.sh | sh
```

Or grab a prebuilt binary from the [Download page](https://github.com/hopefulltydev/Compromise/releases/latest). See the [Quick Start guide](https://compromise.hopefullty.com/docs/#quick-start) and [Documentation](https://compromise.hopefullty.com/docs/) for setup details.

## Goals

- **Performance**: Leveraging multi-threading for maximum speed and efficiency.
- **Compatibility**: Supports the latest Java, Bedrock, Legacy Console Edition, and Eaglercraft Minecraft Clients while adhering to vanilla game mechanics.
- **Security**: Prioritizes security by preventing known security exploits.
- **Flexibility**: Highly configurable, with the ability to disable unnecessary features.
- **Extensibility**: Provides a foundation for plugin development.

## Features

- [x] Configuration (toml)
- [Tracking: Protocol](https://github.com/hopefulltydev/Compromise/issues/1)
  - [x] Server Status/Ping
  - [x] Encryption
  - [x] Packet Compression
  - [x] Java Edition
  - [x] Bedrock Edition (W.I.P)
  - [x] Legacy Console Edition
  - [x] Eaglercraft
  - ...
- [Tracking: World](https://github.com/hopefulltydev/Compromise/issues/2)
  - [x] Player Tab-list
  - [x] Scoreboard
  - [x] World Loading
  - [x] World Time
  - [x] World Borders
  - [x] World Saving
  - [x] Lighting
  - [x] Entity Spawning
  - [x] Bossbar
  - [x] Chunk Loading (Vanilla, Linear, Pump)
  - [Chunk Generation](https://github.com/Pumpkin-MC/Pumpkin/issues/36) (This leads you to PumpkinMC's Roadmap.)
  - [x] Chunk Saving (Vanilla, Linear, Pump)
  - [Redstone](https://github.com/Pumpkin-MC/Pumpkin/issues/1402) (This leads you to PumpkinMC's Roadmap.)
  - [x] Liquid Physics
  - ...
- [Tracking: Player](https://github.com/Pumpkin-MC/Pumpkin/issues/1405) (This leads you to PumpkinMC's Roadmap.)
  - [x] Skins
  - [x] Teleport
  - [x] Movement
  - [x] Animation
  - [x] Inventory
  - [Combat](https://github.com/hopefulltydev/Compromise/issues/3)
  - [x] Experience
  - [x] Hunger
  - [X] Off Hand
  - [X] Advancements (W.I.P)
  - [x] Eating
  - ...
- Entities
  - [x] Non-Living (Minecart, Eggs...) (W.I.P)
  - [x] Entity Effects
  - [x] Players
  - [x] Mobs (W.I.P)
  - [x] Animals (W.I.P)
  - [Entity AI](https://github.com/Pumpkin-MC/Pumpkin/issues/1406) (This leads you to PumpkinMC's Roadmap.)
  - [x] Boss (W.I.P)
  - [x] Villagers (W.I.P)
  - [X] Entity Saving
- Server
  - [Plugins](https://github.com/Pumpkin-MC/Pumpkin/issues/1407) (This leads you to PumpkinMC's Roadmap.)
  - [x] Query
  - [x] [Minecraft Server Management Protocol (MSMP)](https://minecraft.wiki/w/Minecraft_Server_Management_Protocol) (This leads you to Minecraft Wiki.)
  - [x] Inventories
  - [x] Particles
  - [x] Chat
  - [Commands](https://github.com/Pumpkin-MC/Pumpkin/issues/15) (This leads you to PumpkinMC's Roadmap.)
  - [x] Permissions
  - [x] Translations
- Proxy
  - [x] [BungeeCord](https://github.com/SpigotMC/BungeeCord) (This leads you to another GitHub Repository.)
  - [x] [BungeeGuard](https://github.com/lucko/BungeeGuard) (This leads you to another GitHub Repository.)
  - [x] [Velocity](https://github.com/PaperMC/Velocity) (This leads you to another GitHub Repository.)

<!-- Check out our [Github Project](https://github.com/orgs/Pumpkin-MC/projects/3) to see current progress. -->

## Contributions

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md)

## Communication

Consider joining [our Discord server](https://discord.gg/wT8XjrjKkf) to stay up-to-date on events, updates, and connect with other members.

## Funding

If you want to fund me and help the project, check out the [Donation Page](https://pumpkinmc.org/donate/).

## License & Attribution

* **Pumpkin Server**: Licensed under the [GNU General Public License v3.0 (GPLv3)](LICENSE).
* **Plugin API (`pumpkin-plugin-api` & `pumpkin-plugin-wit`)**: Dual-licensed under [MIT](crates/pumpkin-plugin-api/LICENSE-MIT) OR [Apache-2.0](crates/pumpkin-plugin-api/LICENSE-APACHE) for maximum flexibility when writing plugins.
* **Third-Party Assets & Data**: Bedrock mappings, protocol conversion data, and Minecraft assets are subject to their respective licenses and attribution terms. See [assets/NOTICE.md](assets/NOTICE.md) for full details.
