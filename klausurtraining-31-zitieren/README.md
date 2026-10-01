# 📎 Zitieren · Klausurtraining Englisch Sek II

**Kriterium 5 der Darstellungsleistung** — „belegt seine Aussagen durch eine
funktionale Verwendung von Verweisen und Zitaten", **3 Punkte**.

**▶️ Live:** https://nielsfeels-2.github.io/lernspiele/klausurtraining-31-zitieren/

## Drei Aufgabenarten, zehn Items pro Runde

| Teil | Aufgabe | Format |
|---|---|---|
| **A** | Direktes Zitat oder sinngemäße Wiedergabe? | Klicken (2 Optionen) |
| **B** | Ein Satz, ein Zitierfehler — welcher? | Klicken (4 von 6 Fehlertypen) |
| **C** | Behauptung belegen: selbst einen Satz mit eingebautem Zitat schreiben | Freitext mit Musterabgleich |

Jede Runde zieht 4 + 4 + 2 Items und mischt sie neu.

### Die sechs Fehlertypen in Teil B

Zeilenangabe fehlt · Zitat nicht wörtlich · Zitat steht allein statt eingebaut ·
Zitat nicht gedeutet · sinngemäß, aber in Anführungszeichen · Zitat zu lang.
Jeder Typ kommt genau einmal vor (automatisiert geprüft).

### Was der Musterabgleich in Teil C prüft

| Prüfung | wie |
|---|---|
| Zitat in Anführungszeichen | Mindestens zwei Wörter zwischen Anführungszeichen |
| Zeilenangabe | `(l. 18)` · `(ll. 17–18)` · `(cf. l. 3)` |
| **Zitat ist wortwörtlich** | Wortfolgenvergleich gegen den Quelltext |
| in einen Satz eingebaut | Außerhalb der Anführungszeichen stehen ≥ 3 Wörter |

**Die App bewertet nicht.** Nach jeder Schreibaufgabe steht: *„Geprüft wurden die
Bestandteile. Ob dein Satz gut klingt und ob die Deutung stimmt, entscheidest du
am Kriterienraster."* Keine Noten.

## Quelltext — und warum gerade dieser

**Abraham Lincoln, Gettysburg Address (1863), Bliss-Fassung**, wörtlich
übernommen von [nps.gov](https://www.nps.gov/linc/learn/historyculture/gettysburgaddress.htm).
272 Wörter, 22 Zeilen, gemeinfrei.

> ⚠️ **Dieses Modul war zuerst mit einem anderen Text gebaut** — gemeinfrei, aber
> zugleich der Klausurtext einer Klausur, die zwölf Tage später geschrieben wird.
> Rechtlich einwandfrei, didaktisch ein Totalschaden. Es ist **nichts
> veröffentlicht worden**; der Fehler fiel vor dem Push auf.
>
> Daraus ist **Regel R0** der Spezifikation geworden und das Prüfskript
> `12_SCRIPTS/klausurtexte_sperrliste.py`. Die Gettysburg Address ist auch
> langfristig sicher: zu bekannt, um je als *unbekannter* Klausurtext zu dienen.

## QA

| Prüfung | Ergebnis |
|---|---|
| **Sperrliste** — kein Klausurtext, auch nicht im Quelltext-Kommentar | ✅ |
| JS-Syntax (JavaScriptCore) | ✅ |
| Quelltext 22 Zeilen, Wörtlichkeitsprüfung erkennt echte Zitate | ✅ |
| …und weist erfundene ab (`conceived in freedom` statt `liberty`) | ✅ |
| Zeilenangaben-Muster: 5 gültige erkannt, 4 ungültige abgewiesen | ✅ |
| Alle 6 Fehlertypen in Teil B genau einmal, jeder mit Begründung | ✅ |
| Volldurchlauf richtig → 10/10, 3 Sterne | ✅ |
| Teil C: gültige Antwort akzeptiert; fehlende Zeilenangabe, fehlendes Zitat, falsches Zitat und nicht eingebautes Zitat **einzeln** abgewiesen | ✅ |
| Sammlung schrumpft bei Fehlern nicht | ✅ |
| Keine externen Requests · eigener localStorage-Schlüssel `kt-31-v1` | ✅ |

> ⚠️ Noch nicht am iPad angesehen.

## Grundlage

`14_LERNAPPS/KLAUSURTRAINING-SPEZIFIKATION.md` — Regeln R0 bis R5.
