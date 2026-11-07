# Vertex

Vertex is a free main menu and in-game interface suite for Space Engineers, built as a plugin for CringeLauncher. It replaces the stock menus and HUD with a graphite, cyan and orange interface and adds a set of tools for mining, ship management and combat awareness.

## Requirements

Vertex only runs through CringeLauncher.

1. Join the Discord server: https://discord.gg/psbPvMjEhw
2. Get CringeLauncher from the server and install it.
3. Run Space Engineers through CringeLauncher at least once so its plugins folder exists.

Vertex replaces the main menu, so do not run it together with other main menu plugins (for example PBC.MainMenu or BHI.MainMenu). If another one is active, Vertex will not load.

## Installation

1. Download `Vertex.MainMenu.zip` from the latest release on this repository's Releases page.
2. Close Space Engineers and CringeLauncher.
3. Open the CringeLauncher plugins folder, normally `%APPDATA%\CringeLauncher\plugins`.
4. Create a folder named `Vertex.MainMenu` there and extract the contents of the zip into it, so that `Vertex.MainMenu.dll` and the `assets` folder sit directly inside it.
5. Start Space Engineers through CringeLauncher. The Vertex boot sequence and main menu should appear.

Open the settings with the gear button on the main menu or pause menu. Everything can be switched off individually there.

## Updating

Vertex checks this repository's latest release when the game starts. With automatic install on (Settings, Updates), a newer version is downloaded, verified against its checksum and applied; restart the game once to finish. You can also press Check now in the same section. To update by hand, replace the files in the `Vertex.MainMenu` folder with the new zip's contents.

## Features

**Menus and screens**
- Main menu with an animated deep space grid, boot sequence, last session card, dispatch panel and status bar
- Pause menu and loading screen in the same style
- Reskin of the options pages, terminal and G menu controls

**In-game HUD**
- Suit panel: energy, hydrogen, oxygen, health, food, radiation, backpack fill, broadcast state, helmet and air pressure
- Ship panel: speed, altitude, power, power use and time left on batteries, dampeners, hydrogen, cargo fill, and an optional fuel counter for uranium and hydrogen volume
- Planet compass with GPS markers, bracket crosshair, adjustable HUD scale
- G menu loadout planner: save the current toolbar as a loadout and apply it later (Ctrl+L in the G menu)

**Ore map and radar**
- Ore deposit log with bundling of nearby deposits, map and list views, ore filters and ETA
- Radar with an adjustable 1 to 5 km range, ship and station contacts, optional WeaponCore support
- Write the selected or all listed ores to GPS

**Ship tools**
- SIP hull integrity tracking with baseline or projector comparison and impact alerts
- Assembler quota that keeps component stock topped up while you are seated
- Refining calculator: ore to ingots, ingots to ore, yield modules and refining time
- Stopping distance indicator that warns when you cannot brake before an obstacle

**Hostile faction alert**
- Watches for hostile ships of a faction tag you choose
- Banner, world markers, screen edge pulse, radar markers, alarm sound, chat line and optional GPS points
- Retreat warning when a contact is much larger or a higher class than your ship

**Controls and settings**
- Collapsible, searchable settings sections
- Configurable keybinds for the ore map, radar range, GPS writing and more
- Everything is stored in `%APPDATA%\CringeLauncher\config\vertex-mainmenu.json`

## Chat commands

- `/ore` with status, show, hide, mode, next, prev, zoom, filter, gps
- `/sip` with status, baseline, forget, testalert
- `/pbcr` lists current hostile alert contacts

## Support

Questions and bug reports go to the Discord server above. When reporting a problem, include your Vertex version (shown in Settings) and the CringeLauncher log.
