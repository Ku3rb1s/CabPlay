# Änderungen / Changelog

Alle Versionen von ETS2 CarPlay. Die aktuelle Version gibt es unter [Releases](../../releases/latest).

All versions of ETS2 CarPlay. Get the current version from [Releases](../../releases/latest).

## 1.11.0 (2026-10-20)

- Neue Sprachen: Polnisch und Türkisch (Einstellungen › Allgemein › Sprache) – Oberfläche, Disponent, Navi-Ansagen und AI-Sprachassistent. Olivia und die anderen AI-Stimmen sprechen auch Polnisch und Türkisch
- Installer auf Deutsch, Englisch, Polnisch und Türkisch; die App startet in der Sprache, die im Setup gewählt wurde
- Bei einer anderen Sprache als Deutsch ist das Plugin-Menü im Spiel englisch
- Englisch: Abbiege-Ansagen und Auftragsmeldungen werden jetzt vollständig auf Englisch vorgelesen, Ländernamen auf Englisch, fehlende Texte ergänzt
- Home bearbeiten: Icons lassen sich über den Rand auf eine andere Seite ziehen und auf freie Stellen ablegen
- Sport-Einstellungen: Lieblingsteams mit Name und Wappen, verfolgte Spiele lassen sich dort entfernen
- Radio: neue Sender KIIS FM, Power 105.1, Q104.3, YOU FM, Antenne Bayern Top 40 und Radio Bollerwagen; I LOVE-Sender mit lesbaren Namen
- Weniger Arbeitsspeicher: Sprachmodell auf der Grafikkarte braucht etwa 0,8 statt 2,9 GB, die AI-Stimme wird nach 10 Minuten ohne Sprechen entladen
- Das Spiel schließt sich über Steam wieder ohne Verzögerung
- App-Icons: das Dashboard steht nicht mehr in der Liste

## 1.10.2 (2026-10-20)

- Karte: Firmengelände, Häfen, Autohäuser und Tankstellen zeigen ihre Hallen und Gebäude (vorher oft leere Flächen), mit passender Höhe für die 3D-Ansicht
- Karte: Bahnlinien als Option (Einstellungen › Karten › Karteninhalt)
- Karte: „Straßen nach Art einfärben“ als Schalter, Standard aus – im Google-Stil sind dann alle Straßen einheitlich. Wer die weißen Stadtstraßen mag, schaltet ihn ein
- Karte: Straßenbreite mit dem echten Mittelstreifen (vorher teils zu breit oder zu schmal), Hafenanlagen und Schiffe an der richtigen Stelle (bessere Wasserlinie in Häfen)
- Spurempfehlung: noch genauer auf Straßen ohne gemessene Kreuzung
- Einstellungen übersichtlicher: Karten aufgeteilt in „Karteninhalt“ und „Navigation & Hinweise“, eigene Seite „Fahrdaten & Kartenfehler“
- Die GitHub-Knöpfe sagen jetzt dazu, dass ein GitHub-Konto nötig ist

## 1.10.1 (2026-10-19)

- Spurempfehlung: Der Punkt unter der aktuellen Spur stimmt jetzt. Die App hat die Breite des Mittelstreifens bisher aus dem Straßentyp geschätzt und lag damit oft einen halben Fahrstreifen daneben, so stand der Punkt links, obwohl du rechts gefahren bist. Jetzt wird der Mittelstreifen beim Kartenbau an den Kreuzungen gemessen. Auch die Routenlinie liegt dadurch genauer auf der Spur
- Radio: Die Lautstärke folgt jetzt dem Gehör. Kleine Werte sind wirklich leise (1 % ist praktisch stumm), der Regler lässt sich über den ganzen Weg fein einstellen. Wer bisher eher leise gehört hat, muss etwas höher drehen
- Beenden: Nach dem Spielende schließt sich die App sofort. Steam zeigt ETS2 dadurch nicht mehr fast eine Minute lang als „wird ausgeführt“ an
- Sprachbefehl „Nächste Tankstelle“: nennt die Entfernung jetzt in Spiel-Kilometern, wie die Tank-App

## 1.10.0 (2026-10-19)

