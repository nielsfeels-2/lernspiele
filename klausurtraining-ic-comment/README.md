# Klausurtraining I·C · Comment — der Bauplan

**Teilaufgabe 3 · Stellungnahme · 15 Punkte** · Block *Inhalt* · Jahrgang *alle*

Position → Argument mit Beleg → Gegenargument → Fazit

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-ic-comment/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Teilaufgabe 3 fragt nach <b>deiner</b> Position — begründet. Hier geht es um den Unterschied zwischen einem Argument und einer Behauptung. Der Text steht oben zum Aufklappen.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-ic-v1` · 8 Aufgaben je Runde
* 11 Items: 2× freitext, 9× wahl
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
| 1 | IST DAS EIN ARGUMENT? | wahl | Behauptung plus Grund, und der Grund trägt: Er nennt den Zweck eines Museums. Daran kann die Gegenseite anset… |
| 2 | IST DAS EIN ARGUMENT? | wahl | simply ersetzt den Grund, statt ihn zu geben. Wer so schreibt, hat nichts gesagt, dem man widersprechen könnt… |
| 3 | IST DAS EIN ARGUMENT? | wahl | Eine richtige Wiedergabe — AFB I. Als Beleg ist sie wertvoll, aber sie braucht eine Behauptung davor, für die… |
| 4 | IST DAS EIN ARGUMENT? | wahl | Ein gutes Beispiel — es zeigt, dass zurückgeben nicht die einzige Möglichkeit ist. Zum Argument wird es erst … |
| 5 | IST DAS EIN ARGUMENT? | wahl | Auch die Gegenseite argumentiert. Dieses Argument in seiner stärksten Form zu nennen, ist genau das, was AFB … |
| 6 | IST DAS EIN ARGUMENT? | wahl | Everybody knows ist kein Grund, sondern eine Behauptung über andere Leute. Verallgemeinerungen schwächen eine… |
| 7 | WAS FEHLT DIESEM ABSATZ? | wahl | Position, Grund und Fazit sitzen. Es fehlt die Seite, die widerspricht — und damit der Teil, in dem AFB III ü… |
| 8 | WAS FEHLT DIESEM ABSATZ? | wahl | Beide Seiten sind da, aber niemand bezieht Stellung. Bei comment ist genau das die Aufgabe — it is hard to de… |
| 9 | WAS FEHLT DIESEM ABSATZ? | wahl | Aufbau und Entgegnung sind stark. Was fehlt, ist der Verweis, der das stützt — etwa die gestiegenen Besucherz… |
| 10 | DEIN POSITIONSSATZ | freitext | Ein Positionssatz nennt die Forderung und den Grund — dann weiß die Lesende nach einem Satz, worauf der Rest … |
| 11 | DAS GEGENARGUMENT | freitext | Das Gegenargument in seiner stärksten Form zu nennen, kostet nichts und bringt viel: Erst dann wirkt deine En… |
