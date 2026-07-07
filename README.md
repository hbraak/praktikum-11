# Physik-Praktikum Jahrgang 11 (11NP)

Praktikumsanleitungen mit integrierten Protokollbögen für das 11. Schuljahr (Physiktechnik, Lore-Lorentz-Schule Düsseldorf). Stand: **Rev. 2** (Juli 2026).

> ✅ **Status:** Das Konzept wurde im Juli 2026 von den Physik-Lehrkräften der FK Technik im Konsens **übernommen** — ergänzt um optionale Leistungskontrollen (Präsentation, Plakat, Kolloquium, praktische Übung; nicht zu jedem Versuch, lehrkraftabhängig) und die **obligatorische Praktikumsmappe**. Ausblick SJ 2026/27: gemeinsame Festlegung von Progression und Kernerkenntnissen für die Versuche der Jg. 12/13 (siehe `Progression_Jg12-13_Entwurf.md`).

## Didaktisches Konzept

- **Dokumentation vor Ort**: Das Protokoll entsteht vollständig während der 135-minütigen Praktikumsstunde und wird am Ende abgegeben (Abgabevermerk mit Uhrzeit + Sichtvermerk auf jedem Bogen). Keine Hausarbeit → keine KI-generierten Berichte.
- **Praktikumsmappe (obligatorisch, Beschluss FK Technik)**: Alle Messprotokolle werden abgeheftet; die vollständige Mappe wird am Ende des Schuljahres vorgelegt.
- **Optionale Leistungskontrollen** (Beschluss FK Technik): nicht zu jedem Versuch, Form abhängig von der Lehrkraft — z. B. Präsentation, Plakat, Kolloquium, praktische Übung.
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

- `Praktikumskonzept_11NP_SJ2025-26.pdf` — Zusammenfassung des didaktischen Konzepts (Rahmen, KI-sicheres Protokoll, Scaffolding, Leistungskontrollen, QS) — Rev. 2
- `Kompetenzmatrix_Praktika_SJ2025-26.pdf` — kompetenzorientierte Matrix aller Versuche (UF / E / K)
- `Laborbuch_Praktikum11.docx` — das digitale Laborbuch als Word-Dokument (Stand der .md-Seiten)
- `_Review_135min_Scaffolding.md` — didaktisches Review + Änderungsprotokoll Rev. 1 + Rückmeldung FK Technik + offene Punkte
- `Progression_Jg12-13_Entwurf.md` — Gerüst für die gemeinsame Festlegung von Progression und Kernerkenntnissen Jg. 12/13 (Diskussionsgrundlage SJ 2026/27)
- `logo.jpeg`, `fahrbahn.png`, `dewar.png` — von den .tex-Dateien referenzierte Bilder

## Kompilieren

```bash
pdflatex <datei>.tex   # 2x ausführen; Bilder liegen im selben Ordner
```

ℹ️ Hinweis: `20260619_Praktikum_Drillachse_Auswertung` enthält eine **Musterlösung** — Link nicht an SuS weitergeben.
