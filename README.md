# Immo-Deals – Meta Ray-Ban Display Web-App

Kleine Web-App (eine Datei, `index.html`) für das Meta Ray-Ban Display, die die
aktuellen Frankfurter Immobilien-Deals nach Bruttomietrendite anzeigt.

- **Anzeige:** 600×600, additives Display (schwarzer Hintergrund), große helle Schrift.
- **Navigation:** ▲/▼ = nächster/voriger Deal, ⏎ = Liste ↔ Detail, ◀ = zurück zur Liste.
- **Daten:** `deals.json` (Top 30, täglich automatisch aktualisiert). Enthält nur
  öffentliche Inseratsdaten (Rendite, Preis, m², Stadtteil, Quelle, Titel, Link).

Gehostet über GitHub Pages. Erzeugt vom Immo-Deal-Scanner (`scan.py`).
Rendite ist eine Schätzgröße (Annahme 14 €/m²), keine Anlageberatung.