- Nacht: Die App lernt Sonnenauf- und -untergang vom Spiel. Mit Lichtautomatik merkt sie sich, wann das Licht morgens aus- und abends angeht, und nutzt diese Zeiten statt fester Uhrzeiten. Passt sich damit auch an Mods mit anderen Sonnenzeiten an
- Musik: Der Lautstärkeregler für Spotify (Windows-Mixer) ist wieder entfernt. Falls du ihn benutzt hast: im Windows-Lautstärkemixer Spotify wieder auf 100 % stellen

## 1.9.9 (2026-10-19)

- Karte: Gebäude haben ihre echte Grundfläche aus den Modellen des Spiels (Anbauten, Ecken, runde Silos) statt eines Rechtecks und stehen an der richtigen Stelle. Vorher lagen manche bis zu 40 m daneben, etwa quer über einer Straße. Auch die 3D-Gebäude nutzen die echten Umrisse
- Karte: Gebäude sind im dunklen Google-Stil klar zu erkennen, Firmengelände wirken nicht mehr wie ein grauer Schleier, 3D-Gebäude bleiben ruhig (Silos und Türme keine Riesenklötze)
- Tanken & Rasten: Entfernungen in Spiel-Kilometern wie im Navi und bei der Reichweite (ETS2 staucht die Welt, der Maßstab wird live gemessen). Auch Uhrzeiten an Tankstellen und Rastplätzen stimmen besser
- Navi: Wegweiser zeigen keine Spielkennungen mehr („traffic_rule…“)
- Licht: Mit Lichtautomatik im Spiel erkennt die App, ob die Scheinwerfer wirklich brennen (über die Armaturenbeleuchtung). Wichtig für „Nach Scheinwerfer“, „Nachts dunkler“ und die Kontrollleuchte. Nacht nach Uhrzeit jetzt 20:30–5:00
- Musik: Spotify-Lautstärke direkt in der Musik-App (Lautsprecher-Symbol antippen). Geht über den Windows-Mixer, ohne Spotify-Konto
- Telefon und Nachrichten zeigen einen roten Zähler auf dem Symbol. Verpasste Anrufe zählen nur neue, bis du die Anrufliste öffnest
- Bildkorrektur „Ausgewogen“ dimmt Weiß stärker, damit das Display im Cockpit nicht überstrahlt
- Das Plugin wird nach Spielende jetzt sicher aktualisiert (vorher blieb manchmal das alte liegen)

## 1.9.8 (2026-10-19)

- Direkt-Touch: Die Maus gehört wieder dem Spiel, solange es pausiert (Esc-Menü, Vollbildkarte, Frachtmarkt) oder eine Außenkamera aktiv ist. Danach ist Touch von selbst wieder da. Abschaltbar in der Leiste des Direkt-Touch-Modus („Maus frei“)
- Optional: Spotify und Radio halten an, solange das Spiel pausiert, und laufen danach weiter (Einstellungen › Musik › „Bei Spielpause anhalten“)
- Optional: Das Display im Truck wird nachts gedimmt wie in einem echten Auto (Einstellungen › Anzeige & Helligkeit › „Nachts dunkler“)

## 1.9.7 (2026-10-19)

- Karte im Google-Stil: Straßenfarben je Art wie Google Maps in CarPlay. Stadtstraßen weiß mit grauem Rand, Landstraßen, mehrspurige Straßen und Autobahnen graublau
- Karte: Autobahnkreuze sehen herausgezoomt ruhiger aus. Eng nebeneinander liegende Fahrbahnen verschmelzen zu einem Band statt dünner Streifen
- Karte: Firmengelände, Tankstellen, Rastplätze und Kreuzungsinseln zeigen ihre Teilflächen wie die Spielkarte (Hof, Parkflächen, Grün)
- Optional: 3D-Gebäude in der geneigten Ansicht (Einstellungen › Karten)
- Optional: Aussichtspunkte des Spiels und kleine Orte auf der Karte (Einstellungen › Karten)
- Navi: Kleine Orte helfen beim Abgleich mit den Wegweisern, die Richtung stimmt öfter mit dem Schild überein
- Navi: Abbiegepfeile auf der Fahrbahn nur noch dort, wo jeder Pfeil sicher auf einer eigenen Spur liegt
- Navi: Blinkst du schon zur richtigen Spur, kommt kein „Bitte einordnen“ mehr
- Fahrzeug-App: Kontrollleuchten wie im Cockpit (Blinker, Warnblinker, Licht, Fernlicht, Rundumleuchte, Wischer, Retarder) und Warnlampen mit Messwert (Bremsdruck, Öldruck, Motor heiß, Batterie, AdBlue). Bei echten Problemen während der Fahrt kommt eine Mitteilung
- Neues Widget „Live-Ticker“: das verfolgte Spiel oder ein Spiel deiner Lieblingsteams direkt auf dem Dashboard
- Sport: Anstoßzeit mit Datum („Heute 18:30“, „Di 21.10. 18:45“)
- Musik: Ein Tipp aufs Cover im Dashboard öffnet immer „Läuft gerade“
- Softwareupdate zeigt jetzt alle Neuerungen der installierten Version und frühere Versionen. Nach Updates wird bei jedem Start gesucht (höchstens alle drei Stunden)
- Schneller: Das Farbschema wird nicht mehr 20-mal pro Sekunde komplett neu berechnet. Dazu kleinere Aufräumarbeiten

