# Klausurtraining I·E · Cartoon-Analyse

**Teilaufgabe 2 · Analyse · 17 Punkte** · Block *Inhalt* · Jahrgang *Q1/Q2*

Beschreiben → Symbole → Aussage → Wertung

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-ie-cartoon/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Die häufigste Punkteinbuße bei Cartoons: sofort deuten. Erst beschreiben — und <b>jede</b> Deutung am Bild festmachen.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-ie-v1` · 8 Aufgaben je Runde
* 12 Items: 12× wahl
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
| 1 | BESCHREIBUNG ODER DEUTUNG? | wahl | Reine Beschreibung — und nötig. Wer sie überspringt, verliert in der mündlichen Prüfung die ersten sechs Punk… |
| 2 | BESCHREIBUNG ODER DEUTUNG? | wahl | Eine Deutung — und sie ist am Bild festgemacht: an der Vitrine und am Etikett ON PERMANENT DISPLAY. So muss j… |
| 3 | BESCHREIBUNG ODER DEUTUNG? | wahl | Von einer Weigerung ist nichts zu sehen. Die Zeichnung zeigt eine Frage, keine Antwort — hineingelesene Handl… |
| 4 | BESCHREIBUNG ODER DEUTUNG? | wahl | Steht wörtlich in der Sprechblase. Text im Bild gehört zur Beschreibung — er wird gelesen, nicht gedeutet. |
| 5 | BESCHREIBUNG ODER DEUTUNG? | wahl | Eine Deutung, belegt am Schild Can I go home? — das ist der Kern der Zeichnung: Ein Ausstellungsstück stellt … |
| 6 | BESCHREIBUNG ODER DEUTUNG? | wahl | Beschreibung, und die entscheidende: Welche Seite unten ist, trägt die ganze Aussage. Genau hinsehen lohnt si… |
| 7 | BESCHREIBUNG ODER DEUTUNG? | wahl | Deutung, festgemacht an der gekippten Waage und der Aufschrift LEGAL. Und beachte das Verb: suggests, nicht p… |
| 8 | BESCHREIBUNG ODER DEUTUNG? | wahl | Es ist niemand zu sehen. Was nicht im Bild ist, kann auch nicht belegt werden — und unbelegte Deutung kostet … |
| 9 | WAS IST DIE AUSSAGE? | wahl | Der Besucher stellt die Frage — die Antwort gibt niemand, und das Etikett sagt ON PERMANENT DISPLAY. Der Wide… |
| 10 | WAS IST DIE AUSSAGE? | wahl | Die Waage ist das Bild für Abwägen — hier wiegt die Aktenseite das eine Objekt auf. Nicht unmöglich: Die Zeic… |
| 11 | WAS FEHLT DIESER ANALYSE? | wahl | Beschreibung und Behauptung stehen da, dazwischen klafft die Lücke. Es fehlt: … by giving the object a voice … |
| 12 | WAS FEHLT DIESER ANALYSE? | wahl | Eine vollständige, genaue Beschreibung — und sie bleibt bei Schritt 1 stehen. Die Waage ist ein Symbol; wer e… |
