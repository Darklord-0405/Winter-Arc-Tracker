# Winter Arc Tracker

Habit-Tracker für den Winter Arc 2026/27: Jeden Tag Gewohnheiten abhaken, Serien aufbauen und sehen, wie konsequent du durchziehst.

## Funktionen

- **Kategorien**: Sport, Schule, Tägliche Hygiene, Ernährung und Mindset, jede mit eigener Farbe. Kategorien lassen sich anlegen, umbenennen, sortieren und umfärben.
- **Heute-Ansicht**: Gewohnheiten nach Kategorie gruppiert, mit Fortschrittsring und Zähler pro Kategorie. Schnellvorschläge zum Hinzufügen neuer Gewohnheiten.
- **Wochenübersicht**: Alle Gewohnheiten der Woche auf einen Blick, nach Kategorien unterteilt.
- **Arc-Heatmap**: Jeder Tag des Arcs als Feld, Orange heißt alles geschafft.
- **Serien und Quote**: aktuelle Serie, beste Serie und Gesamtquote.
- **Hell, Dunkel und Auto**: Darstellung folgt dem System oder wird manuell gewählt.
- **Geräte-Sync**: Läuft der Tracker als Artifact in claude.ai, gleicht er sich live zwischen allen Geräten ab, auf denen du mit demselben Claude-Konto angemeldet bist. Pro Tag gewinnt die neuere Änderung, offline gemachte Änderungen werden nachgeholt.

## Nutzung

Die ganze App steckt in einer einzigen Datei: `index.html`. Öffne sie im Browser, fertig.

Außerhalb von claude.ai (zum Beispiel lokal oder über GitHub Pages) speichert der Tracker im Browser des jeweiligen Geräts. Der Status oben zeigt dann „Nur dieses Gerät“. Der Geräte-Sync ist nur in der claude.ai-Version aktiv.

### Auf dem iPhone als App

1. `index.html` im Safari öffnen (zum Beispiel über GitHub Pages).
2. Teilen-Symbol tippen und „Zum Home-Bildschirm“ wählen.

### GitHub Pages aktivieren

In den Repository-Einstellungen unter **Settings → Pages** als Quelle den Branch `main` und den Ordner `/ (root)` wählen. Die App ist danach unter `https://darklord-0405.github.io/Winter-Arc-Tracker/` erreichbar.
