# Physik-Praktikum Jahrgang 11 (11NP)

Praktikumsanleitungen mit integrierten Protokollbögen für das 11. Schuljahr (Physiktechnik, Lore-Lorentz-Schule Düsseldorf). Stand: **Rev. 1** (Juli 2026).

## Didaktisches Konzept

- **Dokumentation vor Ort**: Das Protokoll entsteht vollständig während der 135-minütigen Praktikumsstunde und wird am Ende abgegeben (Abgabevermerk mit Uhrzeit + Sichtvermerk auf jedem Bogen). Keine Hausarbeit → keine KI-generierten Berichte.
- **Praktikumsmappe**: Alle Protokollbögen werden gesammelt; die vollständige Mappe wird am Ende des Schuljahres vorgelegt.
- **Scaffolding mit Progression** (pro Versuch nur EINE neue Schwierigkeit):

| Stufe | Diagramm-Scaffold | Versuche |
|---|---|---|
| 1 | Achsen + Zahlenskala fertig | E1, E2 |
| 2 | Achsen beschriftet, Skalierung selbst wählen | E4b, E5, E6 |
| 3 | nur leeres Gitter | Federpendel |
| 4 | Millimeterpapier, komplett selbst | Drillachse |

- Rahmen: 12–14 SuS, 3er-/4er-Gruppen, 135 min pro Versuch.

## Versuche

| HJ | Datei | Versuch |
|---|---|---|
| 11.1 | `2025_11_1_konst_Geschw` | E1: Bewegung mit konstanter Geschwindigkeit |
| 11.1 | `2025_11_1_konst_Besch` | E2: Bewegung mit konstanter Beschleunigung |
| 11.1 | `2025_11_1_Erdbeschleunigung` | E3: Erdbeschleunigung (freier Fall) |
| 11.1 | `2025_11_1_Pendel` | E4: Fadenpendel |
| 11.1 | `2025_11_1_Pendel_Erdbeschleunigung` | E4b: g-Bestimmung, T²-l-Linearisierung (+ Herleitungs-Handout) |
| 11.1 | `2025_11_1_Waerme` | E5: Spezifische Wärmekapazität (Dewar) |
| 11.1 | `2025_11_1_Elektrolyseur` | E6: Elektrolyseur & Wirkungsgrad (+ schlanke Version) |
| 11.2 | `Prak11_2_Federpendel` | Federpendel: D statisch & dynamisch |
| 11.2 | `20260619_Praktikum_Drillachse` | Drillachse: Trägheitsmoment, Extremgeraden (+ `_Auswertung` = **Musterlösung**) |

## Weitere Dateien

- `Kompetenzmatrix_Praktika_SJ2025-26.pdf` — kompetenzorientierte Matrix aller Versuche (UF / E / K)
- `_Review_135min_Scaffolding.md` — didaktisches Review + Änderungsprotokoll Rev. 1 + offene Punkte
- `logo.jpeg`, `fahrbahn.png`, `dewar.png` — von den .tex-Dateien referenzierte Bilder

## Kompilieren

```bash
pdflatex <datei>.tex   # 2x ausführen; Bilder liegen im selben Ordner
```

ℹ️ Hinweis: `20260619_Praktikum_Drillachse_Auswertung` enthält eine **Musterlösung** — Link nicht an SuS weitergeben.
