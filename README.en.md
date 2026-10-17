# ETS2 CarPlay

[Deutsch](README.md) · **English**

An iOS 27 style CarPlay interface for the navigation display in **Euro Truck Simulator 2**: map with turn-by-turn guidance, Spotify, job, vehicle, speed cameras, phone and more – right on the screen in your truck, controlled by mouse, keyboard or phone.

![Dashboard](bilder/dashboard-dunkel.png)

> A fan project. Not affiliated with SCS Software, Apple, Google or Spotify. All trademarks belong to their owners.

---

## Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Requirements](#requirements)
- [Install](#install)
- [First start](#first-start)
- [In-game controls](#in-game-controls)
- [Map](#map)
- [Updates](#updates)
- [FAQ](#faq)
- [Uninstall](#uninstall)
- [Licenses and credits](#licenses-and-credits)

---

## Features

**Map and navigation**
- Own map built from the game files: roads, junctions, roundabouts, buildings, sea, rivers and lakes, forests, meadows, company, service and dealer sites, quarries
- Map styles like **Google Maps** or **Apple Maps**, light and dark; 2D or tilted 3D view; auto zoom by speed
- The route comes straight from the game (set a destination in the in-game navigation)
- Turn instructions with distance, direction, **lane guidance** and a “then …” hint; voice announcements in English or German
- **Traffic lights** along the route with phase and remaining time
- Speed limit and current speed, arrival time, time and distance left
- Fuel stations, rest areas, services, dealers, weigh stations, ferries and trains as map icons

**Speed cameras and warnings**
- Speed cameras, weigh stations and toll gates ahead, with warning tone and warning card
- Learns every camera that catches you, plus your own reports
- Over-speed warning (adjustable tolerance)

**Apps**
- **Spotify**: title, cover art and controls
- **Job**: route, deadline, time buffer, income, next break
- **Vehicle**: speed, gear, RPM, fuel, AdBlue, truck and trailer condition
- **Fuel & Rest**, **Logbook**, **Calendar**, **Weather**, **Phone**, **Messages** from the dispatcher, **Notifications**
- Fully customizable **dashboard** with widgets, own wallpapers and app icons

**Controls**
- **Touch mode** in the game: CarPlay as a movable window or **directly on the display in the cockpit**, compensating head and cab movement
- Hotkeys for all main functions
- **Phone control** over Wi-Fi, connected via QR code
- Editor window on the PC for setup

**General**
- English and German, metric, US and UK units, 12/24-hour clock
- Automatic updates; the app rebuilds the map data by itself after game updates
- The game stays untouched: no mods in the game files, no change to `config.cfg`

---

## Screenshots

| | |
|---|---|
| ![Navigation light](bilder/navi-hell.png) | ![Navigation dark](bilder/navi-dunkel.png) |
| Navigation in Google style, light | Navigation in Google style, dark |
| ![Dashboard light](bilder/dashboard-hell.png) | ![Home](bilder/home.png) |
| Dashboard with navigation and music widget | Home screen |
| ![Job](bilder/auftrag.png) | ![Vehicle](bilder/fahrzeug.png) |
| Job | Vehicle |
| ![Speed cameras](bilder/blitzer.png) | ![Settings](bilder/einstellungen.png) |
| Speed cameras | Settings |

Screenshots show the German interface; switch to English under Settings › General › Language.

---

## Requirements

- Windows 10 or 11 (64-bit)
- Euro Truck Simulator 2 (current version, Steam), DirectX 11
- About 350 MB of disk space

---

## Install

1. **Close** Euro Truck Simulator 2.
2. Download the latest version from [Releases](../../releases):
   - **`ETS2-CarPlay-Setup-<version>.exe`** – installer, choose any folder, listed under Windows “Apps”, or
   - **`ETS2-CarPlay-<version>.zip`** – portable: unzip and run `ETS2 CarPlay.exe`.
3. The app finds ETS2 via Steam and copies the plugin into the game (`bin\win_x64\plugins`) by itself.
   You can check it in the app under **Settings › General › Plugin & game**.

---

## First start

1. Start ETS2. On the first start the game asks about **SDK plugins** – confirm with **OK**.
   From now on the game starts the CarPlay app automatically.
2. Get into a truck with a navigation screen – CarPlay appears on the display.
3. Press **Ctrl + F8** to open the CarPlay menu in the game: choose screens (GPS, dashboard, custom) and press **Apply**.
4. For navigation, set a destination in the in-game navigation or take a job.

On the first start the app builds the map from your game files (one or two minutes, in the background).

---

## In-game controls

| Key | Function |
|---|---|
| **Ctrl + F8** | CarPlay menu in the game (screens, touch, status) |
| **Ctrl + Alt + M** | Touch mode on/off – use CarPlay with the mouse |
| **Ctrl + Alt + E** | Editor window on the PC (dashboard, widgets, settings) |
| **Ctrl + Alt + P** | Music: play/pause |
| **Ctrl + Alt + Page Up / Page Down** | Music: previous/next track |
| **Ctrl + Alt + arrow keys, Enter, Backspace** | Move through CarPlay, select, back |
| **Ctrl + Alt + H** | Home screen |

All hotkeys can be changed in the app or the menu.

**Touch mode**
- **Window**: CarPlay as a window in the game, free to move and resize.
- **On the display**: calibrate once (click the four corners of the display in the cockpit), then click directly on the screen in the truck. Head and cab movement is compensated.
- The bar at the top can be set to **always**, **small** (just a dot, expands on hover) or **hidden**.

**Phone control**: turn it on in the settings and scan the QR code with your phone (same Wi-Fi).

---

## Map

The map is built from your game files – including all DLCs you own – and rebuilt automatically after game updates.

- **Layers** (each can be turned off): buildings, water, forests, meadows & bushes, company sites & quarries, company names, traffic lights, road numbers, scenery roads
- **Water** comes from the game itself (rivers, lakes, harbours, sea surfaces); the open sea from Natural Earth, fitted to the game's coastlines.
- **Scenery roads**: roads the game hides on its own map and that are not connected to the road network – can be shown dashed.

Note: ETS2 compresses Europe a lot (e.g. Dover and Calais are only a few kilometres apart). The map shows the world **as it is in the game**.

---

## Updates

The app checks for a new version once a day (**Settings › General › Software update**), downloads it and installs it when you quit – plugin included. Your settings are kept. Every download is verified with SHA-256 before installing.

---

## FAQ

**Windows shows a warning (“Windows protected your PC”).**
The program is not digitally signed (yet), so Windows SmartScreen does not know the publisher. Click **More info › Run anyway**.
To check that the file is unchanged, compare it with `SHA256SUMS.txt` from the release. In PowerShell:

```powershell
Get-FileHash .\ETS2-CarPlay-Setup-1.4.0.exe -Algorithm SHA256
```

**CarPlay does not appear in the game.**
Fully close ETS2 and start it again, confirm the SDK prompt. Check **Settings › General › Plugin & game** in the app. In the game, press **Ctrl + F8**, choose the screen and press **Apply**.

**The map is empty or outdated.**
**Settings › Info › Rebuild map**. This happens automatically after game updates.

**Does it cost performance?**
The app only redraws when something changes and transfers the image via the GPU. On typical gaming PCs there is no noticeable difference.

**Does it work with American Truck Simulator?**
No, only with Euro Truck Simulator 2.

---

## Uninstall

- Via Windows **Settings › Apps** (installer version), or
- in the app: **Settings › General › Uninstall ETS2 CarPlay**, or
- `Deinstallieren.cmd` in the program folder (ZIP version).

This removes the plugin from the game, the placeholders in `Documents\Euro Truck Simulator 2\ETS2CarPlay` and the program folder – optionally also the settings (`%APPDATA%\ETS2 CarPlay`). The game itself stays unchanged.

---

## Licenses and credits

- Parts of the game plugin come from the [ETS2LA plugin](https://github.com/ETS2LA/plugin) (MIT).
- Map data is read from the game files with the [TruckSim map parser](https://github.com/truckermudgeon/maps) (GPL-3.0); the source is included in every package (`resources/mapdata/parser/QUELLE.txt`).
- Sea areas: [Natural Earth](https://www.naturalearthdata.com/) (public domain).
- Font: [Inter](https://github.com/rsms/inter) (SIL Open Font License 1.1).
- Interface built with [Electron](https://www.electronjs.org/).
