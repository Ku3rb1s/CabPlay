# Changelog

English · [Deutsch](CHANGELOG.de.md)

All versions of CabPlay (up to 1.12: ETS2 CarPlay). Get the current version from [Releases](../../releases/latest).

## 1.14.10 (2026-10-31)

- **Many more rivers and lakes on the map**: many waters were missing or cut off so far – for example the Rhine at the bridge near Duisburg. The game draws them with older water materials that the map did not recognise as water. The app now reads all water materials straight from the game data. In ETS2 this puts more than twice as much of the game's water on the map (e.g. the Rhine at Cologne, the Garonne, Loire and Douro, the Albufera near Valencia), in ATS about three times as much (e.g. the Columbia River, the Missouri at Great Falls, the Spokane River, the Rio Grande).
- **Cleaner shores and towns**: roads and houses at water level are no longer drawn in the water (quays, piers, shore roads), and towns above one of the game's water planes – such as Málaga, Villa San Giovanni or Newport (ATS) – stand on solid ground.
- **Map updates with fewer DLCs**: if you don't own all map DLCs, you previously never got your own up-to-date map – the check compared it with the bundled map of all DLCs and took the smaller map for broken. The check now recognises missing DLCs.
- For this, the map is rebuilt once in the background after the update (a few minutes; your current map stays until then).

## 1.14.9 (2026-10-31)

- **Wrong direction after loading**: if you drove the wrong way on the motorway after starting the game, the navigation showed "Follow the route" and the distance kept growing instead of following the new route. The app had matched the truck to the route's way back on the opposite carriageway. Now, while driving, only route parts in your driving direction count – the navigation shows the game's new route with the next place to turn around.

## 1.14.8 (2026-10-30)

- **Reversing camera on ETS2/ATS 1.62**: when CabPlay had to reload the navigation texture (see 1.14.7), the display of the Road Trip cars no longer switched to the parking camera when reversing. Fixed – the camera shows up as usual again.

## 1.14.7 (2026-10-30)

