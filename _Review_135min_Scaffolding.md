# Review der Praktikumsanleitungen SJ 2025/26

**Prüfkriterien** (aus dem didaktischen Konzept):
1. Dokumentation vollständig **vor Ort** in 135 min (KI-sicher, keine Hausarbeit)
2. **Scaffolding**: Tabellenköpfe, Diagrammachsen, Skalierung vorgegeben
3. **Progression**: Scaffolding nimmt mit Lernzuwachs ab, Anforderungen steigen
4. Rahmen: 12–14 SuS, 3er-/4er-Gruppen (3–5 Gruppen)

---

## Gesamtbefund

| Versuch | Seiten | Aufgaben | Diagramm-Scaffold | 135-min-Risiko |
|---|---|---|---|---|
| E1 konst. Geschwindigkeit | 5 | 6 | Achsen + Skala fest ✅ | gering |
| E2 konst. Beschleunigung | 6 | 6 | Achsen + Skala fest ✅ | gering |
| E3 Erdbeschleunigung | 7 | 5 + 3★ | teilweise | gering (aber 7 Seiten) |
| E4 Fadenpendel | 6 | 3 + 3★ | kein Diagramm nötig | gering |
| E4b Pendel → g | 6 | Boxen | T²-l-Achsen + Skala fest ✅ | mittel |
| E5 Wärme | 7 | 7 Boxen | Achsen + Zahlenskala fest ✅ | **HOCH** ⚠️ |
| E6 Elektrolyseur | 5 (+schlank) | 7 | pgfplots, Skala fest ✅ | mittel |
| Federpendel (11.2) | 6 | 3 + 5★ | **kein Diagramm-Raster** | gering |
| Drillachse (11.2) | 8 | 5 + ★ (10 Teilaufg.) | pgfplots, Skala fest | **HOCH** ⚠️ |

**Positiv:** Einheitliche Struktur, Protokollbögen mit fertigen Tabellenköpfen überall vorhanden, Boxen-System, ★-Differenzierung, Elektrolyseur existiert bereits in schlanker Version.

---

## Änderungsvorschläge

### A) Zeitkritische Versuche entschärfen

**E5 Wärme (größtes Risiko):**
- Teil 1 (15 min Messzeit) + Umbau + Teil 2 (3 Wassermassen je bis ΔT=10 K, mit Abkühl-/Neubefüllzeiten) + 2 Diagramme + Gesamtauswertung passt kaum in 135 min.
- **Vorschlag:** Teil 2 **arbeitsteilig**: jede Gruppe misst nur EINE Wassermasse (100/150/200 g nach Gruppenzuteilung), Ergebnisse werden an der Tafel gesammelt und von allen übernommen. Nebeneffekt: individuelle Gruppendaten = KI-sicher, plus Kommunikationskompetenz.
- Alternativ: Teil 2 auf 2 Massen (100 g / 200 g) kürzen.

**Drillachse:**
- 5 Abstände × 3 Wiederholungen = 15 Zeitmessungen à ~35 s plus Umbauten ≈ 30 min; danach r²/J-Berechnung (×5), Diagramm, Steigungsdreieck, Fehlerbalken an ALLEN Punkten, Extremgeraden, Reflexion → sehr voll.
- **Vorschlag:** Wiederholungen 3 → 2 (Mittelwert aus 2); Fehlerbalken nur am kleinsten und größten r (reicht für Extremgeraden); Aufgabe 6 (Reflexion) bleibt ★.
- Rollenkarten für 3er-Gruppen (Auslenken/Stoppen/Protokoll) sparen Umbauzeit.

**E3 Erdbeschleunigung:** 7 Seiten → Theorieteil auf 1 Seite straffen (Ziel ≤ 6 Seiten). Weniger Blättern = weniger Zeitverlust.

**E1 (Einstieg):** Aufgabe 6 (Messunsicherheit) zur ★-Aufgabe umwidmen — beim allerersten Praktikum Fokus auf Messen + Tabelle + Diagramm.

### B) Progression explizit machen (Scaffolding-Stufen)

Vorschlag für ein 4-Stufen-Raster, das je Versuch ausgewiesen wird:

| Stufe | Tabelle | Diagramm | eingeführt ab |
|---|---|---|---|
| 1 | Kopf + Einheiten fertig | Achsen + Zahlenskala fertig | E1–E2 |
| 2 | Kopf fertig | Achsen beschriftet, **Skalierung selbst** | E4b–E6 |
| 3 | Spaltengrößen selbst wählen | nur leeres Gitter | Federpendel |
| 4 | leere Fläche/Millimeterpapier | komplett selbst | Drillachse / 12.1 |