## 1.9.6 (2026-10-18)

- Karte: Felder, Fels, Sand und Schnee aus dem Gelände des Spiels, mit runden, ruhigen Kanten. Im Google-Stil dezent wie bei Google Maps. Abschaltbar unter Einstellungen › Karten („Felder, Fels & Sand“)
- Karte: Wälder entstehen jetzt auch aus dicht stehenden Baumgruppen. Einzelne Bäume an Straßen und in Gärten bleiben weg
- Karte: Rastplätze und Parkreihen an der Autobahn werden gezeichnet
- Nah herangezoomt: Richtungspfeile auf den Spuren vor Kreuzungen, wie aufgemalt. Vor Kreuzungen und Ausfahrten sind die Spurlinien durchgezogen statt gestrichelt
- Navi: Kleeblatt- und Überflieger-Ausfahrten heißen jetzt „Ausfahrt rechts“ statt „Scharf rechts“. Die Spuranzeige ordnet Abzweige nach der Lage der Spuren (keine falschen Pfeile mehr bei Gabelungen)
- Navi: Ansage „Bitte rechts/links einordnen“, die Zielanzeige ist zweizeilig wie die Abbiegungen
- Optional: Kurvenwarnung bei zu hohem Tempo vor engen Kurven (Einstellungen › Karten)
- Straßenbahngleise zählen nicht mehr als Fahrspur
- Sport: 12 weitere Ligen: Frauen-Bundesliga, Europa League, Conference League, Championship, Serie A, Ligue 1, Eredivisie, Liga Portugal, Österreich, Schweiz, Süper Lig und die NFL. Premier League und LaLiga kommen jetzt aus aktuelleren Daten. Mit Live-Uhr, Torschützen und Tabellen
- Sport: Ein Spiel antippen = Live-Ticker nur für dieses Spiel, nochmal antippen schaltet ihn aus
- Sport: Ligen sortieren per Ziehen (in der App eine Liga kurz halten, in den Einstellungen am Griff ≡) und einzeln ausblenden
- „Navi verbessern“ sammelt auf Wunsch Fahrdaten (Route, Spurwahl, Abbiegungen) als Grundlage für bessere Spurempfehlungen

## 1.9.5 (2026-10-18)

- Abbiegungen kommen jetzt aus den Kreuzungsdaten des Spiels (Richtung der Fahrspuren und Blinker der KI). Stadtabbiegungen, dicht aufeinanderfolgende Kreuzungen und die letzte Abbiegung vor dem Ziel fehlen nicht mehr
- Wegweiser: Ausfahrten zeigen die Straßennummer als Schild und das Ziel von den echten Schildern, z. B. „Ausfahrt rechts · A1 Richtung Linz“. Die Ansage sagt es genauso
- Einfahrt aufs Firmengelände: „Links abbiegen · aufs Gelände: Firma“, das Ziel zeigt den Firmennamen
- Spurhinweise erscheinen nur noch, wenn die Spuren bis zu dir reichen. Auf Rastplatz, Rampe oder Beschleunigungsstreifen siehst du nicht mehr die Spuren der Autobahn dahinter
- Die Linie wechselt früher auf die Spur, die du brauchst. Die übrigen Spuren zeigen ihre echte Richtung (Hauptfahrbahn geradeaus statt schräg)
- Marker unter der Spur, auf der du gerade fährst: blau = richtig, orange = wechseln. Abschaltbar unter Einstellungen › Karten
- Neue App „Sport“: Bundesliga, 2. und 3. Liga, DFB-Pokal, Champions League, Premier League, LaLiga und Formel 1, mit Live-Spielständen, Tabellen und WM-Stand. Lieblingsteams bekommen einen Live-Ticker als Mitteilung
- Das Fahrzeug-Icon zeigt das Logo der Marke, die du fährst (in Farbe, Dunkel und Klar). Abschaltbar unter Einstellungen › App-Icons
- Optional: Spurempfehlung verbessern. Die App merkt sich Stellen, an denen die Empfehlung nicht passt, und du kannst sie auf GitHub teilen
- Behoben: Mitteilungen im Symbolstil „Klar“ hatten ein unsichtbares App-Icon

