# HUD Generator

Eine statische Seite (`index.html`), die bei jedem Aufruf ein neues, animiertes Gaming-HUD baut.

## Was zufällig erzeugt wird

- **Genre**: Sci-Fi, Cyberpunk, Fantasy, Tactical oder Arcade – mit eigener Farbwelt, Schrift, Rahmenstil, Hintergrund und Vokabular (Stats, Bosse, Quests, Log-Zeilen, Achievements)
- **Layout**: zufällige Aufteilung des Rasters (BSP), auf dem Handy gestapelt
- **24 Widgets**: Radar, Oszilloskop, Spektrum, Reaktor-Ringe, Hex-Karte, Telemetrie/EKG, Netzwerk, Log, Vitals,
  Zielerfassung, Globus, Heatmap, Score, Minimap, Hotbar, Hologramm, Boss-Lebensbalken, Questlog, Kompass,
  Leaderboard, Warp-Tunnel, Waffe/Munition, Audio-Ring, Downloads
- **Live-Ereignisse**: Warnungen mit Screen-Shake, Achievements, Loot, Level-Up, Killfeed, Glitches

## Bedienung

| Taste / Button | Funktion |
| --- | --- |
| **R** / REROLL | neues UI |
| **G** / GENRE | Genre festlegen (Mix → Sci-Fi → Cyberpunk → Fantasy → Tactical → Arcade) |
| **A** / AUTO | alle 10 s ein neues UI (Showcase-Modus) |
| **M** / SOUND | Soundeffekte an/aus |
| Klick auf ein Panel | nur dieses Widget tauschen |
| LINK | Link auf genau dieses UI kopieren (`?seed=123&genre=fantasy`) |

Keine Abhängigkeiten – `index.html` im Browser öffnen oder per GitHub Pages ausliefern.
