# Klausurtraining I·B · Summary

**Teilaufgabe 1 · Leseverstehen · 12 Punkte** · Block *Inhalt* · Jahrgang *alle*

Auswahl nach Relevanz, Präsens, keine Wertung

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-ib-summary/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Eine Zusammenfassung ist keine Nacherzählung. Sie wählt aus — und genau dafür gibt es die Punkte. Der Text steht oben, du kannst ihn jederzeit aufklappen.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-ib-v1` · 8 Aufgaben je Runde
* 13 Items: 2× freitext, 11× wahl
* Quellen: schautext, vorgaben

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
| 1 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Das ist der Auslöser der ganzen Geschichte. Ohne ihn versteht niemand, warum die Liste entsteht. |
| 2 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Der zweite Weg ist der überraschende — wer ihn weglässt, verkürzt den Text auf zurückgeben oder behalten und … |
| 3 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Die Reise ist die Einzelheit, die Vereinbarung ist der Punkt. Nimm das Allgemeine, nicht das Anschauliche. |
| 4 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Ortsangaben gehören in den Einleitungssatz, wenn überhaupt. Für den Gedankengang des Textes ändert der Norden… |
| 5 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Dein Urteil — und in Teilaufgabe 1 unbezahlt. Heb es dir für Teilaufgabe 3 auf, dort bringt es Punkte. |
| 6 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Der Text spricht über ein Museum. Eine Verallgemeinerung auf alle britischen Museen steht nicht da — und ist … |
| 7 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Das Museum beginnt von sich aus — darauf liegt sogar die Betonung. Hineingelesener Zwang ist ein Inhaltsfehle… |
| 8 | GEHÖRT DAS IN DIE ZUSAMMENFASSUNG? | wahl | Der Schluss des Textes — und seine Pointe. Eine Zusammenfassung, die vor dem Ergebnis aufhört, ist unvollstän… |
| 9 | WARUM TAUGT DIESER SATZ NICHT? | wahl | Inhaltlich richtig, formal falsch. Zitate gehören in die Analyse (Kriterium 5), nicht in die Zusammenfassung … |
| 10 | WARUM TAUGT DIESER SATZ NICHT? | wahl | Textpräsens, auch in der Zusammenfassung: the museum begins … and publishes … Die Jahreszahl darf stehen blei… |
| 11 | WARUM TAUGT DIESER SATZ NICHT? | wahl | Nur das Tempus ist geändert, sonst steht der Satz wortgleich im Text. Das kostet Kriterium 6 — und in der Zus… |
| 12 | IN EINEM SATZ | freitext | Ein Hauptgedanke nennt wer, was tut und wozu das führt — und lässt alles Anschauliche weg. |
| 13 | IN EINEM SATZ | freitext | Gegensätze zusammenzufassen heißt, beide Seiten in einen Satz zu bekommen — meist mit while oder whereas. |
