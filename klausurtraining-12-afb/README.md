# Klausurtraining 1.2 · AFB erkennen

**Kriterium 1 · Aufgabenbezug · 6 Punkte** · Block *Aufgabe verstehen* · Jahrgang *alle*

Welche Teilaufgabe will welche Leistung?

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-12-afb/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Jede Klausur hat <b>drei Teilaufgaben</b>, und jede will etwas anderes. Wer in Teilaufgabe 1 schon wertet, verschenkt doppelt: Die Wertung zählt dort nicht — und in Teilaufgabe 3 fehlt sie dann.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-12-v1` · 8 Aufgaben je Runde
* 12 Items: 12× wahl
* Quellen: gettysburg, vorgaben

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
| 1 | WELCHE TEILAUFGABE IST DAS? | wahl | Wiedergeben, geordnet, ohne Deutung — das sichert das Textverständnis. Teilaufgabe 1, Schwerpunkt AFB I und I… |
| 2 | WELCHE TEILAUFGABE IST DAS? | wahl | Verlangt ist eine Analyse „unter Berücksichtigung des Zusammenhangs von Form und Inhalt“. Teilaufgabe 2, Schw… |
| 3 | WELCHE TEILAUFGABE IST DAS? | wahl | Ein begründetes Urteil, das über den Text hinausgeht — kritisch-wertend. Teilaufgabe 3, Schwerpunkt AFB II un… |
| 4 | WELCHE TEILAUFGABE IST DAS? | wahl | Produktiv-gestaltend: eine eigene Textsorte mit eigener Position. Das ist die andere Hälfte von Teilaufgabe 3… |
| 5 | WELCHE TEILAUFGABE IST DAS? | wahl | Eine Zusammenfassung bestimmter thematischer Aspekte — genau die Form, die die Konstruktionshinweise für Teil… |
| 6 | WELCHE TEILAUFGABE IST DAS? | wahl | examine heißt „describe and explain in detail“ — dieselbe Erläuterung wie analyse. Teilaufgabe 2. |
| 7 | WELCHE TEILAUFGABE IST DAS? | wahl | interpret = „explain the meaning, purpose or message of sth.“ Bedeutung erklären ist Analyse, nicht Wertung —… |
| 8 | WELCHER ANFORDERUNGSBEREICH? | wahl | Eine Angabe aus dem Text bzw. der Textquelle, korrekt wiedergegeben. Nötig — aber AFB I, und davon gibt es nu… |
| 9 | WELCHER ANFORDERUNGSBEREICH? | wahl | Das ist noch reines Beobachten — nachzählen kann jede und jeder. AFB II beginnt erst bei: … which makes him s… |
| 10 | WELCHER ANFORDERUNGSBEREICH? | wahl | Beobachtung plus Wirkung — genau der Schritt von AFB I zu AFB II. Hier liegt der Schwerpunkt der Analyseaufga… |
| 11 | WELCHER ANFORDERUNGSBEREICH? | wahl | Ein eigenes Urteil mit Begründung, über den Text hinaus. AFB III — und das gibt es nur in Teilaufgabe 3. |
| 12 | WELCHER ANFORDERUNGSBEREICH? | wahl | Zwei Stellen in Beziehung setzen ist schon Deutung — AFB II. Reines Wiedergeben wäre: The speaker mentions th… |
