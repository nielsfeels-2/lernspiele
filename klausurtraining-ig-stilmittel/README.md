# Klausurtraining I·G · Stilmittel

**Teilaufgabe 2 · Mittel mit Beleg und Wirkung · 6 von 17 Punkten** · Block *Inhalt* · Jahrgang *alle*

Die Mittel erkennen, richtig benennen — und wissen, welcher Begriff wann erwartet wird

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-ig-stilmittel/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Der Werkzeugkasten für jede Analyse. Im Erwartungshorizont stehen dafür <b>6 der 17 Punkte</b> — und zwar für Mittel <b>mit Beleg und Wirkung</b>. Vier Texte stehen oben zum Aufklappen: ein Kommentar, zwei Reden von heute und eine historische.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-ig-v1` · 9 Aufgaben je Runde
* 36 Items: 4× markieren, 32× wahl
* Quellen: kolumne, redebus, redeabschied, gettysburg, vorgaben, standard

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
| 1 | WELCHES MITTEL IST DAS? | wahl | like steht dabei — damit ist es ein simile. Wirkung: Das Haus wirkt verschlossen und transportabel zugleich; … |
| 2 | WELCHES MITTEL IST DAS? | wahl | Kein like, kein as — die Gleichsetzung steht direkt da. Wirkung: Aus einem Beruf wird etwas, das weitergeht, … |
| 3 | WELCHES MITTEL IST DAS? | wahl | Vitrinen flüstern nicht. Wirkung: Die Leerstelle bekommt eine Stimme — das Fehlende wird zum eigentlichen Aus… |
| 4 | WELCHES MITTEL IST DAS? | wahl | Eine Aufzählung, die immer unwahrscheinlicher wird. Wirkung: Der Bushaltestelle-Schluss wirkt komisch — und b… |
| 5 | WELCHES MITTEL IST DAS? | wahl | a bus gegen an evening, im gleichen Satzbau. Wirkung: Aus einer Haushaltsfrage wird eine Frage nach dem Leben… |
| 6 | WELCHES MITTEL IST DAS? | wahl | Eine Übertreibung, und eine freundliche. Wirkung: Die Rednerin lacht über sich selbst, bevor jemand anders es… |
| 7 | WELCHES MITTEL IST DAS? | wahl | Bewusst zu klein gesagt. Wirkung: Die Rednerin nimmt dem Rat das Gegenargument aus der Hand, bevor er es auss… |
| 8 | WELCHES MITTEL IST DAS? | wahl | remarkably quiet meint das Gegenteil: Das Wort verschweigt. Wirkung: Nicht das Objekt wird angegriffen, sonde… |
| 9 | WELCHES MITTEL IST DAS? | wahl | Sie sagt, sie halte sich nicht an Ratschläge — und tut es in diesem Moment. Wirkung: Der Ton ist in zwei Zeil… |
| 10 | WELCHES MITTEL IST DAS? | wahl | furious ist wertend. Wirkung: Die Gegenseite erscheint aufgebracht statt argumentierend — eine Vorentscheidun… |
| 11 | WELCHES MITTEL IST DAS? | wahl | Eine Jahreszahl, die etwas voraussetzt. Wirkung: Wer sie einordnen kann, liest das Etikett anders — der Text … |
| 12 | WELCHES MITTEL IST DAS? | wahl | Das Wort wird wiederholt, aber nicht am Satzanfang — deshalb repetition, nicht anaphora. Wirkung: Die winzige… |
| 13 | WELCHES MITTEL IST DAS? | wahl | Dreimal derselbe Satzanfang — das unterscheidet die Anapher von der bloßen Wiederholung. Wirkung: Der Dank be… |
| 14 | WELCHES MITTEL IST DAS? | wahl | Patience … practical — gleicher Anlaut. Wirkung: Der Satz klingt wie ein Merksatz und bleibt deshalb hängen. |
| 15 | WELCHES MITTEL IST DAS? | wahl | Eine Frage, auf die niemand antworten soll. Wirkung: Der Rat muss sie im Kopf beantworten — und jede Antwort … |
| 16 | WELCHES MITTEL IST DAS? | wahl | Die Rede beginnt bei den Zuhörenden, nicht beim Thema. Wirkung: Wer angesprochen wird, hört zu — und das Alte… |
| 17 | WELCHES MITTEL IST DAS? | wahl | Zweimal derselbe Bau: Adverb plus Verb. Wirkung: Die zweite Hälfte klingt wie die erste und wirkt deshalb ebe… |
| 18 | WELCHES MITTEL IST DAS? | wahl | under God und new birth holen religiöse Sprache in eine politische Rede. Wirkung: Der Neuanfang bekommt eine … |
| 19 | FALSCH BENANNT — WAS IST ES WIRKLICH? | wahl | Die häufigste Verwechslung überhaupt. like oder as ⇒ simile. Ohne ⇒ metaphor. Ein falscher Fachbegriff kostet… |
| 20 | FALSCH BENANNT — WAS IST ES WIRKLICH? | wahl | anaphora ist die Wiederholung am Anfang aufeinanderfolgender Sätze. Hier steht das Wort am Ende und dann alle… |
| 21 | FALSCH BENANNT — WAS IST ES WIRKLICH? | wahl | Genau umgekehrt: hyperbole übertreibt, understatement untertreibt. Und das Untertreiben wirkt hier stärker — … |
| 22 | FALSCH BENANNT — WAS IST ES WIRKLICH? | wahl | Die Wörter selbst sind neutral; es ist die Reihe, die wirkt. emotive language wäre furious oder burned to the… |
| 23 | WELCHE WIRKUNG PASST HIER? | wahl | Dreimal derselbe Anfang, dreimal ein anderes Ziel — und jedes fällt weg. Die Wiederholung macht die Folgen zä… |
| 24 | WELCHE WIRKUNG PASST HIER? | wahl | Dasselbe Mittel wie eben, andere Wirkung. Genau deshalb reicht es nie, das Mittel zu benennen: Der Punkt häng… |
| 25 | WELCHE WIRKUNG PASST HIER? | wahl | Concise sentences wirken durch den Bruch im Rhythmus. Nach den langen Sätzen davor steht ein einzelnes Wort —… |
| 26 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Im Grundkurs nicht erwartet — und ausdrücklich als zu schwierig markiert. Nimm enumeration oder parallelism; … |
| 27 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Leistungskurs. Im Grundkurs beschreibst du einfach, was passiert: Die zweite Hälfte dreht die Reihenfolge der… |
| 28 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Leistungskurs. Der Grundkursbegriff dafür heißt understatement — und trifft es für die meisten Stellen genaus… |
| 29 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Leistungskurs. Im Grundkurs genügt: eine Aufzählung ohne Bindewörter — und was das mit dem Tempo macht. |
| 30 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Grundkursrepertoire, und eines der wichtigsten: In fast jeder Rede steckt eine Anapher. |
| 31 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Grundkursrepertoire. Leicht zu finden — und leicht zu verschenken, wenn nur der Name dasteht und keine Wirkun… |
| 32 | GRUNDKURS ODER LEISTUNGSKURS? | wahl | Grundkursrepertoire — und bei politischen Reden besonders ergiebig, weil die Anspielung eine Wertung mitbring… |
| 33 | FINDE DAS MITTEL | markieren | Simile — erkennbar am like. Wirkung: Das Museum erscheint verschlossen und zugleich als etwas, das jemand mit… |
| 34 | FINDE DAS MITTEL | markieren | Personification. Wirkung: Was fehlt, bekommt eine Stimme — die Leerstelle wird zum eigentlichen Exponat. |
| 35 | FINDE DAS MITTEL | markieren | Antithesis. Zwei Wörter im gleichen Satzbau, die zwei Größenordnungen gegeneinandersetzen. Wirkung: Aus einer… |
| 36 | FINDE DAS MITTEL | markieren | Alliteration. Wirkung: Der Satz klingt wie ein Merksatz — deshalb steht er allein und ohne Erklärung da. |
