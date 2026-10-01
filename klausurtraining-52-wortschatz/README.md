# Klausurtraining 5.2 · Textbesprechungswortschatz

**Kriterium 8 · Textbesprechungswortschatz · 4 Punkte** · Block *Sprache* · Jahrgang *alle*

the author conveys · emphasises · suggests …

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-52-wortschatz/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Kriterium 8 fragt nach dem „funktional angemessenen Wortschatz zur Textproduktion und Textbesprechung.“ Übersetzt: Du brauchst Verben, die sagen, <b>was der Text tut</b> — nicht nur <i>says</i>.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-52-v1` · 8 Aufgaben je Runde
* 12 Items: 12× luecke
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
| 1 | WELCHES VERB PASST? | luecke | Eine Wiederholung betont. tells und informs brauchen ein Gegenüber (tells us), writes down ist Protokoll, nic… |
| 2 | WELCHES VERB PASST? | luecke | only verlangt ein schwaches Verb — angedeutet, nicht gesagt. Und: ein Text beweist nichts. proves behauptet m… |
| 3 | WELCHES VERB PASST? | luecke | Ein Kontrast hebt hervor. Ein sprachliches Mittel kann nicht say — sprechen tut der Sprecher, wirken tut das … |
| 4 | WELCHES VERB PASST? | luecke | draw a parallel ist die feste Fügung. Solche Kollokationen sind genau das, worauf Kriterium 8 schaut — make a… |
| 5 | WELCHES VERB PASST? | luecke | refer to — verweisen. relate to heißt sich beziehen auf im Sinne von Verständnis, point to braucht etwas Sich… |
| 6 | WELCHES VERB PASST? | luecke | Eine Metapher vermittelt eine Vorstellung, sie erklärt sie nicht. convey ist dafür das genaue Verb. |
| 7 | WELCHES VERB PASST? | luecke | Ein Appell: urge, call on, appeal to. wishes wäre zu schwach — die Rede fordert, sie wünscht nicht. |
| 8 | WELCHES VERB PASST? | luecke | Eine Behauptung bleibt eine Behauptung — zumal eine, die sich als falsch erwies. proves und knows machen sie … |
| 9 | WELCHES VERB PASST? | luecke | deal with — der Text behandelt etwas. Die drei anderen sind aus dem Deutschen gebaut und kosten zusätzlich be… |
| 10 | WELCHES VERB PASST? | luecke | Textpräsens. Über einen Text wird im Präsens geschrieben, auch wenn er von 1863 ist. Die Vergangenheit gehört… |
| 11 | WELCHES VERB PASST? | luecke | create an effect / a sense of — die feste Wendung für Wirkung. Genau diese Formeln machen den Unterschied zwi… |
| 12 | WELCHES VERB PASST? | luecke | present sth. as sth. — darstellen als. Das Verb zeigt, dass es eine Entscheidung des Sprechers ist, nicht ein… |
