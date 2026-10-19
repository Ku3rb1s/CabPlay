# ETS2 CarPlay

Deutsch · [English](README.en.md)

Apple CarPlay für das Navi-Display in Euro Truck Simulator 2. Auf dem Bildschirm im Cockpit läuft eine echte Navigation mit Spurempfehlung und Wegweisern, dazu Spotify, Radio, Live-Fußball, dein Auftrag, Fahrzeugdaten mit Kontrollleuchten, ein Blitzerwarner und mehr. Die Karte entsteht aus deinen eigenen Spieldateien, mit allen DLCs. Bedient wird mit der Maus direkt auf dem Display, über Tastenkürzel, Lenkrad-Tasten oder vom Handy aus.

![Dashboard](bilder/dashboard-dunkel.png)

Fan-Projekt, nicht verbunden mit SCS Software, Apple, Google oder Spotify. Die Marken gehören ihren Inhabern.

## Inhalt

- [Was es kann](#was-es-kann)
- [Bilder](#bilder)
- [Voraussetzungen](#voraussetzungen)
- [Installieren](#installieren)
- [Erster Start](#erster-start)
- [Bedienung im Spiel](#bedienung-im-spiel)
- [Die Karte](#die-karte)
- [Einzelne Funktionen genauer](#einzelne-funktionen-genauer)
- [Updates](#updates)
- [Häufige Fragen](#häufige-fragen)
- [Deinstallieren](#deinstallieren)
- [Lizenzen und Danke](#lizenzen-und-danke)

## Was es kann

### Navigation wie im echten Auto

- Die Route kommt aus dem Navi des Spiels. Abbiegungen erkennt die App aus den Kreuzungsdaten des Spiels, also so, wie das Spiel selbst abbiegt
- Spurempfehlung: Welche Spur du brauchst, siehst du vor jeder Kreuzung und Ausfahrt. Ein Marker zeigt, auf welcher Spur du gerade fährst
- Wegweiser: „Ausfahrt rechts · A1 Richtung Linz“ mit Straßennummer und Ziel von den echten Schildern
- Ampeln mit Restzeit, Tempolimit, Ankunftszeit, Rastplätze entlang der Strecke, Hinweise zu Grenzen und Steigungen
- Ansagen auf Deutsch oder Englisch, auch mit natürlich klingenden KI-Stimmen. Wer schon zur richtigen Spur blinkt, wird nicht unnötig ermahnt
- Optional: Warnung vor engen Kurven, wenn du zu schnell bist

### Eine Karte aus deinem Spiel

- Gebaut aus deinen Spieldateien, mit allen DLCs. Nach Spiel-Updates baut die App sie selbst neu
- Straßen so breit, wie sie Spuren haben, Brücken über den Straßen darunter, nah herangezoomt Fahrbahnmarkierungen und Abbiegepfeile
- Gebäude, Wasser, Wälder, Felder, Fels und Sand, Firmengelände mit Hof- und Parkflächen
- Zwei Stile wie Google Maps und Apple Karten, hell und dunkel, flach oder schräg von hinten. Im Google-Stil haben die Straßen dieselben Farben wie Google Maps in CarPlay
- Optional: 3D-Gebäude, kleine Orte, Aussichtspunkte, versteckte Straßen und geheime Abkürzungen

### Apps

- **Spotify** mit Cover, Steuerung, Mediathek, Warteschlange und mitlaufenden Songtexten. Geht auch, wenn das Spiel gerade nicht läuft
- **Radio** mit über 90 Sendern (deutsche, englische, I LOVE RADIO und die Sender aus deinem Spiel), dazu eigene Sender
- **Sport** mit Live-Spielständen, Torschützen und Tabellen: Bundesliga bis 3. Liga, DFB-Pokal, Champions League, Premier League, LaLiga, Serie A und weitere Ligen, NFL und Formel 1. Für Lieblingsteams und einzelne Spiele gibt es einen Live-Ticker als Mitteilung
- **Auftrag**: Strecke, Lieferfrist, Puffer, Lohn, Kosten unterwegs und wann die nächste Pause fällig ist
- **Fahrzeug**: Tempo, Gang, Tank, AdBlue, Zustand von Zugmaschine und Anhänger, dazu Kontrollleuchten wie im Cockpit (Blinker, Licht, Fernlicht, Retarder) und Warnlampen für Bremsdruck, Öldruck, Motortemperatur und Batterie
- **Blitzer**, Waagen und Mautstellen mit Warnton. Blitzer, die dich erwischt haben, merkt sich die App
- **Wetter** für den Ort, an dem du gerade bist
- Telefon mit Disponent und Pannenhilfe, Nachrichten, Kalender, Fahrtenbuch, Tanken & Rasten, Videos von YouTube und Twitch
- Ein Dashboard mit Widgets, das du dir selbst zusammenstellst (zum Beispiel Navi, Musik oder der Live-Ticker), dazu eigene Hintergründe und Symbole

### Sprachassistent (optional)

Home-Knopf gedrückt halten und reden, zum Beispiel „Schaffe ich die Lieferung noch?“ oder „Spiel was von AC/DC“. Das Sprachmodell läuft komplett auf deinem PC, kostet nichts und braucht kein Konto. Es wird nur geladen, wenn du es in den Einstellungen anforderst (etwa 1,5 bis 3 GB), und lässt sich jederzeit wieder entfernen. Ohne den Download gibt es feste Sprachbefehle.

### Bedienung

- Touch-Modus im Spiel: CarPlay als Fenster oder direkt auf dem Display im Cockpit anklicken. Kopf- und Kabinenbewegungen rechnet die App heraus
- Tastenkürzel für alles Wichtige, auch für Lenkrad-Tasten
- Handy-Steuerung im WLAN, verbunden per QR-Code
- Ein Editor-Fenster am PC zum Einrichten

### Sonst noch

- Deutsch und Englisch, metrische und US/UK-Einheiten, 12- oder 24-Stunden-Uhr
- Updates kommen automatisch. Nach einem Spiel-Update baut die App die Karte selbst neu
- Am Spiel wird nichts verändert: keine Mods in den Spieldateien, keine Änderung an der `config.cfg`

## Bilder

| | |
|---|---|
| ![Navi hell](bilder/navi-hell.png) | ![Navi dunkel](bilder/navi-dunkel.png) |
| Navi im Google-Stil mit Spurempfehlung, hell | Navi im Google-Stil, dunkel |
| ![Apple-Stil dunkel](bilder/karte-apple-dunkel.png) | ![Dashboard hell](bilder/dashboard-hell.png) |
| Navi im Apple-Stil, dunkel | Dashboard, hell |
| ![3D-Gebäude](bilder/karte-3d.png) | ![Gelände](bilder/karte-gelaende.png) |
| 3D-Gebäude und Firmengelände (Option) | Wälder, Fels und Serpentinen |
| ![Sport](bilder/sport.png) | ![Home](bilder/home.png) |
| Sport mit Live-Spielständen | Home-Bildschirm |
| ![Fahrzeug](bilder/fahrzeug.png) | ![Auftrag](bilder/auftrag.png) |
| Fahrzeug mit Kontrollleuchten | Auftrag |
| ![Radio](bilder/radio.png) | ![Wetter](bilder/wetter.png) |
| Radio | Wetter |
| ![Blitzer](bilder/blitzer.png) | |
| Blitzer | |

## Voraussetzungen

- Windows 10 oder 11, 64 Bit
- Euro Truck Simulator 2 in der aktuellen Version (Steam), DirectX 11
- Etwa 350 MB Platz, mit Sprachassistent entsprechend mehr

## Installieren

1. Euro Truck Simulator 2 beenden.
2. Unter [Releases](../../releases) die neueste Version herunterladen. Entweder den Installer `ETS2-CarPlay-Setup-<Version>.exe` (Ordner frei wählbar) oder die ZIP, die du nur entpackst und dann `ETS2 CarPlay.exe` startest.
3. Die App sucht ETS2 über Steam und kopiert das Plugin selbst ins Spiel. Ob das geklappt hat, steht in der App unter Einstellungen › Allgemein › Plugin & Spiel.

## Erster Start

1. ETS2 starten. Beim ersten Mal fragt das Spiel, ob es SDK-Plugins laden darf. Mit OK bestätigen. Ab dann startet das Spiel die App von selbst mit.
2. In einen Truck mit Navi-Bildschirm steigen. CarPlay erscheint auf dem Display.
3. Mit Strg + F8 öffnest du das CarPlay-Menü im Spiel. Dort wählst du, auf welchen Bildschirmen CarPlay laufen soll, und drückst Anwenden.
4. Für die Navigation ein Ziel im Spiel-Navi setzen oder einen Auftrag annehmen.

Beim allerersten Start baut die App die Karte aus deinen Spieldateien. Das dauert ein, zwei Minuten und läuft im Hintergrund.

## Bedienung im Spiel

| Tasten | Was passiert |
|---|---|
| Strg + F8 | CarPlay-Menü im Spiel (Bildschirme, Touch, Status) |
| Strg + Alt + M | Touch-Modus an oder aus, dann geht CarPlay mit der Maus |
| Strg + Alt + E | Editor-Fenster am PC |
| Strg + Alt + P | Musik abspielen oder pausieren |
| Strg + Alt + Bild↑ / Bild↓ | Vorheriger oder nächster Titel |
| Strg + Alt + Pfeiltasten, Enter, Rücktaste | Durch CarPlay blättern, auswählen, zurück |
| Strg + Alt + H | Home-Bildschirm |
| Strg + Alt + V | Sprachbefehl |

Alle Kürzel kannst du in der App ändern.

Im Touch-Modus gibt es zwei Varianten. Entweder liegt CarPlay als Fenster über dem Spiel, das du verschieben und vergrößern kannst. Oder du kalibrierst einmal das Display im Cockpit (vier Ecken anklicken) und klickst danach direkt auf den Bildschirm im Truck.

Fürs Handy schaltest du in den Einstellungen die Handy-Steuerung ein und scannst den QR-Code. Handy und PC müssen im selben WLAN sein.

## Die Karte

Die App liest die Karte aus den Dateien deines Spiels und baut sie nach Spiel-Updates neu. Was angezeigt wird, stellst du in den Karten-Einstellungen ein: Grünflächen, Wald, Wiesen, Felder, Fels und Sand, Wasser, Gebäude, Firmengelände, Straßennummern, Fahrbahnmarkierungen und so weiter.

Brücken und Überführungen liegen sichtbar über den Straßen darunter. Straßen sind so breit, wie sie Spuren haben, Einbahnstraßen und Auffahrten bekommen Pfeile. Nah herangezoomt siehst du Fahrbahnmarkierungen, vor Kreuzungen durchgezogen, und die aufgemalten Abbiegepfeile auf den Spuren. Firmengelände, Tankstellen und Rastplätze zeigen ihre Teilflächen wie die Spielkarte.

Ab Werk aus, aber jederzeit einschaltbar:
- 3D-Gebäude: in der geneigten Ansicht als Klötze mit der Höhe aus dem Spiel
- Kleine Orte: Dörfer und Kulissenorte, die im Spiel keine eigene Stadt sind. Fürs Navi nutzt die App sie immer, um die Richtung mit den Wegweisern abzugleichen
- Aussichtspunkte: die Aussichten, die man im Spiel entdecken kann
- Versteckte Straßen: Straßen, die das Spiel auf seiner eigenen Karte nicht zeigt. Meist Kulisse oder nur für den KI-Verkehr
- Geheime Abkürzungen: die Strecken, die man im Spiel erst entdecken muss

Das Wasser für Meer, Flüsse und Seen kommt aus dem Spiel selbst, das offene Meer aus Natural Earth. Flüsse und Seen sind noch nicht überall genau.

ETS2 staucht Europa ziemlich zusammen, Dover und Calais liegen zum Beispiel nur ein paar Kilometer auseinander. Die Karte zeigt die Welt so, wie sie im Spiel ist.

## Einzelne Funktionen genauer

### Spotify

Ohne Einrichtung zeigt CarPlay, was in der Spotify-App am PC läuft (Titel, Interpret, Cover), und steuert Abspielen, Pause und Titelwechsel.

Für die Mediathek mit Playlists, zuletzt gehörten Titeln, Lieblingssongs, Suche und Warteschlange verbindest du einmal dein eigenes Spotify-Konto:
1. Auf [developer.spotify.com/dashboard](https://developer.spotify.com/dashboard) mit deinem Spotify-Konto anmelden und „Create app“ wählen. Name ist egal, als API „Web API“ ankreuzen.
2. Als Redirect URI genau `http://127.0.0.1:8724/callback` eintragen und speichern.
3. Die Client ID der App kopieren.
4. In CarPlay im Editor-Fenster unter Einstellungen › Musik › Spotify-Mediathek die Client ID einfügen, auf Verbinden klicken und im Browser zustimmen.

Die Anmeldung bleibt auf deinem PC (`%APPDATA%\ETS2 CarPlay`), es läuft nichts über fremde Server. Zum Abspielen aus der Mediathek brauchst du Spotify Premium und eine offene Spotify-App. Die Songtexte kommen von LRCLIB und laufen mit, wenn es für den Titel synchronisierte Texte gibt.

### Radio

Die Sender sind nach Deutsch, Englisch, I LOVE RADIO, ETS2 und Eigene sortiert. Unter ETS2 stehen die Sender, die du im Spiel eingetragen hast. Eigene Sender fügst du im Editor-Fenster mit „+ Sender“ hinzu: Namen suchen (Senderverzeichnis radio-browser.info) oder eine Stream-Adresse eintragen. Radio und Spotify stoppen sich gegenseitig, und mit den Lenkrad-Tasten wechselst du den Sender.

### Sport

Spielstände, Torschützen, Tabellen und Formel 1 ohne Konto. Lieblingsteams wählst du in der Tabelle mit einem Tipp auf den Verein, einzelne Spiele verfolgst du mit einem Tipp auf das Spiel. Bei Anpfiff, Toren, Halbzeit und Abpfiff kommt dann eine Mitteilung. Die Ligen sortierst du per Ziehen und blendest aus, was dich nicht interessiert. Als Widget zeigt der Live-Ticker dein Spiel direkt auf dem Dashboard.

### Video

YouTube- und Twitch-Links laufen auf dem Display im Truck. Link kopieren und in der Video-App einfügen oder vom Handy schicken. Wenn du willst, pausiert das Video während der Fahrt.

### Sprachbefehle und Ansagen

Strg + Alt + V (oder den Home-Knopf gedrückt halten) startet einen Sprachbefehl, zum Beispiel „Nächste Tankstelle“, „Wie weit noch“, „Wetter“, „Disponent anrufen“ oder „Nächster Titel“. Ohne Sprachassistent erkennt die Windows-Spracherkennung feste Befehle, mit Sprachassistent kannst du frei reden. Navi-Ansagen sprechen die Windows-Stimmen oder eine der zehn zusätzlichen AI-Stimmen (zum Beispiel Olivia). Die laufen direkt in der App auf dem Prozessor, auch auf mittleren PCs, und werden nur auf Wunsch geladen (etwa 400 MB). Die Lautstärke ist für Ansagen und Warntöne getrennt einstellbar.

### Auftrag, Fahrzeug und Bus

Der Disponent meldet sich mit Nachrichten und Anrufen. Fährst du einen Reisebus aus dem Coach-DLC, merkt das die App: kein Anhänger, Fahrt statt Fracht, Ankunftsfrist und Bushaltestellen auf der Karte.

### Wetter

Das echte Wetter der Stadt, durch die du gerade fährst. Es kommt von Open-Meteo, bei Ausfällen von MET Norway. Übertragen wird nur der Ort, ein Konto braucht es nicht.

### Mods

Firmen- und Städtenamen aus Mods, die im Spiel eingeschaltet sind (zum Beispiel echte Firmennamen), erscheinen auch auf der Karte. Die App liest dafür nur die Namensdateien. Abschaltbar unter Einstellungen › Karten.

### Kartenfehler melden

Stimmt die Karte an einer Stelle nicht, etwa Wasser, wo Land ist, wählst du im Kartenmenü „Fehler auf der Karte melden“. Position und ein Bild landen in `%APPDATA%\ETS2 CarPlay\map-reports`. Gern hier auf GitHub als Issue anhängen.

### Einstellungen sichern

Unter Einstellungen › Allgemein › „Einstellungen sichern …“ schreibst du alle Einstellungen, gelernten Blitzer und Videos in eine Datei. Praktisch, wenn du den PC wechselst.

## Updates

Bei jedem Start schaut die App nach einer neuen Version (höchstens alle drei Stunden, Einstellungen › Allgemein › Softwareupdate). Sie lädt das Update und installiert es beim Beenden, das Plugin gleich mit. Deine Einstellungen bleiben erhalten. Jede Datei wird vorher per SHA-256 geprüft. Was neu ist, steht nach dem Update unter Softwareupdate, frühere Versionen gleich darunter.

## Häufige Fragen

**Windows warnt beim Start („Der Computer wurde durch Windows geschützt“).**
Die Programmdatei ist nicht digital signiert, deshalb kennt Windows den Herausgeber nicht. Auf „Weitere Informationen“ und dann „Trotzdem ausführen“ klicken. Wer sichergehen will, vergleicht die Prüfsumme mit der `SHA256SUMS.txt` im Release:

```powershell
Get-FileHash .\ETS2-CarPlay-Setup-*.exe -Algorithm SHA256
```

**CarPlay erscheint nicht im Spiel.**
ETS2 einmal ganz beenden und neu starten, die SDK-Abfrage bestätigen. In der App unter Einstellungen › Allgemein › Plugin & Spiel nachsehen, ob das Plugin installiert ist. Dann im Spiel mit Strg + F8 den Bildschirm auswählen und Anwenden drücken.

**Die Karte ist leer oder alt.**
Einstellungen › Info › Karte neu erzeugen. Nach Spiel-Updates macht die App das von selbst.

**Kostet das Leistung?**
Kaum. Die App zeichnet nur neu, was sich ändert, und gibt das Bild über die Grafikkarte ans Spiel. Auf einem normalen Spiele-PC merkt man keinen Unterschied.

**Geht das auch mit American Truck Simulator?**
Nein, nur mit Euro Truck Simulator 2.

## Deinstallieren

Entweder über Windows unter Einstellungen › Apps (wenn du den Installer benutzt hast), in der App unter Einstellungen › Allgemein › ETS2 CarPlay deinstallieren, oder bei der ZIP-Version mit `Deinstallieren.cmd` im Programmordner.

Entfernt werden das Plugin im Spiel, die Platzhalter in `Dokumente\Euro Truck Simulator 2\ETS2CarPlay` und der Programmordner. Deine Einstellungen (`%APPDATA%\ETS2 CarPlay`) nur, wenn du das willst. Am Spiel selbst bleibt alles, wie es war.

## Lizenzen und Danke

- Teile des Spielplugins stammen aus dem [ETS2LA-Plugin](https://github.com/ETS2LA/plugin) (MIT).
- Die Kartendaten liest der [TruckSim-Kartenparser](https://github.com/truckermudgeon/maps) (GPL-3.0) aus den Spieldateien. Der Quellcode liegt jedem Paket bei (`resources/mapdata/parser/QUELLE.txt`).
- Meeresflächen: [Natural Earth](https://www.naturalearthdata.com/) (gemeinfrei). Liste der Dörfer im Spiel: krmarci, aus dem TruckSim-Kartenparser.
- Sport: [OpenLigaDB](https://www.openligadb.de/) (deutsche Ligen), ESPN (weitere Ligen, NFL), [Jolpica](https://jolpi.ca/) (Formel 1). Markenlogos der Trucks: Wikimedia Commons.
- Radiosender: [radio-browser.info](https://www.radio-browser.info/), Songtexte: [LRCLIB](https://lrclib.net/), Wetter: [Open-Meteo](https://open-meteo.com/) und MET Norway.
- Sprachassistent: whisper.cpp und llama.cpp (MIT), Sprachmodell Qwen (Apache 2.0), Stimmen Supertonic 3 von Supertone (OpenRAIL-M) über ONNX Runtime (MIT).
- Schrift: [Inter](https://github.com/rsms/inter) (SIL Open Font License 1.1).
- Gebaut mit [Electron](https://www.electronjs.org/).
