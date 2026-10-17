# Änderungen / Changelog

Alle Versionen von ETS2 CarPlay. Die aktuelle Version gibt es unter [Releases](../../releases/latest).

All versions of ETS2 CarPlay. Get the current version from [Releases](../../releases/latest).

## 1.7.1 (2026-10-17)

- Google-Kartenstil: Der Positionspfeil ist größer, und die weiße Scheibe darum ist leicht durchsichtig wie bei Google Maps, damit man die Straße darunter noch sieht

*English:*

- Google map style: the position arrow is bigger, and the white disc around it is slightly see-through like in Google Maps, so you can still see the road underneath

## 1.7.0 (2026-10-17)

- Radio-App mit über 90 Sendern: deutsche, englische, I LOVE RADIO, die Sender aus deinem Spiel und eigene. Zum laufenden Song gibt es Titel und Cover, die Lautstärke geht in kleinen Schritten (gedrückt halten für große), und die Lenkrad-Tasten wechseln den Sender. Radio und Spotify stoppen sich gegenseitig
- Songtexte in der Musik-App, sie laufen mit dem Song mit
- Spotify zeigt auch ohne laufendes Spiel, was gerade spielt, und lässt sich steuern
- Karte: Brücken liegen sichtbar über den Straßen darunter, Straßen sind so breit wie ihre Spuren, Einbahnstraßen und Auffahrten haben Pfeile, und ganz nah gibt es Fahrbahnmarkierungen
- Versteckte Straßen und geheime Abkürzungen kannst du einzeln einblenden. Beides ist ab Werk aus, Gleise und Gehwege werden nie als Straße gezeichnet
- Neues dunkles Design für den Apple-Kartenstil
- Die App braucht deutlich weniger Prozessor. Die GPU-Übertragung ist jetzt ab Werk an, und der Editor rechnet nicht mehr, wenn er minimiert oder hinter dem Spiel liegt
- Einstellungen aufgeräumt, die Karten-Einstellungen sind jetzt in Gruppen sortiert
- Behoben: Anrufe brachen sofort ab, die Tempo-Anzeige sprang, das Wetter lud manchmal nicht, Senderlogos wurden mitten im Wort umbrochen

*English:*

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

- AI-Sprachassistent (optional): Halte den Home-Knopf gedrückt und sprich einfach frei, zum Beispiel „Schaffe ich die Lieferung noch?“, „Spiel was von AC/DC“ oder „Ruf die Pannenhilfe an“. Die Antworten kommen aus deinen Spieldaten (Auftrag, Route, Tank, Pause, Wetter), dazu kann der Assistent Apps öffnen, Musik steuern und anrufen. Er versteht Deutsch und Englisch und antwortet in der App-Sprache
- Telefonate mit AI: Disponent, Verkehrsfunk, Pannenhilfe & Co. reden mit dir. Tippe nach der Ansage auf das Mikrofon und frag einfach nach
- Alles läuft auf deinem PC: kostenlos, ohne Konto und nach dem Download ohne Internet. Geladen wird nur, wenn du es willst (Einstellungen › Sprachassistent): Standard etwa 3 GB, Kompakt für schwächere PCs etwa 1,5 GB. Du kannst es jederzeit wieder entfernen
- Natürliche Stimme „Kerstin“ (optional, etwa 150 MB): liest Disponent, Navi-Hinweise und Antworten vor und klingt natürlicher als die Windows-Stimmen. Sie funktioniert auch ohne das Sprachmodell und ist jederzeit wieder entfernbar
- Neuer Anrufbildschirm wie bei CarPlay: großes Bild, Gesprächsdauer, Ton aus, Auflegen und bei AI-Gesprächen die Mitschrift. Ein eingehender Anruf erscheint als Pille unten und öffnet sich per Tipp, der Home-Knopf macht ihn wieder klein
- Feste Sprachbefehle erweitert: mehr Formulierungen, dazu Uhrzeit, Tankinhalt, Lieferfrist, Kontakte anrufen und „Wiederholen“
- Home-Bildschirm bearbeiten: Halte die Seitenpunkte unten gedrückt, dann wackeln die Icons wie auf dem iPhone. Das geht jetzt auch im Spiel und im Touch-Fenster

*English:*

