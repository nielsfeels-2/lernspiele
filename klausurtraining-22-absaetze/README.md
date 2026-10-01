# Klausurtraining 2.2 · Absätze ordnen

**Kriterium 3 · Struktur · 5 Punkte** · Block *Aufbau* · Jahrgang *alle*

Aufbau einer Analyse — die conclusion nicht vergessen

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-22-absaetze/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Kriterium 3 fragt nicht, ob viel dasteht, sondern ob man dir <b>folgen</b> kann. Bring die Absätze in die Reihenfolge, die eine Korrektur erwartet.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-22-v1` · 6 Aufgaben je Runde
* 8 Items: 6× sortieren, 2× wahl
* Quellen: vorgaben

**Nicht hier ändern.** Die Datei wird erzeugt:

```
uv run python 12_SCRIPTS/klausurtraining_bauen.py
```

Inhalte stehen in `12_SCRIPTS/klausurtraining_inhalte.py`.

## Abnahme nach R5

Jedes Item hat eine Begründung, die mehr sagt als die Aufgabe — das ist die
R2-Probe. `pruefe_module` prüft zusätzlich maschinell: Antwortindex,
Optionsdubletten, Lückenzeichen, Fehler- und Heilstellen bei Markieraufgaben,
Punktzahl im Kriterium, Schlüsselkonvention und **jedes Zitat gegen seine
Quelle**.

| # | Aufgabentyp | Format | Was eine richtige Antwort zeigt |
|---|---|---|---|
| 1 | ANALYSE · AUFBAU | sortieren | Erst der Rahmen, dann der Inhalt, dann die Mittel einzeln, am Ende die Bündelung. Der Schluss ist der Absatz,… |
| 2 | COMMENT · AUFBAU | sortieren | Die Position kommt früh, nicht am Ende als Überraschung. Das Gegenargument gehört dazu: Wer es weglässt, wirk… |
| 3 | SUMMARY · AUFBAU | sortieren | Eine Zusammenfassung folgt dem Text, nicht der eigenen Eingebung. Der Hauptgedanke steht vorn — damit die Les… |
| 4 | EIN ABSATZ · AUFBAU | sortieren | Erst die Behauptung, dann der Beleg — nicht umgekehrt. Ein Absatz, der mit dem Zitat beginnt, lässt die Lesen… |
| 5 | SPRACHMITTLUNG · AUFBAU | sortieren | Die Auswahl kommt vor dem Übertragen. Wer erst übersetzt und dann streicht, hat die Zeit schon verbraucht — u… |
| 6 | KLAUSURSTUNDE · AUFBAU | sortieren | Die Aufgabe steht vor dem Text. Wer den Text zuerst liest, markiert, was interessant ist — nicht, was gefragt… |
| 7 | WELCHER ABSATZ FEHLT? | wahl | Zwei Mittel genügen, wenn sie gut belegt sind. Was fehlt, ist der Satz, der die Leitfrage beantwortet. Ohne i… |
| 8 | WELCHER ABSATZ FEHLT? | wahl | Ein Kommentar ohne Gegenseite liest sich wie eine Behauptung. Wer das Gegenargument nennt und beantwortet, ze… |