- **ETS2 1.62 (beta)**: the in-cab navigation screen sometimes showed only the red "GPS" placeholder instead of CabPlay. ETS2 1.62 sometimes loads the navigation texture at game start, before the plugin is running. CabPlay now detects this and has the game reload the texture shortly after you get in – after about 2 seconds, CabPlay is on the screen. Thanks to KamsatoAyaka for the detailed report (#2).

## 1.14.6 (2026-10-29)

- **Reversing camera of the Road Trip cars**: in the Ford F-150 2023 and the Ford Bronco 2024 (ATS), the navigation screen shows the game's parking camera again when reversing – with guide lines and 360° view. As soon as you drive forward, CabPlay is back. In trucks, CabPlay stays on screen when reversing. Can be turned off in the in-game menu (Ctrl+F8) under "Game's reversing camera".

## 1.14.5 (2026-10-27)

- **Map updates without a running game**: if you start the app without a game (e.g. after an update), it rebuilds outdated maps of all installed games in the background – the ATS map is ready before you start ATS. If you start a game meanwhile, the build for the other game stops (so nothing stutters) and is done later. Your current map is never touched.
- **Settings › Map data** shows both games with status and date, each with a "Rebuild map now" button.
- **Long jobs**: the route in the navigation now reaches about 3,000 km (it used to end after roughly 650 km). Long routes are calculated about ten times faster – the interface no longer freezes and the map stays smooth.
- **More stable**: three possible game crashes fixed in the plugin (image transfer, empty vehicle data); in touch mode, keyboard and wheel can no longer be blocked by mistake. Settings, hotkeys and the Spotify login are no longer lost if something crashes while saving; a damaged config or places file no longer stops the app from starting or the map from loading.

## 1.14.4 (2026-10-26)

- **More accurate turns**: no more "U-turn" or "sharp turn" in the middle of loop ramps, no turn announced for a mere bend of the road next to a junction, no double announcements for the same exit. If the game's AI signals to the other side than a short wiggle of the lane, the signal wins.
- **Ferries**: its own "Take the ferry" announcement with a ship icon instead of wrong turns at the pier.
- **Direction from signposts**: signs for the opposite direction no longer count (it said e.g. "towards München" instead of "towards Nürnberg"). In ATS, sign words such as MAXIMUM, EXIT, SOUTH and signs on company sites are no longer destinations, nor are state names and clearance heights.
- **Lane guidance**: a turn lane that only appears shortly before an exit is shown from there – not 1.5 km ahead across gas stations and other exits. At junctions with tram tracks or closed lanes, lane count and highlighted lane are now right (ETS2 and ATS).
- **Map**: houses above tunnels and buildings whose yard or parking lot covered a road no longer sit on the road. In ATS, interstate ramps are drawn as motorway.
- **Map check**: every rebuild of the map is now also checked for lane data, junctions, buildings and signposts and compared with the current map – if something fails, the old map stays.
- **Dashboard**: whether the stack jumps to the notifications widget on fines, tolls and jobs can be turned off (Settings › Dashboard).

## 1.14.3 (2026-10-25)

- **No new desktop shortcut with every update**: updates no longer create the shortcut again – one you deleted stays gone. Whether there is one is up to you under Settings › Software update › "Desktop shortcut". (The update to 1.14.3 still runs the old way and creates it one last time.)

## 1.14.2 (2026-10-25)

- **Road Trip: courier jobs are shown**: ATS reports jobs by car differently from truck jobs – so CabPlay showed "No job". Now cargo, start, destination, pay and deadline appear in the Job app, in navigation and with the dispatcher; delivering counts just like truck jobs
- **Direct touch per vehicle**: the "On the display" calibration is saved for every truck and car separately – shared between ETS2 and ATS (`%APPDATA%\CabPlay\touch-vehicles.ini`). When you get in, the matching one applies automatically; a vehicle without its own calibration opens touch in the window. Your current calibration now belongs to the vehicle you're sitting in on the first start with 1.14.2
- **Miles**: with mph, the speed warning ("From +5") now works in mph and says so (before it counted in km/h); the spoken "The speed limit here is …" gives the limit in mph instead of km/h
- Times like "1 h 60 min" are gone – properly rounded it now says "2 h 0 min"

## 1.14.1 (2026-10-25)

- **In-game menu back on Ctrl+F8**: the CabPlay menu in the game opens with Ctrl+F8 (before: F8 alone). The plugin switches the old F8 setting over by itself; you can still pick another key in the menu under "Shortcuts"
- **Small roundabouts on the map**: narrow roundabouts (e.g. in Rijeka) were drawn like ordinary intersections – now they have their green island, at almost 1,000 places in ETS2. On two-lane roundabouts the island no longer covers the inner lane. A map you rebuilt yourself is rebuilt once for this
- Keyboard shortcuts now read "Ctrl" instead of "Strg" in English, Polish and Turkish (app and in-game menu)

## 1.14.0 (2026-10-25)

- CabPlay now also runs in **American Truck Simulator**. The app detects which game is running by itself – there's nothing to choose. The plugin goes into every game installed through Steam
- Its own **map of the USA**: the first time you play ATS with CabPlay, it builds the map from your game files (takes about five minutes, runs in the background)
- **US signs**: the speed limit as a white "SPEED LIMIT" sign, road numbers as Interstate, US Highway and State Route shields on the map
- **States** instead of countries: "Welcome to Nevada" with the state's truck speed limits, a notice before the state line
- **Units and clock as in the game** (new setting "Same as in the game", now the default): miles or kilometers, 12 or 24 hours – the way you set it in the game options. Money in dollars
- In ATS, instead of speed cameras (there are none), warnings for **weigh stations** and toll booths
- **Radio**: a new **USA** list with 26 stations (lots of country, plus rock, pop, hip-hop, NPR) and the stations from the ATS online radio
- **Wide displays without distortion**: in the Freightliner Cascadia, Western Star 57X, MAN TGX 2020 (ETS2) and other trucks with a wider or narrower navigation screen the picture was stretched – CabPlay now draws in the right shape
- **Road Trip**: courier jobs by car are shown correctly (cargo in kg, no trailer, no truck speed limits at state lines); the Bronco and F-150 have their own display shape, which CabPlay takes into account; Ford logo as the vehicle icon
- **Map error reports and lane data kept per game**: reports from ATS improve the ATS map, reports from ETS2 the ETS2 map – nothing gets mixed
- Uninstalling removes the plugin from both games
- **Units with Steam Cloud profiles**: settings are now read from the cloud profile in Steam or from the running game (before, an outdated copy was used for cloud profiles – also for automatic lights in ETS2)
- **Touch directly on the display**: on wide displays clicks now land in the right place (before e.g. Home instead of Settings)
- **Radio**: US stations (KISS FM, Z100 …) no longer show things like text="…" song_spot=… in the title; titles with an apostrophe ("Don't Stop") are no longer cut off; on wide displays the controls stay visible
- **Traffic lights on the map**: one icon per intersection, in its center (in ATS they were next to or behind the intersection)
- The flag at the delivery point (since 1.13.4) has been removed again – the destination shows the red pin as before, company names as usual
- **No more false roundabouts**: large intersections, fuel stations and toll booths got a green island on the map like a roundabout – in ATS at many intersections, in ETS2 at about 100 places. Only real roundabouts are detected now. CabPlay rebuilds an already created ATS map once for this
- **No false water in ATS**: rock and gravel ground counted as water (large lakes e.g. near Las Cruces, North Platte and Emporia), and European coastlines lay as "sea" in the middle of Texas and Kansas. Both are fixed, and terrain shapes and ground types are now right for ATS
- **Tidier map**: small towns without sign formatting in their names and without junctions or state lines as towns ("Jct I-25", "State Line"); national roads (e.g. French N and Croatian D roads) no longer shown as motorways; toll booths count for the right country; border notices along the route are detected more reliably

## 1.13.6 (2026-10-25)

- Software update fixed: "Update now" closed CabPlay without installing anything. Windows ended the update program right away before it started – so updating from within the app never actually worked. It now starts a different way, shows the "Updating CabPlay …" window and installs the new version
- Uninstalling from within the app (Settings › General) had the same bug and now works too; with an installation "for all users", Windows asks for administrator rights

## 1.13.5 (2026-10-25)

- Closed CabPlay by accident? The in-game menu (F8) now shows a "Start" button next to "CabPlay app": it starts CabPlay in the background just like when the game starts, without a window – the display is back after a second or two
- Plugin 1.9.2

## 1.13.4 (2026-10-25)

- Map: the drop-off point of your job is now shown as a red flag with the company name on the CabPlay map – like the flag on the in-game map. With a navigation route it sits at the end of the route, and it stays after you arrive. Without a job, the pin shows the route destination as before

## 1.13.3 (2026-10-24)

- Visible software update: while updating, a small window "Updating CabPlay …" with a progress bar shows what is happening (closing the app, installing the new version, updating the plugin). At the end it says "CabPlay is up to date" – or shows a hint if something went wrong. Before, the app just closed and nothing could be seen for half a minute

## 1.13.2 (2026-10-24)

- Software update: if CabPlay was installed "for all users", updating from within the app did nothing – the app just closed. Now Windows asks once for administrator rights and the update goes through. If something goes wrong, the app still restarts, and a log (`update\einspielen.log`) shows what happened
- "What's new" now shows **highlights** and `file names` properly instead of asterisks and backticks

## 1.13.1 (2026-10-24)

- The folder with the placeholder textures for the navigation display is now called `Documents\Euro Truck Simulator 2\CabPlay-Display` (previously `ETS2CarPlay`). The plugin creates it by itself when the game starts, switches your settings over and removes the old folder
- Plugin 1.9.1: the dashboard placeholders, which are no longer needed, are gone
- Uninstalling removes both folder names

## 1.13.0 (2026-10-24)

- New name: "ETS2 CarPlay" becomes **CabPlay** – app, desktop icon, installer, plugin and in-game menu. The interface in the truck stays the same
- Your settings, map data, AI models, logos and Spotify login move along automatically on first start (from `%APPDATA%\ETS2 CarPlay` to `%APPDATA%\CabPlay`)
- The plugin is now called `cabplay.dll` (version 1.9.0). The app replaces the old `ets2_carplay.dll` by itself as soon as the game is closed and keeps your shortcuts, screen and touch settings
- The installer is now called `CabPlay-Setup-<version>.exe`, the ZIP `CabPlay-<version>.zip`. The program file is `CabPlay.exe`
- Settings backups (Settings › General › Back up settings) from older versions can still be loaded

## 1.12.3 (2026-10-24)

- Voice assistant: the app now loads the local AI only once the game has finished loading and is running – no longer in the middle of the loading screen, where the game and the language model were loading onto the graphics card at the same time
- The app crashed on exit when the AI voice was loaded (invisible to you, but it left a large crash report every time) – the voice is now released properly first
- New log `app.log` in the data folder (`%APPDATA%\ETS2 CarPlay`): startup, connection to the game, errors and crashes of child processes. Useful when reporting problems. Crash reports stay on your PC and are never uploaded

## 1.12.2 (2026-10-21)

- Lights: with automatic lights, the app correctly detects darkness again. The game only dims the dashboard backlight at night (1.0 during the day, about 0.8 at night), so it always counted as "lights on" – "By headlights", the light indicator and "Dimmer at night" were in night mode during the day too
- "Dimmer at night" now dims in every color scheme (with "Light" the switch did nothing), a bit more with "Light", and is also visible in the window on the PC
- Formula 1: if the previous data service (Jolpica) is unreachable, calendar, results and standings come from OpenF1 automatically – instead of "No connection to the sports service"
- Navigation settings and README: note that distances for turns, lanes and traffic lights are the real distance on the road – the game's navigation counts in compressed game kilometres (about 1:19 in the countryside)
- Less load on high refresh rate monitors: the window on the PC only asks for a frame as often as the map draws (previously more than 500 times per second at 540 Hz)
- Plugin 1.8.1: leftovers of the removed dashboard and custom screens taken out (no more "Custom-Render-Patch nicht gefunden" warning in the game log)

## 1.12.1 (2026-10-21)

- "Apple" icon set: new Music icon in the style of iOS 27.2 – black note on white, white note on black in the "Dark" icon style. The note follows Apple's design (tilted oval note heads, slim stems, bold beam)

## 1.12.0 (2026-10-21)

- New in-game plugin menu in CarPlay style: status, GPS display (resolution and frames per second at a tap), touch, shortcuts and start at a glance. Changes apply and save right away
- The menu now opens with F8 (the only F key the game doesn't use). Ctrl+F8 still works
- Plugin cleaned up: dashboard and custom screens, window sources and the fingerprint search from the predecessor plugin are gone – CarPlay runs on the GPS display as before
- New app icon in the style of the start screen, and the start screen itself with a larger symbol
- Sports: the live ticker reports kick-off and goals faster – during a match it checks every 15 seconds (previously up to 5 minutes)
- New setting "Logos" (General): save club crests and truck brands on this PC (deleted after 30 days without being shown, at most 40 MB) or load only. The app's cache no longer grows to hundreds of MB
- ZIP version: "Deinstallieren.exe" instead of the .cmd file, with questions in regular windows
- Translations: "Straight ahead" in the navigation banner, "Motorway" on the speed limit sign, "Goal" in the sports widget, "Roadside assistance" and "Along the route" in the map settings are now translated in English, Polish and Turkish; "Euro Truck Simulator" no longer turns into "euros Truck Simulator"

## 1.11.1 (2026-10-20)

- Border crossing: "Welcome to …" now appears at the actual border – no longer too early, with the wrong country or randomly in between. The app uses the country of the road you are driving on instead of the nearest city (which is often in the neighboring country near a border)
- Fuel & Rest: the diesel price therefore also shows the right country near borders

## 1.11.0 (2026-10-20)

- New languages: Polish and Turkish (Settings › General › Language) – interface, dispatcher, navigation announcements and the AI voice assistant. Olivia and the other AI voices also speak Polish and Turkish
- Installer in German, English, Polish and Turkish; the app starts in the language chosen during setup
- With any language other than German, the plugin's in-game menu is in English
- English: turn announcements and job messages are now read out fully in English, country names in English, missing texts added
- Edit home screen: drag icons over the edge onto another page and drop them on free spots
- Sports settings: favorite teams with name and crest, followed matches can be removed there
- Radio: new stations KIIS FM, Power 105.1, Q104.3, YOU FM, Antenne Bayern Top 40 and Radio Bollerwagen; I LOVE stations with readable names
- Less memory: the language model on the graphics card needs about 0.8 instead of 2.9 GB, the AI voice is unloaded after 10 minutes without speaking
- The game closes via Steam without delay again
- App icons: the dashboard is no longer in the list

## 1.10.2 (2026-10-20)

- Map: company sites, ports, dealers and fuel stations show their halls and buildings (often empty areas before), with matching heights for the 3D view
- Map: railways as an option (Settings › Maps › Map content)
- Map: "Color roads by type" is now a switch, off by default – in the Google style all roads then look the same. Turn it on if you like the white city streets
- Map: road width uses the real median (some roads were too wide or too narrow), port structures and ships are in the right place (better shoreline in ports)
- Lane guidance: more accurate on roads without a measured junction
- Clearer settings: maps split into "Map content" and "Navigation & alerts", own page "Driving data & map errors"
- The GitHub buttons now say that a GitHub account is needed

## 1.10.1 (2026-10-19)

- Lane guidance: the dot under your current lane is now correct. The app used to estimate the median width from the road type and was often half a lane off, so the dot showed the left lane while you were driving on the right. The median is now measured at the junctions when the map is built. The route line also sits more accurately on the lane
- Radio: volume now follows how loudness is perceived. Low values are really quiet (1 % is practically silent), and the whole slider range is usable. If you listened at a low level before, turn it up a little
- Quitting: the app closes right after the game ends, so Steam no longer shows ETS2 as running for almost a minute
- Voice command "nearest fuel station": the distance is now given in game kilometres, like in the fuel app

## 1.10.0 (2026-10-19)

- Night: the app learns sunrise and sunset from the game. With automatic headlights it remembers when the lights go off in the morning and on in the evening, and uses those times instead of fixed hours. This also adapts to mods with different sun times
- Music: the Spotify volume control (Windows mixer) has been removed again. If you used it: set Spotify back to 100 % in the Windows volume mixer

## 1.9.9 (2026-10-19)

- Map: buildings have their real footprint from the game's models (annexes, corners, round silos) instead of a rectangle, and sit in the right place. Before, some were up to 40 m off, for example across a road. 3D buildings use the real outlines too
- Map: buildings are clearly visible in the dark Google style, company sites no longer look like a gray veil, 3D buildings stay calm (silos and towers no giant blocks)
- Fuel & Rest: distances in game kilometres like the navigation and the range (ETS2 compresses the world, the scale is measured live). Times at fuel stations and rest areas are more accurate too
- Navigation: signposts no longer show game identifiers ("traffic_rule…")
- Lights: with automatic headlights in the game, the app detects whether the headlights are really on (via the dashboard backlight). Matters for "By headlights", "Dimmer at night" and the indicator light. Night by clock is now 20:30–5:00
- Music: Spotify volume right in the Music app (tap the speaker icon). Works through the Windows mixer, no Spotify account needed
- Phone and Messages show a red counter on the icon. Missed calls only count new ones until you open the call list
- Display correction "Balanced" dims white more so the display in the cab doesn't glare
- The plugin is now reliably updated after the game closes (before, the old one sometimes stayed)

## 1.9.8 (2026-10-19)

- Direct touch: the mouse goes back to the game while it is paused (Esc menu, full-screen map, job market) or an exterior camera is active. Touch comes back by itself afterwards. Can be turned off in the direct-touch bar ("Free mouse")
- Optional: Spotify and radio pause while the game is paused and continue afterwards (Settings › Music › "Pause when the game pauses")
- Optional: the display in the truck dims at night like in a real car (Settings › Display & Brightness › "Dimmer at night")

## 1.9.7 (2026-10-19)

- Map in Google style: road colors by type, like Google Maps in CarPlay. City streets white with a gray edge; main roads, multi-lane roads and motorways blue-gray
- Map: motorway interchanges look calmer when zoomed out. Carriageways that run close together merge into one band instead of thin stripes
- Map: company sites, fuel stations, rest areas and junction islands show their sub-areas like the game map (yard, parking, green)
- Optional: 3D buildings in the tilted view (Settings › Maps)
- Optional: the game's viewpoints and small towns on the map (Settings › Maps)
- Navigation: small towns help match the signposts, so the direction matches the sign more often
- Navigation: painted turn arrows only where every arrow clearly sits on its own lane
- Navigation: if you are already indicating towards the right lane, there is no "Please keep left/right" anymore
- Vehicle app: indicator lights like in the cab (indicators, hazards, lights, high beam, beacon, wipers, retarder) and warning lights with values (air pressure, oil pressure, engine hot, battery, AdBlue). Real problems while driving trigger a notification
- New "Live ticker" widget: the match you follow or a match of your favourite teams right on the dashboard
- Sports: kick-off time with date ("Today 18:30", "Tue 21.10. 18:45")
- Music: tapping the cover on the dashboard always opens "Now playing"
- Software update now shows everything new in the installed version and earlier versions. Updates are checked at every start (at most every three hours)
- Faster: the color scheme is no longer fully recalculated 20 times per second. Plus smaller clean-ups

## 1.9.6 (2026-10-18)

- Map: fields, rock, sand and snow from the game's terrain, with smooth, rounded edges. Subtle in the Google style, like Google Maps. Can be turned off under Settings › Maps ("Fields, rock & sand")
- Map: forests now also come from dense groups of trees. Single trees along roads and in gardens are left out
- Map: motorway rest areas and parking rows are drawn
- Zoomed in close: direction arrows on the lanes before junctions, like painted ones. Before junctions and exits the lane lines are solid instead of dashed
- Navigation: cloverleaf and flyover exits are now "Exit right" instead of "Sharp right". Lane guidance orders branches by lane position (no more wrong arrows at forks)
- Navigation: "Please keep right/left" announcement, the destination display has two lines like the turns
- Optional: curve warning when you are too fast before tight curves (Settings › Maps)
- Tram tracks no longer count as lanes
- Sports: 12 more leagues: Women's Bundesliga, Europa League, Conference League, Championship, Serie A, Ligue 1, Eredivisie, Liga Portugal, Austria, Switzerland, Süper Lig and the NFL. Premier League and LaLiga now come from more up-to-date data. With live clock, goal scorers and tables
- Sports: tap a match for a live ticker for just that match, tap again to turn it off
- Sports: reorder leagues by dragging (press and hold a league in the app, or use the ≡ handle in Settings) and hide single leagues
- "Improve navigation" collects driving data on request (route, lane choice, turns) as a basis for better lane guidance

## 1.9.5 (2026-10-18)

- Turns now come from the game's junction data (lane directions and the AI's turn signals). City turns, junctions close together and the last turn before the destination are no longer missing
- Signposts: exits show the road number as a shield and the destination from the real signs, e.g. "Exit right · A1 towards Linz". The voice says it the same way
- Entering the company site: "Turn left · into the site: Company", and the destination shows the company name
- Lane guidance only appears once the lanes reach you. On rest areas, ramps or acceleration lanes you no longer see the motorway lanes beyond
- The route line moves into the lane you need earlier. The other lanes show their real direction (main road straight instead of slanted)
- Marker under the lane you are in: blue = right lane, orange = change lanes. Can be turned off under Settings › Maps
- New "Sports" app: Bundesliga, 2. and 3. Liga, DFB Cup, Champions League, Premier League, LaLiga and Formula 1, with live scores, tables and standings. Favourite teams get a live ticker as notifications
- The vehicle icon shows the logo of the brand you drive (in color, dark and clear). Can be turned off under Settings › App Icons
- Optional: improve lane guidance. The app remembers places where the recommendation doesn't fit, and you can share them on GitHub
- Fixed: notifications in the "Clear" icon style had an invisible app icon

## 1.9.4 (2026-10-18)

- The route line follows the real lane through roundabouts and on- and off-ramps and sits on the lane you need
- Lane guidance looks ahead across several junctions like the game does. Lanes now also show where you go straight and the lanes split, and the other lanes show their own direction
- If the next turn is more than 2 km away, the navigation shows "Straight", with the turn small next to it
- Notice before borders: truck speed limits, tolls, diesel price and time zone of the next country
- Notice before steep climbs and descents, with an elevation profile and advice depending on weight
- Both appear in the navigation and on the dashboard and can be turned off under Settings › Maps, with or without voice
- Optional turn announcements by the app itself (Settings › Maps), earlier on motorways, later in town
- Leaving the route: "Recalculating route" until the game sends the new route
- Speed cameras, weigh stations and toll booths now come as normal notifications
- Setup on first start: game and plugin, controls, voice, map
- Pronunciation: kilometers, decimals and large numbers sound more natural, plus a list for the English voice. Olivia is marked as the recommended voice
- More variety in calls, plus a few new secret numbers
- Faster: speech is computed on its own thread, so the display no longer stutters while speaking. Map data loads much faster at startup
- Fixed: settings and lists jumped to the top after changes, light/dark needed two clicks, video volume and Twitch, Back in the map menu

## 1.9.3 (2026-10-18)

- Twitch streams now start on their own. Pause and volume also work for Twitch
- Video volume: the percentage was blank after tapping, and new videos started at full volume instead of your setting
- Phone remote: the picture is much smoother now (before, sometimes only 2 frames per second)
- Roundabouts: the instruction stays on screen after entering and counts down to your exit
- The speed in the navigation turns orange once you are above your speed warning setting. In the Google style it always stayed white before
- "By headlights" now also works with the game's automatic lights
- Map style and icons go together: Apple Maps brings the Apple icons, Google the Google Maps and Spotify icons
- Fixed: light/dark needed two clicks
- Fixed: in the map menu, Back after "More …" went to the settings instead of the map
- Fixed: settings and lists (radio, messages, places, calendar, video) jumped to the top after every change and during downloads
- The map no longer redraws everything after a setting change and uses less memory

## 1.9.2 (2026-10-18)

- Fixed: after tapping a result in the settings search, the whole picture was shifted. This could also happen when switching something far down in a long list
- Fixed: version 1.9.1 started with a blank screen only (1.9.1 has been withdrawn)

## 1.9.0 (2026-10-18)

**Voice**

- Olivia and the other AI voices sound cleaner (more processing steps, still under half a second per navigation sentence)
- Pronunciation list: numbers, times and prices are spoken correctly ("one euro sixty-nine", "fourteen thirty", "the second exit"), abbreviations are spelled out, road numbers read properly
- Places use the names a German navigation system uses (München, Köln, Kopenhagen …), foreign places and the game's companies are easier to understand. All cities and companies in the game were checked
- Voice list tidied up: the old voice Kerstin is gone (if you used it, you now get Olivia), the Windows voices are now labelled "Katja (Windows)" etc.

**Settings**

- New search at the top of the settings: finds every option, including sub-pages. A result opens the page and highlights the row
- On the truck screen there is an on-screen keyboard for it, docked at the bottom like in CarPlay, with umlauts, numbers and symbols

## 1.8.0 (2026-10-17)

**Navigation**

- Roundabouts are announced with the exit number ("Roundabout, exit 2")
- Fewer false turn prompts: bends and loop ramps no longer count as turns. The app uses the turn signal data of junctions from the game files for this
- Motorway exits now say "Exit right/left", forks still say "Keep right/left"
- The route line stays on your own carriageway and is smoother, without jumps to the middle of the road
- An uncoupled trailer is shown on the map

**Map**

- Water is more accurate in many places, Amsterdam among them. The game's ground data was read the wrong way before
- New: "Learn while driving". If you drive where the map shows water (ports, company yards), it becomes land the next time the map is rebuilt. The data stays on your PC
- Map menu: "Back" no longer jumps to the dashboard, clearer choices in "Report a map error", arrival time in the same glass as the sidebar

**Voice**

- Ten new voices for announcements, dispatcher and assistant, for example Olivia. They run right inside the app on the processor, also on mid-range PCs without a strong graphics card. Download under Settings › Voice assistant › Voice (about 400 MB)

**Other**

- Video: Twitch links work, own buttons for pause, seeking and volume
- Touch mode: the mouse pointer hides after 3 seconds without movement (plugin 1.6.0, installed by the app)

## 1.7.1 (2026-10-17)

- Google map style: the position arrow is bigger, and the white disc around it is slightly see-through like in Google Maps, so you can still see the road underneath

## 1.7.0 (2026-10-17)

- Radio app with more than 90 stations: German, English, I LOVE RADIO, the stations from your game and your own. The current song shows title and cover, volume goes in small steps (hold for big ones), and the steering wheel buttons switch stations. Radio and Spotify stop each other
- Lyrics in the music app, scrolling along with the song
- Spotify shows what's playing and can be controlled even when the game isn't running
- Map: bridges visibly sit above the roads below, roads are as wide as their lanes, one-way roads and ramps have arrows, and close up there are lane markings
- Hidden roads and secret shortcuts can be shown separately. Both are off by default, and railway tracks and footpaths are never drawn as roads
- New dark design for the Apple map style
- The app uses a lot less CPU. GPU transfer is now on by default, and the editor stops working while it's minimised or behind the game
- Settings tidied up, the map settings are now sorted into groups
- Fixed: calls ended right away, the speed display jumped, the weather sometimes didn't load, station logos broke in the middle of a word

## 1.6.0 (2026-10-17)

- AI voice assistant (optional): hold the Home button and just talk, e.g. “Will I make the delivery?”, “Play something by AC/DC” or “Call roadside assistance”. Answers come from your game data (job, route, fuel, breaks, weather), and the assistant can open apps, control music and make calls. It understands German and English and answers in the app language
- AI phone calls: the dispatcher, traffic radio, roadside assistance and co. talk to you. Tap the microphone after the greeting and just ask
- Everything runs on your PC: free, no account and no internet after the download. It is only downloaded if you want it (Settings › Voice assistant): standard about 3 GB, compact about 1.5 GB for weaker PCs. You can remove it at any time
- Natural voice “Kerstin” (optional, about 150 MB): reads out the dispatcher, navigation hints and answers and sounds more natural than the Windows voices. Works without the language model too and can be removed at any time
- New call screen like CarPlay: large picture, call duration, mute, hang up and, for AI calls, a transcript. An incoming call appears as a pill at the bottom and opens with a tap; the Home button makes it small again
- More fixed voice commands: more phrasings, plus time, fuel level, delivery deadline, calling contacts and “Repeat”
- Edit the home screen: hold the page dots at the bottom and the icons jiggle like on the iPhone. This now also works in the game and in the touch window

## 1.5.1 (2026-10-17)

- Map: “Sea” and “Rivers & lakes” can be turned on and off separately, each with its own icon. “Rivers & lakes” is marked as experimental because the game’s water data is incomplete
- Map: much less false water. Trees, buildings, fuel stations, parking areas, companies, bus stops, raised quays and riverside paths, plus quay walls, piers and harbour facilities from the game’s models now count as land. Vlorë, Heraklion and Rotterdam no longer sit in the water, and the harbours of Gothenburg, Frederikshavn and Palermo show their quays
- Report a map error: choose what is wrong: “Water here, but land in the game”, “Land here, but water in the game” or “Something else”. On the next map rebuild the reports are checked against the game data and applied
- Settings > Map errors: shows how many reports have been applied. From there you can rebuild the map with your reports, open the folder or report the latest one on GitHub
- Map check after game updates: additional fixed checkpoints at previously broken spots
- Phone: there are a few secret numbers. Just try dialling 😉

## 1.5.0 (2026-10-17)

- Map: bus stops from the game (can be turned off)
- Bus mode (Coach DLC): vehicle and job apps recognise coaches – no trailer, “trip” instead of cargo, arrival deadline, matching dispatcher messages
- Map: company and city names from active mods (e.g. real company names) – can be turned off
- Much smoother map: roads and areas are drawn in the background, the UI only blends in finished tiles; smaller map file (46 instead of 49 MB), loads faster and uses less memory
- Map: water errors fixed – no more false water over Florence, the town of Borlänge no longer sits in the river
- Map: “Report a map error” in the map menu saves position and picture so wrong spots can be fixed
- After game updates the regenerated map is checked automatically; if it fails, the previous map is kept
- Touch window (Ctrl+Alt+M): shows the picture without the cockpit image correction – no longer too dark, the cockpit display stays corrected
- Fixed: empty turn banner in the Google map style when no route is active
- Under the hood: code split up and covered by automated tests for the map data

## 1.4.0 (2026-10-17)

- Map: company, service and dealer sites plus quarries, company names when zoomed in (both can be turned off)
- Map: rivers, lakes, canals, harbours and sea surfaces straight from the game; coastlines from the game's terrain heights – much more accurate
- Map: drivable roads the game hides on its own map (residential areas, access roads) are now drawn; pure scenery roads optionally dashed
- Map: more coherent green areas, buildings without crossing outlines, Google colors (light and dark) like in CarPlay, narrower grey roads
- Navigation: no more “turn” announcements in ordinary bends; direction in the nav widget on its own, readable line
- Speed camera warning as a bold warning card
- Direct touch: more accurate in curves (cab tilt is compensated), top bar always/small/hidden, logging can be switched on
- Fixed: signal bars stayed empty in the game; empty turn banner when opening the map
- More compact map file

## 1.3.0 (2026-10-17)

- Map: building outlines, sea and lakes, forests, meadows & bushes (each can be turned off), roundabouts as rings, ferry and train lines
- Traffic lights like Google Maps: icons at junctions along the route, traffic light hint with remaining time in the navigation
- Map icons as pictograms (service, dealer, weigh station, ferry, train, fuel)
- Navigation: correct arrow right after the route start, nav widget with turn and direction on separate lines, long texts shrink instead of being cut off
- Updates download automatically and install when you quit (plugin included), “What’s new” in Settings, checksum (SHA-256)
- Notification banners can be turned off per type, phone control with QR code
- Redesigned in-game menu, now also in English
- Direct touch: steadier in curves, top bar always / small / hidden, logging can be switched on for testing
- Status bar: iOS-style charging bolt, bolder signal bars
- New app icon

## 1.2.0 (2026-10-16)

- Installer (setup): choose any folder, German/English, uninstall via Windows “Apps”
- English app (Settings › General › Language), including English announcements
- Metric / US / UK units (mph, mi, °F, gal, lb) and 12/24-hour time
- Google Maps style like CarPlay: turn card top left, arrival bottom left, speed top right; new light/dark colors
- Reworked Apple Maps dark, notifications like CarPlay (wider, at the bottom, with a check button)
- Uninstall from the app, tidied-up settings

## 1.1.0 (2026-10-16)

First public release.