**Ist-Zustand weicht ab:** E4b, E5, E6 UND Drillachse haben alle noch feste Zahlenskalen (Stufe 1). Die Progression findet aktuell bei den *Methoden* statt (Linearisierung, Fehlerbalken), aber nicht beim *Scaffolding*.
- **Vorschlag konkret:** Bei E6 (Elektrolyseur) und Drillachse die Achsenzahlen entfernen, nur Gitter + Achsenbeschriftung stehen lassen; dafür Hilfebox „So wählst du eine Skalierung". Bei der Drillachse ist die neue Methode (Extremgeraden) anspruchsvoll — wenn beides zu viel ist: Skala auf dem Hauptdiagramm offen, ★-Zusatzblatt mit fertiger Skala als Rettungsanker.
- Grundsatz: **pro Versuch nur EINE neue Schwierigkeit** (neue Methode ODER weniger Scaffold).

**Federpendel:** Es fehlt ein Diagramm-Raster im Protokoll (Stufe 3: leeres Gitter ergänzen), sonst weichen die Gruppen auf lose Blätter aus → schwer einzusammeln.

### C) KI-Sicherheit / Vor-Ort-Dokumentation stärken

1. **Zeitleiste aufs Deckblatt** jedes Protokollbogens, z. B.:
   `0–15 Aufbau · 15–55 Messung · 55–115 Auswertung · 115–135 Ergebnisbox + Abgabe`
2. **Abgabevermerk** auf dem Protokollbogen: „Abgegeben am ____ um ____ Uhr, Sichtvermerk Lehrkraft: ____" — dokumentiert die Vor-Ort-Erstellung.
3. **Individuelle Datensätze erzwingen:** Jede Gruppe bekommt leicht andere Parameter (z. B. Drillachse: Ziel-Abstände 4/8/12/16/20 vs. 5/10/15/20/25 cm; Wärme: zugeteilte Masse). Identische Berichte fallen sofort auf.
4. **Ergebnisbox** (gelb) als Pflichtfeld am Ende: eigenes Zahlenergebnis + 2 Sätze Deutung in eigenen Worten — der Teil, den KI nicht liefern kann, weil er von den Live-Messwerten abhängt.

### D) Kleinigkeiten
- E6: schlanke Version als Standard deklarieren, lange Version = Differenzierung nach oben (beides vorhanden).
- Einheitliche Nummerierung: Elektrolyseur ist intern als „Experiment 5" betitelt, Wärme ebenfalls → Elektrolyseur auf „Experiment 6" korrigieren.
- Materialbox um Anzahl der Stationen ergänzen (3–5 Gruppen → reichen die Aufbauten?).

---

## Priorität der Umsetzung
1. **E5 Wärme arbeitsteilig** (Zeitrisiko, sofort wirksam)
2. **Drillachse kürzen** (Wiederholungen, Fehlerbalken)
3. Zeitleiste + Abgabevermerk auf alle Protokollbögen (ein Baustein, überall einfügbar)
4. Scaffolding-Stufen bei E6/Drillachse zurücknehmen (Skala offen)
5. Federpendel-Diagrammraster ergänzen
6. E3 straffen, E1 Aufgabe 6 → ★

---

## Umgesetzt in Rev. 1 (02.07.2026, nur Kopien in diesem Ordner — Originale unverändert)

| Änderung | Dateien | Status |
|---|---|---|
| Abgabevermerk-Box (Datum, Uhrzeit, Sichtvermerk, Mappen-Hinweis, „Rev. 1") | alle 10 Anleitungen | ✅ |
| Stufe 2: Zahlenskalen entfernt, Hilfebox „Skalierung selbst wählen" | E4b, Wärme, Elektrolyseur (+schlank) | ✅ |
| Stufe 3: 2 leere Gitter (F-s und T²-m) + Hilfebox | Federpendel | ✅ |
| Stufe 4: Diagrammraster ersetzt durch Millimeterpapier-Box mit Checkliste; Aufgabe 3/5 angepasst (Fehlerbalken min./max. r) | Drillachse | ✅ |
| Drillachse_Auswertung (Musterlösung): unverändert gelassen — enthält bewusst das fertige Beispieldiagramm | — | ✅ |

**Noch offen** (aus dem Review, nicht Teil von Rev. 1): Wärme Teil 2 arbeitsteilig, Drillachse Wiederholungen 3→2, Zeitleiste aufs Deckblatt, E3 straffen, E1 Aufgabe 6 → ★, gruppenindividuelle Parameter.
