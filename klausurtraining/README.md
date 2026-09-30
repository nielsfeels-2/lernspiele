# 🎯 Klausurtraining Englisch · Oberstufe — Hub

Auswahlseite für die Übungsmodule zur Oberstufenklausur. Die SuS wählen nach
**Block** und, bei den Inhaltsmodulen, nach **Jahrgang**.

**▶️ Live:** https://nielsfeels-2.github.io/lernspiele/klausurtraining/

## Was der Hub tut — und was nicht

- Er listet **alle** geplanten Module, auch die noch nicht gebauten. Die stehen
  sichtbar als **„in Arbeit"** und sind nicht anklickbar. Ein Hub mit toten
  Links wäre schlechter als gar keiner.
- Er **liest** den Fortschritt aus dem `localStorage`-Schlüssel des jeweiligen
  Moduls (gleicher Origin) und zeigt ihn auf der Karte an. Er **schreibt**
  nichts.
- Er enthält **keine Aufgaben**. Jedes Modul ist eine eigene Datei.

## Aufbau

Zwei aufklappbare Abschnitte erklären die Einteilung:

1. **„Warum diese Einteilung?"** — die 12 Kriterien der Darstellungsleistung mit
   Punktzahlen, und warum sie in jeder Klausur gleich sind (66 von 110 Punkten).
2. **„Was die Übungen können — und was nicht"** — die Ehrlichkeitsregel: Bei
   Schreibaufgaben werden **Bestandteile** geprüft, nicht Qualität. Keine Noten.

## Ein neues Modul eintragen

Im `MODULE`-Array ergänzen bzw. `status` von `"soon"` auf `"live"` setzen und
`href` (+ optional `key` für die Fortschrittsanzeige) eintragen. Der Block muss
in `BLOECKE` vorkommen, der Jahrgang in `JAHRE` oder `"alle"` sein — ein
Testlauf prüft das.

## QA

| Prüfung | Ergebnis |
|---|---|
| JS-Syntax (JavaScriptCore) | ✅ |
| 16 Module vollständig, Nummern eindeutig | ✅ automatisiert |
| Live-Module haben einen Link, Blöcke/Jahrgänge existieren im Filter | ✅ automatisiert |
| Alle Filterkombinationen laufen durch, „Alle/Alle" zeigt alles | ✅ automatisiert |
| EF-Filter zeigt EF + jahrgangsunabhängig, kein Q1/Q2 | ✅ automatisiert |
| Fortschritt wird gelesen, Modul ohne Schlüssel liefert nichts | ✅ automatisiert |
| Live-Module stehen oben | ✅ automatisiert |
| Keine externen Requests | ✅ |

> ⚠️ Noch nicht am iPad angesehen.

## Grundlage

`14_LERNAPPS/KLAUSURTRAINING-SPEZIFIKATION.md` — dort stehen die Modulkarte und
die fünf Regeln, nach denen die Items abgeleitet werden.
