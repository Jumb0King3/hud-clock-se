# HUD Clock (Server Edition)

A server-installable build of [HUD Clock by Elocrypt](https://mods.vintagestory.at/hudclock). All credit for the mod goes to Elocrypt, so please follow and support the original.

**What's different in this edition**

- The original HUD Clock is client-side only, so a server can't push it to players. This edition is marked Client and Server side. Put it in your server's Mods folder, and players are prompted to download it automatically when they join.
- The mod only runs on players' PCs. On the server it loads but does nothing.
- The code is unchanged from HUD Clock 4.4.1. It has been checked against Vintage Story 1.22.7.

**Features (from the original)**

In-game time, date and season, temperature, wind, rainfall, temporal storm countdown, rift activity, room/cellar/greenhouse detection, land-claim owner and online players. Everything can be configured per player.

**Controls**

- Ctrl+U: toggle the HUD
- Shift+O: open settings
- Ctrl+I: toggle the storm HUD

**Important**

Players shouldn't also have the original HUD Clock in their own Mods folder, or it will load twice. Single-player users should download the original mod instead.

## Download

ModDB (1-click install): https://mods.vintagestory.at/hudclockserver

## Report a problem

Bugs and feature requests for the mod itself go to the [original page](https://mods.vintagestory.at/hudclock). For problems specific to this server edition, report them on the [Issues](../../issues) tab and include your game version, the mod version and your log. Security problems: see [SECURITY.md](SECURITY.md).

**Where to find your log**

The logs are in the Vintage Story data folder, in a folder called `Logs`:

| System | Data folder |
|---|---|
| Windows | `%appdata%\VintagestoryData` (paste that into the File Explorer address bar) |
| Linux | `~/.config/VintagestoryData` |
| Mac | `~/Library/Application Support/VintagestoryData` |

- **Playing on a server:** send `client-main.log` from your own game. If you run the server, also send `server-main.log` from the server's data folder.
- **Singleplayer:** `client-main.log` and `server-main.log` are both in the data folder above.
- Attach the file to the issue (drag it into the box), or paste just the lines with errors. Reproduce the problem first, then grab the log straight afterwards, so the error is near the end.
