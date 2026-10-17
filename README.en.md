# ETS2 CarPlay

[Deutsch](README.md) · English

A CarPlay interface for the navigation display in Euro Truck Simulator 2. The screen in your truck then shows a map with turn-by-turn directions, Spotify, radio, your job, truck data, speed camera warnings, a phone and a few more apps. You control it with the mouse, with hotkeys or from your phone.

![Dashboard](bilder/dashboard-dunkel.png)

Fan project, not affiliated with SCS Software, Apple, Google or Spotify. All trademarks belong to their owners.

## Contents

- [What it does](#what-it-does)
- [Screenshots](#screenshots)
- [Requirements](#requirements)
- [Installation](#installation)
- [First start](#first-start)
- [Using it in the game](#using-it-in-the-game)
- [The map](#the-map)
- [Features in more detail](#features-in-more-detail)
- [Updates](#updates)
- [FAQ](#faq)
- [Uninstalling](#uninstalling)
- [Licenses and thanks](#licenses-and-thanks)

## What it does

### Map and navigation

The map is built from your own game files, so it includes every DLC you own. It shows roads, junctions, bridges, buildings, water, forests, company sites and fuel stations. There are two styles, based on Google Maps and Apple Maps, each in light and dark, either flat or tilted.

The app takes the route from the game's own navigation. You get turn directions with lane guidance, traffic lights with remaining time, the speed limit, arrival time and rest areas along the route. Announcements are available in German or English.

### Apps

- Spotify with cover art, controls, queue and synced lyrics. It also works when the game isn't running
- Radio with more than 90 stations (German, English, I LOVE RADIO and the stations from your game), plus your own
- Job: route, deadline, time buffer, pay and when your next break is due
- Truck: speed, gear, rpm, fuel, AdBlue and the condition of truck and trailer
- Speed cameras, weigh stations and toll gates with a warning sound. The app remembers every camera that caught you
- Weather for the place you're driving through
- Phone with dispatcher, roadside assistance and others, messages, calendar, logbook, fuel & rest, videos
- A dashboard with widgets you arrange yourself, plus your own wallpapers and icons

### Voice assistant (optional)

Hold the Home button and talk, for example "Will I make the delivery?" or "Play something by AC/DC". The language model runs entirely on your PC, costs nothing and needs no account. It is only downloaded if you ask for it in the settings (about 1.5 to 3 GB) and can be removed at any time. Without the download you get fixed voice commands.

### Controls

- Touch mode in the game: click CarPlay as a window or directly on the display in the cab. The app compensates for head and cab movement
- Hotkeys for everything important, including steering wheel buttons
- Phone remote over Wi-Fi, connected via QR code
- An editor window on the PC for setting things up

### Also

- German and English, metric and US/UK units, 12 or 24 hour clock
- Updates arrive automatically. After a game update the app rebuilds the map by itself
- Nothing in the game is changed: no mods in the game files, no edits to `config.cfg`

## Screenshots

| | |
|---|---|
| ![Navigation light](bilder/navi-hell.png) | ![Navigation dark](bilder/navi-dunkel.png) |
| Navigation, Google style, light | Navigation, Google style, dark |
| ![Apple style dark](bilder/karte-apple-dunkel.png) | ![Dashboard light](bilder/dashboard-hell.png) |
| Navigation, Apple style, dark | Dashboard |
| ![Radio](bilder/radio.png) | ![Home](bilder/home.png) |
| Radio | Home screen |
| ![Job](bilder/auftrag.png) | ![Truck](bilder/fahrzeug.png) |
| Job | Truck |
| ![Speed cameras](bilder/blitzer.png) | ![Weather](bilder/wetter.png) |
| Speed cameras | Weather |

The screenshots show the German interface. English can be switched on in the settings.

## Requirements

- Windows 10 or 11, 64 bit
- Euro Truck Simulator 2, current version (Steam), DirectX 11
- About 350 MB of disk space, more with the voice assistant

## Installation

1. Close Euro Truck Simulator 2.
2. Download the latest version from [Releases](../../releases). Either the installer `ETS2-CarPlay-Setup-<version>.exe` (you pick the folder) or the ZIP, which you just unpack before starting `ETS2 CarPlay.exe`.
3. The app finds ETS2 through Steam and copies the plugin into the game by itself. You can check that it worked under Settings › General › Plugin & game.

## First start

1. Start ETS2. The first time, the game asks whether it may load SDK plugins. Confirm with OK. From then on the game starts the app by itself.
2. Get into a truck with a navigation screen. CarPlay appears on the display.
3. Ctrl + F8 opens the CarPlay menu in the game. Pick the screens CarPlay should run on and press Apply.
4. For navigation, set a destination in the game's navigation or take a job.

On the very first start the app builds the map from your game files. That takes a minute or two and runs in the background.

## Using it in the game

| Keys | What happens |
|---|---|
| Ctrl + F8 | CarPlay menu in the game (screens, touch, status) |
| Ctrl + Alt + M | Touch mode on or off, then CarPlay works with the mouse |
| Ctrl + Alt + E | Editor window on the PC |
| Ctrl + Alt + P | Play or pause music |
| Ctrl + Alt + Page Up / Page Down | Previous or next track |
| Ctrl + Alt + arrow keys, Enter, Backspace | Move through CarPlay, select, go back |
| Ctrl + Alt + H | Home screen |
| Ctrl + Alt + V | Voice command |

You can change every hotkey in the app.

Touch mode comes in two flavours. Either CarPlay sits on top of the game as a window that you can move and resize. Or you calibrate the display in the cab once (click its four corners) and then click straight on the screen in the truck.

For the phone, turn on phone control in the settings and scan the QR code. Phone and PC need to be on the same Wi-Fi.

## The map

The app reads the map from your game files and rebuilds it after game updates. What it shows is up to you in the map settings: green areas, forests, water, buildings, company sites, road numbers, lane markings and so on.

Bridges and overpasses visibly sit above the roads below. Roads are as wide as their lanes, and one-way roads and ramps get arrows.

Two switches are off by default:
- Hidden roads: roads the game doesn't show on its own map. Mostly scenery or only for AI traffic
- Secret shortcuts: the routes you have to discover in the game first

Water for sea, rivers and lakes comes from the game itself, the open sea from Natural Earth. Rivers and lakes are not accurate everywhere yet.

ETS2 squeezes Europe quite a lot, Dover and Calais are only a few kilometres apart for example. The map shows the world the way it is in the game.

## Features in more detail

### Spotify

Without any setup CarPlay shows what is playing in the Spotify app on your PC (title, artist, cover) and controls play, pause and skipping.

For the library with playlists, recently played, liked songs, search and queue, connect your own Spotify account once:
1. Sign in at [developer.spotify.com/dashboard](https://developer.spotify.com/dashboard) with your Spotify account and choose "Create app". Any name works, tick "Web API".
2. Enter exactly `http://127.0.0.1:8724/callback` as Redirect URI and save.
3. Copy the app's Client ID.
4. In CarPlay, in the editor window under Settings › Music › Spotify library, paste the Client ID, click Connect and approve in the browser.

The login stays on your PC (`%APPDATA%\ETS2 CarPlay`), nothing goes through third-party servers. Playing from the library needs Spotify Premium and an open Spotify app. Lyrics come from LRCLIB and scroll along when synced lyrics exist for the track.

### Radio

Stations are sorted into German, English, I LOVE RADIO, ETS2 and Own. ETS2 lists the stations you added in the game. You add your own in the editor window with "+ Station": search by name (radio-browser.info directory) or enter a stream address. Radio and Spotify stop each other, and the steering wheel buttons switch stations.

### Video

YouTube and Twitch links play on the display in the truck. Copy a link and paste it in the video app, or send it from your phone. If you like, the video pauses while you drive.

### Voice commands and announcements

Ctrl + Alt + V (or holding the Home button) starts a voice command, for example "Next fuel station", "How far", "Weather", "Call dispatcher" or "Next track". Without the voice assistant the Windows speech recognition understands fixed commands, with it you can talk freely. Navigation announcements use the Windows voices or one of ten extra AI voices (for example Olivia). They run right inside the app on the processor, also on mid-range PCs, and are only downloaded if you want them (about 400 MB). Announcements and warning sounds have separate volumes.

### Job, truck and bus

The dispatcher gets in touch with messages and calls. If you drive a coach from the Coach DLC, the app notices: no trailer, a trip instead of cargo, an arrival deadline and bus stops on the map.

### Weather

The real weather of the city you're driving through. It comes from Open-Meteo, with MET Norway as a fallback. Only the place is sent, no account needed.

### Mods

Company and city names from mods enabled in the game (real company names, for example) also show up on the map. The app only reads the name files. You can turn this off under Settings › Maps.

### Reporting map errors

If the map is wrong somewhere, say water where there is land, choose "Report a map error" in the map menu. The position and a picture are saved to `%APPDATA%\ETS2 CarPlay\map-reports`. Feel free to attach them to an issue here on GitHub.

### Backing up settings

Settings › General › "Back up settings …" writes all settings, learned speed cameras and videos into one file. Handy when you move to another PC.

## Updates

Once a day the app checks for a new version (Settings › General › Software update). It downloads the update and installs it when you close the app, plugin included. Your settings are kept. Every file is checked via SHA-256 first.

## FAQ

**Windows shows a warning at startup ("Windows protected your PC").**
The program isn't digitally signed, so Windows doesn't know the publisher. Click "More info" and then "Run anyway". If you want to be sure, compare the checksum with `SHA256SUMS.txt` in the release:

```powershell
Get-FileHash .\ETS2-CarPlay-Setup-1.7.0.exe -Algorithm SHA256
```

**CarPlay doesn't show up in the game.**
Close ETS2 completely, start it again and confirm the SDK prompt. In the app, check under Settings › General › Plugin & game that the plugin is installed. Then pick the screen in the game with Ctrl + F8 and press Apply.

**The map is empty or outdated.**
Settings › About › Rebuild map. After game updates the app does this by itself.

**Does it cost performance?**
Hardly. The app only redraws what changes and hands the picture to the game through the graphics card. On a normal gaming PC you won't notice a difference.

**Does it work with American Truck Simulator?**
No, only with Euro Truck Simulator 2.

## Uninstalling

Either through Windows under Settings › Apps (if you used the installer), in the app under Settings › General › Uninstall ETS2 CarPlay, or for the ZIP version with `Deinstallieren.cmd` in the program folder.

This removes the plugin from the game, the placeholders in `Documents\Euro Truck Simulator 2\ETS2CarPlay` and the program folder. Your settings (`%APPDATA%\ETS2 CarPlay`) only if you want. The game itself stays exactly as it was.

## Licenses and thanks

- Parts of the game plugin come from the [ETS2LA plugin](https://github.com/ETS2LA/plugin) (MIT).
- Map data is read from the game files with the [TruckSim map parser](https://github.com/truckermudgeon/maps) (GPL-3.0). Its source code ships with every package (`resources/mapdata/parser/QUELLE.txt`).
- Sea areas: [Natural Earth](https://www.naturalearthdata.com/) (public domain).
- Radio stations: [radio-browser.info](https://www.radio-browser.info/), lyrics: [LRCLIB](https://lrclib.net/), weather: [Open-Meteo](https://open-meteo.com/) and MET Norway.
- Voice assistant: whisper.cpp and llama.cpp (MIT), Qwen language model (Apache 2.0), Supertonic 3 voices by Supertone (OpenRAIL-M) via ONNX Runtime (MIT).
- Font: [Inter](https://github.com/rsms/inter) (SIL Open Font License 1.1).
- Built with [Electron](https://www.electronjs.org/).