- AI voice assistant (optional): hold the Home button and just talk, e.g. “Will I make the delivery?”, “Play something by AC/DC” or “Call roadside assistance”. Answers come from your game data (job, route, fuel, breaks, weather), and the assistant can open apps, control music and make calls. It understands German and English and answers in the app language
- AI phone calls: the dispatcher, traffic radio, roadside assistance and co. talk to you. Tap the microphone after the greeting and just ask
- Everything runs on your PC: free, no account and no internet after the download. It is only downloaded if you want it (Settings › Voice assistant): standard about 3 GB, compact about 1.5 GB for weaker PCs. You can remove it at any time
- Natural voice “Kerstin” (optional, about 150 MB): reads out the dispatcher, navigation hints and answers and sounds more natural than the Windows voices. Works without the language model too and can be removed at any time
- New call screen like CarPlay: large picture, call duration, mute, hang up and, for AI calls, a transcript. An incoming call appears as a pill at the bottom and opens with a tap; the Home button makes it small again
- More fixed voice commands: more phrasings, plus time, fuel level, delivery deadline, calling contacts and “Repeat”
- Edit the home screen: hold the page dots at the bottom and the icons jiggle like on the iPhone. This now also works in the game and in the touch window

## 1.5.1 (2026-10-17)

- Karte: „Meer“ und „Flüsse & Seen“ getrennt schaltbar, mit eigenen Symbolen. „Flüsse & Seen“ ist als experimentell markiert, weil die Wasserdaten des Spiels lückenhaft sind
- Karte: deutlich weniger falsches Wasser. Bäume, Gebäude, Tankstellen, Parkplätze, Firmen, Bushaltestellen, höher liegende Kais und Uferwege sowie Kaimauern, Piers und Hafenanlagen aus den Spielmodellen gelten jetzt als Land. Vlorë, Heraklion und Rotterdam stehen nicht mehr im Wasser, die Häfen von Göteborg, Frederikshavn und Palermo zeigen ihre Kais
- Kartenfehler melden: Beim Melden wählst du, was falsch ist: „Hier ist Wasser, im Spiel aber Land“, „Hier ist Land, im Spiel aber Wasser“ oder „Etwas anderes“. Beim nächsten Kartenneubau werden die Meldungen mit den Spieldaten abgeglichen und eingearbeitet
- Einstellungen > Kartenfehler: zeigt, wie viele Meldungen eingearbeitet sind. Dort kannst du die Karte mit den Meldungen neu erzeugen, den Ordner öffnen oder die letzte Meldung auf GitHub melden
- Kartenprüfung nach Spiel-Updates: zusätzlich feste Prüfpunkte an früher fehlerhaften Stellen
- Telefon: Es gibt ein paar geheime Nummern. Einfach mal wählen 😉

*English:*

- Map: “Sea” and “Rivers & lakes” can be turned on and off separately, each with its own icon. “Rivers & lakes” is marked as experimental because the game’s water data is incomplete
- Map: much less false water. Trees, buildings, fuel stations, parking areas, companies, bus stops, raised quays and riverside paths, plus quay walls, piers and harbour facilities from the game’s models now count as land. Vlorë, Heraklion and Rotterdam no longer sit in the water, and the harbours of Gothenburg, Frederikshavn and Palermo show their quays
- Report a map error: choose what is wrong: “Water here, but land in the game”, “Land here, but water in the game” or “Something else”. On the next map rebuild the reports are checked against the game data and applied
- Settings > Map errors: shows how many reports have been applied. From there you can rebuild the map with your reports, open the folder or report the latest one on GitHub
- Map check after game updates: additional fixed checkpoints at previously broken spots
- Phone: there are a few secret numbers. Just try dialling 😉

## 1.5.0 (2026-10-17)

- Karte: Bushaltestellen aus dem Spiel (abschaltbar)
- Bus-Modus (Coach-DLC): Fahrzeug- und Auftrag-App erkennen Reisebusse – ohne Anhänger, „Fahrt“ statt Fracht, Ankunftsfrist, passende Disponenten-Nachrichten
- Karte: Firmen- und Städtenamen aus aktiven Mods (z. B. echte Firmennamen) – abschaltbar
- Karte deutlich flüssiger: Straßen und Flächen werden im Hintergrund gezeichnet, die Oberfläche blendet nur fertige Kacheln ein; Kartendatei kleiner (46 statt 49 MB), lädt schneller und braucht weniger Speicher
- Karte: Wasserfehler behoben – keine falsche Wasserfläche mehr über Florenz, der Ort Borlänge steht nicht mehr im Fluss
- Karte: „Fehler auf der Karte melden“ im Karten-Menü speichert Position und Bild – so lassen sich falsche Stellen gezielt korrigieren
- Nach Spiel-Updates wird die neu erzeugte Karte automatisch geprüft; fällt sie durch, bleibt die bisherige Karte
- Touch-Fenster (Strg+Alt+M): zeigt das Bild ohne die Cockpit-Bildkorrektur – nicht mehr zu dunkel, das Display im Cockpit bleibt korrigiert
- Behoben: leeres Abbiege-Banner im Google-Kartenstil, wenn keine Route aktiv ist
- Unter der Haube: Programmcode aufgeteilt und mit automatischen Tests für die Kartendaten abgesichert

