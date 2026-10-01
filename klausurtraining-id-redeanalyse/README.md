# Klausurtraining I·D · Redeanalyse

**Teilaufgabe 2 · Analyse · 17 Punkte** · Block *Inhalt* · Jahrgang *Q1/Q2*

Rhetorische Mittel — mit Wirkung, nicht als Liste

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-id-redeanalyse/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Eine Liste rhetorischer Mittel ist keine Analyse. Die Punkte liegen auf der <b>Wirkung</b>. Beide Reden stehen oben zum Aufklappen.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-id-v1` · 8 Aufgaben je Runde
* 17 Items: 4× markieren, 13× wahl
* Quellen: rede, gettysburg, vorgaben

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
| 1 | WELCHES MITTEL IST DAS? | wahl | Die Rede beginnt bei den Zuhörenden, nicht beim Thema. Wirkung: Wer angesprochen wird, hört zu — und die drei… |
| 2 | WELCHES MITTEL IST DAS? | wahl | Zwei fast gleiche Sätze, die sich an einem Wort scheiden: safe gegen honestly. Wirkung: Das Eingeständnis kom… |
| 3 | WELCHES MITTEL IST DAS? | wahl | Die Frage ist der erwartete Einwand — der Redner stellt ihn selbst und beantwortet ihn sofort. Wirkung: Der W… |
| 4 | WELCHES MITTEL IST DAS? | wahl | Der Tresor steht für Besitz und Verschluss. Wirkung: Das Bild macht einen Verwaltungsstreit anschaulich — man… |
| 5 | WELCHES MITTEL IST DAS? | wahl | Zwei Verben, die einander ausschließen, in vier Wörtern. Wirkung: Die ganze Streitfrage — fragen oder nehmen … |
| 6 | WELCHES MITTEL IST DAS? | wahl | Die Kiste ist das Bild für Wegschaffen. Wirkung: Der Schluss dreht den Vorwurf um — man kann dem Museum Objek… |
| 7 | WELCHES MITTEL IST DAS? | wahl | Dreimal derselbe Anfang. Wirkung: Die Wiederholung macht den Redner klein — er zählt auf, was er nicht vermag… |
| 8 | WELCHES MITTEL IST DAS? | wahl | Drei Präpositionen, ein Wort. Wirkung: Die Dreierfigur klingt abgeschlossen — deshalb steht sie am Ende und w… |
| 9 | MITTEL ODER WIRKUNG? | wahl | Eine Beobachtung am Text — richtig, aber noch unbezahlt. Erst der nächste Satz bringt den Punkt. |
| 10 | MITTEL ODER WIRKUNG? | wahl | Hier steht, was das Mittel mit den Zuhörenden macht. Genau dieser Satz ist in Klausuren am häufigsten der feh… |
| 11 | MITTEL ODER WIRKUNG? | wahl | Eine Inhaltsangabe. Sie gehört in Teilaufgabe 1 — in der Analyse zählt sie allenfalls als Beleg für eine Beha… |
| 12 | MITTEL ODER WIRKUNG? | wahl | Das Mittel ist nur noch genannt, die Aussage liegt auf dem redefines. So sieht ein Analysesatz aus, der trägt. |
| 13 | MITTEL ODER WIRKUNG? | wahl | Benannt und verortet — mehr nicht. Ein Katalog solcher Sätze ist die häufigste Form einer Analyse, die trotzd… |
| 14 | FINDE DAS MITTEL | markieren | Dreimal derselbe Anfang — eine Anapher. Wirkung: Der Imperativ richtet den Blick dreimal neu aus und macht au… |
| 15 | FINDE DAS MITTEL | markieren | Antithese. Der Satzbau bleibt gleich, nur ein Wort kippt — dadurch wirkt das Eingeständnis wie eine Korrektur… |
| 16 | FINDE DAS MITTEL | markieren | Metapher. Ein Museum ist kein Tresor — das Bild macht aus wir besitzen ein wir verschließen und begründet dam… |
| 17 | FINDE DAS MITTEL | markieren | Das inklusive we: Der Redner stellt sich mit auf die Seite der Schuld. Wirkung: Die Zuhörenden können die Kri… |
