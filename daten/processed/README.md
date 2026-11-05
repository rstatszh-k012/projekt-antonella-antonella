# Bereinigte Daten

## sondierbohrungen.csv

Bereinigte Tabelle aus dem Bericht (`docs/index.qmd`, Abschnitt "Daten"): 170 Sondierbohrungen aus Zollikon, Küsnacht und Erlenbach mit zehn Spalten. Die Datei wird beim Rendern des Berichts neu geschrieben.

| Spalte | Herkunft in den Rohdaten | Einheit |
|---|---|---|
| Gemeinde | Gemeinde, ohne den Zusatz "(ZH)" | |
| east_coordinate_lv95 | XKOORD | m, LV95 |
| north_coordinate_lv95 | YKOORD | m, LV95 |
| Terrainkote_m | Terrainkote der Bohrung | m ü. M. |
| Jahr | Ausführungsjahr | |
| Bohrtiefe_m | Bohrtiefe; die Tiefbohrung Küsnacht 1960 (2692.5 m) ist auf NA gesetzt | m |
| Felstiefe | Felstiefe | m |
| Grundwasserspiegelkote | Grundwasserspiegelkote; die vertauschten Werte für Erlenbach 1987 sind zurückgetauscht | m ü. M. |
| Flurabstand_m | Flurabstand an diesem Tag | m |
| Firma | Firma; "Dr. Heinrich Jäckli AG" vereinheitlicht zu "Jäckli Geologie AG" | |

## codebook.csv

Beschreibt die Spalten der Rohdaten in `daten/raw/` (Semikolon-getrennt): Variablenname, Beschreibung, Typ, Einheit.
