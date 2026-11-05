# Sondierbohrungen im Kanton Zürich

Daten aus Zollikon, Küsnacht und Erlenbach. Abschlussprojekt rstatsZH Kurs 012.

**Bericht**: [Sondierbohrungen im Kanton Zürich](https://rstatszh-k012.github.io/projekt-antonella-antonella/)  
**Datenquelle**: [Sondierbohrungen im GIS-Browser des Kantons Zürich](https://geo.zh.ch/s/a76cc86c-72f6-4bdd-89de-b852c3b0f750)  
**Code**: [Quarto Datei](https://github.com/rstatszh-k012/projekt-antonella-antonella/blob/main/docs/index.qmd)

## Einleitung

Dieses Projekt stellt Trainingsdaten sowie Anleitungen zur Darstellung von Sondierbohrungen und deren geologischen Merkmalen im Kanton Zürich bereit.

Es umfasst 171 Sondierbohrungen aus den Gemeinden Zollikon, Küsnacht und Erlenbach. Die vollständige Liste aller Sondierbohrungen im Kanton Zürich wird vom Amt für Abfall, Wasser, Energie und Luft (AWEL), Abteilung Gewässerschutz, geführt.

## Sondierbohrdatenbank

Die Access-Sondierbohrdatenbank des Kantons Zürich, die von der Sektion Grundwasser und Wasserversorgung geführt wird, enthält Daten zu über 18 000 Sondierbohrungen. Sie umfasst Bohrungen seit dem Jahr 1949 und wird laufend aktualisiert.

Weitere Informationen: Sondierbohrungen | opendata.swiss

## Motivation

Die Sektion Grundwasser und Wasserversorgung des Kantons Zürich ist für die Erhebung, Analyse, Speicherung und Bereitstellung geologischer Daten verantwortlich. Mit diesem Projekt werden ausgewählte Datensätze und Anleitungen bereitgestellt, um die Visualisierung und Auswertung von Sondierbohrungen zu erleichtern.

## Koordinaten

Seit 2017 ist LV95 der offizielle geodätische Bezugsrahmen für die amtliche Vermessung in der Schweiz.

Weitere Informationen: Lokale Bezugsrahmen Schweiz: LV95 und LHN95

## Tiefe der Bohrungen

Im Jahr 1960 wurde in Küsnacht eine Erdöl-Tiefbohrung bis in eine Tiefe von 2 692,5 m niedergebracht. Die Bohrung wurde in der Juraformation eingestellt. Aufgrund ihrer aussergewöhnlichen Tiefe wird sie in den grafischen Darstellungen nicht berücksichtigt, da sie die Skalierung und Vergleichbarkeit der übrigen Bohrungen erheblich verzerren würde.

## Ordnerstruktur

- `daten/raw/`: Export aus der Sondierbohrdatenbank, zwei CSV-Dateien (Semikolon-getrennt, UTF-8). Der Bericht verwendet `SondierbohrungenZollikonKüsnachtErlenbach.CSV`.
- `daten/processed/`: die bereinigte Tabelle `sondierbohrungen.csv` (wird beim Rendern des Berichts geschrieben) und das `codebook.csv` zu den Rohdaten.
- `docs/`: die Quarto-Datei des Berichts (`index.qmd`) und die gerenderte Webseite (`index.html`).
- `analyse/`: eine kurze Demo zur Darstellung der Bohrungen als Karte mit `sf`.
- `bilder/`: zwei Abbildungen aus der Projektarbeit, im Bericht nicht eingebunden.

## Mitwirkende

Vielen Dank an folgende Personen, die mitgewirkt haben:

[@larnsce](https://github.com/larnsce)

## Kontakt

- Antonella Toth, AWEL, Sektion Grundwasser und Wasserversorgung