*English:*

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

- Karte: Firmen-, Werkstatt- und Händlergelände sowie Steinbrüche, Firmennamen beim Heranzoomen (beides abschaltbar)
- Karte: Flüsse, Seen, Kanäle, Häfen und Meeresflächen direkt aus dem Spiel; Küsten aus den Geländehöhen des Spiels – deutlich genauer
- Karte: befahrbare Straßen, die das Spiel auf seiner eigenen Karte versteckt (Wohngebiete, Zufahrten), werden jetzt gezeichnet; reine Kulissenstraßen optional gestrichelt
- Karte: Grünflächen zusammenhängender, Gebäude ohne sich kreuzende Ränder, Google-Farben (hell und dunkel) wie in CarPlay, schmalere graue Straßen
- Navi: keine „abbiegen“-Ansage mehr in normalen Kurven; Richtung im Navi-Widget gut lesbar in eigener Zeile
- Blitzer-Warnung als kräftige Warnkarte
- Direkt-Touch: genauer in Kurven (Neigung der Kabine wird ausgeglichen), Leiste oben immer/klein/unsichtbar, Messung schaltbar
- Behoben: Empfangsbalken im Spiel blieben leer; leeres Abbiege-Banner beim Öffnen der Karte
- Kartendatei kompakter

*English:*

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

- Karte: Gebäude-Umrisse, Meer und Seen, Wälder, Wiesen & Büsche (einzeln abschaltbar), Kreisverkehre als Ring, Fähr- und Zuglinien
- Ampeln wie bei Google Maps: Symbol an Kreuzungen entlang der Route, Ampel-Hinweis mit Restzeit im Navi
- Kartensymbole als Piktogramme (Werkstatt, Händler, Waage, Fähre, Zug, Tankstelle)
- Navi: richtiger Pfeil direkt nach dem Routenstart, Navi-Widget mit Abbiegen und Richtung in eigenen Zeilen, lange Texte werden kleiner statt abgeschnitten
- Updates laden automatisch und werden beim Beenden installiert (Plugin gleich mit), „Was ist neu“ in den Einstellungen, Prüfsumme (SHA-256)
- Mitteilungen je Art als Banner abschaltbar, Handy-Steuerung mit QR-Code
- Ingame-Menü neu gestaltet und auf Englisch
- Direkt-Touch: ruhiger in Kurven, Leiste oben immer / klein / unsichtbar, Messung zum Testen ein- und ausschaltbar
- Statusleiste: Ladeblitz wie in iOS, kräftigere Empfangsbalken
- Neues App-Logo

*English:*

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

- Installer (Setup): Programmordner frei wählbar, Deutsch/Englisch, Deinstallation über Windows „Apps“
- App auf Englisch (Einstellungen › Allgemein › Sprache), inkl. englischer Ansagen
- Einheiten metrisch / US / UK (mph, mi, °F, gal, lb) und 12-/24-Stunden-Uhr
- Google-Maps-Stil wie in CarPlay: Abbiegekarte oben links, Ankunft unten links, Tempo oben rechts; neue Farben hell/dunkel
- Apple Karten dunkel überarbeitet, Mitteilungen wie in CarPlay (breiter, unten, mit Häkchen)
- Deinstallieren aus der App, aufgeräumte Einstellungen

*English:*

- Installer (setup): choose any folder, German/English, uninstall via Windows “Apps”
- English app (Settings › General › Language), including English announcements
- Metric / US / UK units (mph, mi, °F, gal, lb) and 12/24-hour time
- Google Maps style like CarPlay: turn card top left, arrival bottom left, speed top right; new light/dark colors
- Reworked Apple Maps dark, notifications like CarPlay (wider, at the bottom, with a check button)
- Uninstall from the app, tidied-up settings

## 1.1.0 (2026-10-16)

Erste veröffentlichte Version. / First public release.