## 1.9.4 (2026-10-18)

- Routenlinie folgt in Kreisverkehren und an Auf- und Abfahrten der echten Fahrspur und liegt auf der Spur, die du brauchst
- Spurempfehlung schaut wie das Spiel über mehrere Kreuzungen voraus. Spuren werden jetzt auch angezeigt, wo es geradeaus weitergeht und sich die Spuren teilen, die anderen Spuren zeigen ihre eigene Richtung
- Ist die nächste Abbiegung weiter als 2 km weg, zeigt das Navi „Geradeaus“, die Abbiegung steht klein daneben
- Hinweis vor Grenzen: Lkw-Tempolimits, Maut, Dieselpreis und Zeitzone des nächsten Landes
- Hinweis vor Steigungen und Gefällen mit Höhenprofil und Rat je nach Gewicht
- Beides erscheint im Navi und im Dashboard und lässt sich unter Einstellungen › Karten abschalten, auch mit oder ohne Ansage
- Abbiegungen auf Wunsch selbst ansagen (Einstellungen › Karten), auf der Autobahn früher, in der Stadt später
- Route verlassen: „Route wird neu berechnet“, bis das Spiel die neue Route schickt
- Blitzer, Waagen und Mautstellen kommen als normale Mitteilung
- Einrichtung beim ersten Start: Spiel und Plugin, Bedienung, Stimme, Karte
- Aussprache: Kilometer, Kommazahlen und große Zahlen klingen natürlicher, dazu eine Liste für die englische Stimme. Olivia ist als empfohlene Stimme gekennzeichnet
- Mehr Abwechslung bei Anrufen, dazu ein paar neue geheime Nummern
- Schneller: Die Sprachausgabe rechnet in einem eigenen Thread, das Display ruckelt beim Sprechen nicht mehr. Kartendaten laden beim Start deutlich schneller
- Behoben: Einstellungen und Listen sprangen nach Änderungen nach oben, Hell/Dunkel brauchte zwei Klicks, Video-Lautstärke und Twitch, Zurück im Karten-Menü

## 1.9.3 (2026-10-18)

- Twitch-Streams starten jetzt von selbst. Pause und Lautstärke funktionieren auch bei Twitch
- Video-Lautstärke: Die Prozentanzeige war nach dem Tippen leer, und neue Videos starteten mit voller Lautstärke statt mit der eingestellten
- Handy-Steuerung: Das Bild kommt jetzt deutlich flüssiger an (vorher teils nur 2 Bilder pro Sekunde)
- Kreisverkehr: Die Anzeige bleibt nach der Einfahrt stehen und zählt bis zur Ausfahrt herunter
- Tempo im Navi wird orange, sobald du über deiner eingestellten Tempo-Warnung fährst. Im Google-Stil blieb es vorher immer weiß
- „Nach Scheinwerfer“ funktioniert jetzt auch mit dem automatischen Licht im Spiel
- Kartenstil und Symbole gehören zusammen: Apple Karten bringt die Apple-Symbole mit, Google die von Google Maps und Spotify
- Behoben: Hell/Dunkel brauchte zwei Klicks
- Behoben: Im Karten-Menü führte Zurück nach „Mehr …“ in die Einstellungen statt zur Karte
- Behoben: Einstellungen und Listen (Radio, Mitteilungen, Orte, Kalender, Video) sprangen nach jeder Änderung und während eines Downloads nach oben
- Die Karte zeichnet nach dem Umstellen einer Einstellung nicht mehr alles neu und braucht dabei weniger Speicher

## 1.9.2 (2026-10-18)

- Behoben: Nach dem Antippen eines Treffers in der Einstellungs-Suche war das ganze Bild verschoben. Das konnte auch passieren, wenn man in einer langen Liste weit unten etwas umgeschaltet hat
- Behoben: Version 1.9.1 startete nur mit leerem Bildschirm (1.9.1 wurde zurückgezogen)

