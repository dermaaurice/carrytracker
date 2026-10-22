# Carry Tracker

**Automatically count your Hypixel SkyBlock slayer carries and show every client's progress in a clean, customizable HUD.**

[![Download on Modrinth](https://img.shields.io/badge/Download-Modrinth-1bd96a?style=for-the-badge)](https://modrinth.com/mod/carrytracker)

Carry Tracker is a client-side Fabric mod for people who run slayer carries for other players. Instead of keeping score in your head or in a notepad, the mod counts each finished boss for you and shows the progress of every client on screen.

> This repository is only used as an issue tracker. The source code is not public.

## Features

- **Automatic counting**: Carry Tracker counts a carry when a client's slayer boss is killed. Supports Revenant Horror, Tarantula Broodfather, Sven Packmaster, Voidgloom Seraph, Inferno Demonlord and Riftstalker Bloodfiend.
- **Per-client HUD**: One card per client with their head, name, one dot per carry (progress bar for large amounts), and a big `done/total` counter. The card lights up briefly when a carry is counted and turns orange when the client is finished.
- **Drag and drop HUD**: Move the HUD anywhere with `/carry move`. It snaps to the screen edges and center.
- **Finish notification**: When a client is done you get a title and a clickable `[Remove]` button in chat.
- **Sound feedback**: A ping for every counted carry and a level-up sound for the last one. Can be turned off.
- **Optional client messages**: Can send your client a progress message like `Name: 3/10` after each carry. Off by default.
- **Optional `!left` command**: A client can type `!left` in party chat and you automatically answer with their remaining carries. On by default, can be turned off.
- **Smart name handling**: Autocomplete for player names from the tab list, and names copied from chat (with ranks, heads and color codes) work too.
- **Safe saving**: Your data is saved after every change in a background thread, with an automatic backup if the file is ever damaged.
- **Lightweight**: Built to be cheap on performance.
- **Languages**: Available in English and German. The mod automatically uses your Minecraft game language.

## Commands

| Command | What it does |
|---|---|
| `/carry` | Show the list of clients |
| `/carry add <name> [amount]` | Add a client, or raise their goal |
| `/carry set <name> <count>` | Set a client's current count |
| `/carry remove <name>` | Remove a client |
| `/carry move` | Drag the HUD (ESC saves, right click resets) |
| `/carry hud` | Turn the HUD on or off |
| `/carry sound` | Turn the sounds on or off |
| `/carry msg` | Turn progress messages to clients on or off |
| `/carry left` | Turn the `!left` party reply on or off |

## Requirements

- Minecraft 26.1.2
- [Fabric Loader](https://fabricmc.net/) 0.19.5 or newer
- [Fabric API](https://modrinth.com/mod/fabric-api)
- Java 25
- Client-side only: install it on your own client, no server installation needed

## Important notes

- This mod is **not** affiliated with or endorsed by Hypixel Inc. or Mojang. Hypixel only allows certain kinds of modifications, and a carry tracker is not explicitly listed. Use it at your own risk and check Hypixel's current rules if you are unsure.

## Reporting a bug

Open a new issue in the [Issues](../../issues) tab and include:

- What you expected to happen and what happened instead
- Your Minecraft version and mod version
- Steps to reproduce the problem
- Your `latest.log` if the game crashed or showed an error

## Suggestions and questions

Have an idea for a feature? Open an issue and describe it. For quick questions, join the Discord server linked on the Modrinth page.

## License

Copyright (c) 2026 CtrlShiftRun. All rights reserved.
