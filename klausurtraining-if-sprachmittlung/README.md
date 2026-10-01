# Klausurtraining I·F · Sprachmittlung

**Klausurteil B · Sprachmittlung · 50 Punkte** · Block *Inhalt* · Jahrgang *Q1/Q2*

Auswahl nach Zweck, nicht vollständig übertragen

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-if-sprachmittlung/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Sprachmittlung ist <b>kein Übersetzen</b>. Du wählst aus, was deine Adressatin für ihren Zweck braucht — und erklärst, was es in ihrem Land nicht gibt. Der deutsche Text steht oben.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-if-v1` · 8 Aufgaben je Runde
* 12 Items: 1× freitext, 11× wahl
* Quellen: detext, vorgaben

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
| 1 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Die Zahlen sind der Kern: Sie zeigen Umfang und Ehrlichkeit des Projekts. Wer sie weglässt, lässt den Inhalts… |
| 2 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Für die Frage, ob sich ein Besuch lohnt, ist die Finanzierung ohne Belang. Auswahl heißt auch: etwas Richtige… |
| 3 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Wichtig — es zeigt, dass der Anstoß von außen kam. Aber Bürgerbegehren gibt es in Großbritannien so nicht; oh… |
| 4 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Verfahrensdetail. Dass der Rat zustimmte, steckt schon darin, dass die Liste veröffentlicht wurde — doppelt g… |
| 5 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Sie plant einen Besuch mit ihrem Kurs. Öffnungszeiten und Eintritt sind für diesen Zweck wichtiger als alles … |
| 6 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Nützlich, wenn der Kurs Fragen hat — aber Sprechstunde ist kein Wort, das sich übertragen lässt. Beschreib, w… |
| 7 | BRAUCHT DIE ADRESSATIN DAS? | wahl | Vorgeschichte. Interessant, aber ihre Frage lautet: Lohnt sich der Besuch, und worum geht es? Darauf antworte… |
| 8 | WIE ÜBERTRÄGST DU DAS? | wahl | Erklären statt übersetzen. Das deutsche Wort sagt ihr nichts, citizens’ demand ist eine Wortfürwortübertragun… |
| 9 | WIE ÜBERTRÄGST DU DAS? | wahl | Eigennamen bleiben stehen — sonst findet sie das Haus nicht. Die kurze Erläuterung dahinter kostet vier Wörte… |
| 10 | WIE ÜBERTRÄGST DU DAS? | wahl | Depot heißt im Museum storage, nicht warehouse — und die vierte Fassung verliert, dass es um die Herkunft geh… |
| 11 | WAS IST HIER FALSCH? | wahl | In einer E-Mail an eine Freundin klingt das harmlos — in Klausurteil B ist es ein Fehler. Die Wertung ersetzt… |
| 12 | SCHREIB DEN ANFANG | freitext | Anrede, Gegenstand, Kern — in drei Sätzen. Die E-Mail beginnt bei ihrer Frage, nicht beim Anfang des deutsche… |