## 1.9.0 (2026-10-18)

**Stimme**
- Olivia und die anderen AI-Stimmen sprechen sauberer (mehr Rechenschritte, trotzdem unter einer halben Sekunde je Navi-Satz)
- Aussprache-Liste: Zahlen, Uhrzeiten und Geldbeträge werden richtig gesprochen („ein Euro neunundsechzig“, „vierzehn Uhr dreißig“, „die zweite Ausfahrt“), Abkürzungen wie z. B., ca., GmbH oder ADR ausgeschrieben, Straßennummern als „A zehn“
- Orte heißen wie in einem deutschen Navi (München, Köln, Kopenhagen, Danzig …), ausländische Orte und die Firmen aus dem Spiel klingen verständlicher. Geprüft wurden alle Städte und Firmen des Spiels
- Stimmenauswahl aufgeräumt: die alte Stimme Kerstin ist raus (wer sie hatte, bekommt Olivia), die Windows-Stimmen heißen jetzt „Katja (Windows)“ usw.

**Einstellungen**
- Neue Suche oben in den Einstellungen: findet jede Option, auch in Unterseiten. Ein Treffer öffnet die Seite und markiert die Zeile
- Auf dem Truck-Bildschirm gibt es dafür eine Bildschirmtastatur, unten angedockt wie bei CarPlay, mit Umlauten, Ziffern und Zeichen

*English:*

**Voice**
- Olivia and the other AI voices sound cleaner (more processing steps, still under half a second per navigation sentence)
- Pronunciation list: numbers, times and prices are spoken correctly ("one euro sixty-nine", "fourteen thirty", "the second exit"), abbreviations are spelled out, road numbers read properly
- Places use the names a German navigation system uses (München, Köln, Kopenhagen …), foreign places and the game's companies are easier to understand. All cities and companies in the game were checked
- Voice list tidied up: the old voice Kerstin is gone (if you used it, you now get Olivia), the Windows voices are now labelled "Katja (Windows)" etc.

**Settings**
- New search at the top of the settings: finds every option, including sub-pages. A result opens the page and highlights the row
- On the truck screen there is an on-screen keyboard for it, docked at the bottom like in CarPlay, with umlauts, numbers and symbols

## 1.8.0 (2026-10-17)

**Navi**
- Kreisverkehre werden mit der Ausfahrt angesagt („Im Kreisverkehr 2. Ausfahrt“)
- Weniger falsche Abbiegehinweise: Kurven und Auffahrtschleifen gelten nicht mehr als Abbiegen. Die App nutzt dafür die Blinker-Angaben der Kreuzungen aus den Spieldaten
- Autobahnausfahrten heißen jetzt „Ausfahrt rechts/links“, Gabelungen weiter „Rechts/Links halten“
- Die Routenlinie liegt auf der eigenen Fahrbahn und ist glatter, ohne Sprünge zur Straßenmitte
- Ein abgekuppelter Anhänger wird auf der Karte angezeigt

**Karte**
- Wasser stimmt an vielen Stellen besser, unter anderem in Amsterdam. Die Bodendaten des Spiels wurden bisher falsch gelesen
- Neu: „Beim Fahren dazulernen“. Fährst du irgendwo, wo die Karte Wasser zeigt (Hafen, Firmengelände), wird es beim nächsten Erneuern der Karte zu Land. Die Daten bleiben auf deinem PC
- Kartenmenü: „Zurück“ springt nicht mehr zum Dashboard, klarere Auswahl bei „Fehler auf der Karte melden“, Ankunftszeit im selben Glas wie die Seitenleiste

**Stimme**
- Zehn neue Stimmen für Ansagen, Disponent und Assistent, zum Beispiel Olivia. Sie laufen direkt in der App auf dem Prozessor, auch auf mittleren PCs ohne starke Grafikkarte. Laden unter Einstellungen › Sprachassistent › Stimme (etwa 400 MB)

**Sonstiges**
- Video: Twitch-Links funktionieren, eigene Knöpfe für Pause, Spulen und Lautstärke
- Touch-Modus: Der Mauszeiger verschwindet nach 3 Sekunden ohne Bewegung (Plugin 1.6.0, wird von der App selbst eingespielt)

*English:*

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
