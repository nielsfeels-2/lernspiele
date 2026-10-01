# Klausurtraining 2.1 · Einleitungssätze

**Kriterien 1 + 2 · Aufgabenbezug und Textsortenmerkmale · 10 Punkte** · Block *Aufbau* · Jahrgang *alle*

Bibliografiesatz und In-order-to-Satz — und keine Absichtserklärung

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-21-einleitung/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Der Einstieg einer Analyse besteht aus <b>zwei</b> Sätzen: dem Bibliografiesatz und dem In-order-to-Satz. Und aus einer Sorte Satz, die ausdrücklich <b>nicht</b> hineingehört.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-21-v1` · 7 Aufgaben je Runde
* 11 Items: 4× freitext, 7× wahl
* Quellen: standard

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
| 1 | WAS FEHLT HIER? | wahl | Textsorte (speech), Autor und Thema stehen da. Ohne Titel und Jahr weiß die Lesende nicht, über welchen Text … |
| 2 | WAS FEHLT HIER? | wahl | Das ist eine Überschrift, kein Satz. Es fehlt, worum es geht — ohne Thema steht am Anfang der Analyse noch ke… |
| 3 | WAS IST HIER FALSCH? | wahl | Die Korrektur weiß, dass du analysieren wirst — es steht in der Aufgabe. Der Satz verbraucht eine Zeile und b… |
| 4 | WAS IST HIER FALSCH? | wahl | Das Passiv versteckt das I will, ändert aber nichts: Es bleibt eine Ankündigung. Nicht das Problem ist In ord… |
| 5 | IN ORDER TO — RICHTIG ODER NICHT? | wahl | Das ist die Musterformulierung. Der Satz sagt, wozu der Text seine Mittel einsetzt — und nennt mit line of ar… |
| 6 | IN ORDER TO — RICHTIG ODER NICHT? | wahl | Dieselbe Fügung, anderes Subjekt — und daran entscheidet es sich. … the author uses … ist richtig, … I will l… |
| 7 | WELCHER IST BESSER? | wahl | B hat alle Bestandteile und sagt zusätzlich, was Lincoln tut. A sagt nur, dass es um etwas geht — und braucht… |
| 8 | SCHREIB DEN EINSTIEG | freitext | Zwei Sätze: erst wer, was und wann — dann wozu der Text seine Mittel einsetzt. |
| 9 | SCHREIB DEN EINSTIEG | freitext | Bei einem Gedicht heißt die Textsorte sonnet oder poem — nicht text. Kriterium 2 fragt genau danach. |
| 10 | SCHREIB DEN EINSTIEG | freitext | Bei einem Romanauszug gehört dazu, welche Stelle es ist — in the opening, in this excerpt. Sonst fehlt der Le… |
| 11 | SCHREIB DEN EINSTIEG | freitext | Beim Essay ist die Hauptthese das Thema. argues that … sagt in einem Wort, dass der Text etwas behauptet — da… |
