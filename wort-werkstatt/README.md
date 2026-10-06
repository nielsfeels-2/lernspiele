# ⛏️ Wort-Werkstatt – Lesen und Schreiben (Klasse 2)

Eigenständiges Lernspiel (Weg A, Genre: Sammeln und Bauen) für ein Kind der 2. Klasse, das beim Lesen und Schreiben noch Unterstützung braucht und sich für Bau-Spiele begeistert. Offline lauffähig, anonym, ohne Anmeldung, iPad-first.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/wort-werkstatt/

![QR-Code](qr-wort-werkstatt.png)

## Idee

Das Kind sucht in Bau-Spielen Gegenstände über ihren Namen. Hier wird genau das zum Lernen: Jedes **gelesene oder geschriebene Wort** bringt den passenden **Gegenstand** (🪵 Holz, 🏠 Haus, 🐄 Kuh …) in die Truhe. Damit baut das Kind seine **eigene Welt** (8 × 6 Felder, Himmel, Gras, Erde). Ohne Lesen und Schreiben gibt es keine Bausteine.

## Vier Aufgabenarten

| Art | Was das Kind tut | Üben |
|---|---|---|
| **Finden** | Bauer nennt Wörter („Bring mir: Holz und Stein."), Kind tippt die richtigen Wortkarten an | Lesen, Wörter wiedererkennen |
| **Schreiben** | Bild zeigen, Wort Buchstabe für Buchstabe legen (falsche Buchstaben werden nicht eingetragen) | Rechtschreibung |
| **Bauen** | Bauanleitung lesen („Baue eine Axt. Du brauchst 2 Holz und 3 Steine."), Zutaten mit richtiger Anzahl auf die Werkbank legen | Leseverstehen, Zahlen, Mehrzahl |
| **Satz** | Wörter eines Satzes in die richtige Reihenfolge tippen (Satz kann angehört werden) | Satzbau, Lesen ganzer Sätze |

## Vier Stufen (Biome), schrittweise schwerer

| Stufe | Wörter | Beispiele | Hilfen |
|---|---|---|---|
| 🌲 Wald (13) | 3–5 Buchstaben, lautgetreu | Kuh, Brot, Holz, Haus | Bild + Wort sichtbar, Wort zum Abschreiben, nur nötige Buchstaben |
| ⛰️ Höhle (20) | 5–6 Buchstaben, 2 Silben, sch/ei/ch | Apfel, Schaf, Kuchen, Dino | Bild + Wort, 3 Extra-Buchstaben, Wort nur am Anfang sichtbar, Satz aus 3–4 Wörtern |
| 🌊 Meer (15) | 6–9 Buchstaben, Doppelkonsonanten | Schwein, Kartoffel, Brücke | nur Wortkarten (Bild nur als Hilfe), ganze Buchstaben-Tastatur, Bauanleitungen, längere Sätze |
| 🏰 Schloss (12) | Zusammengesetzte Wörter | Spitzhacke, Regenbogen, Schneemann | ähnliche Wörter als Ablenker, 3 Zutaten, lange Sätze |

Die nächste Stufe schaltet frei, wenn die Hälfte der Wörter der Stufe davor einmal fehlerfrei gekonnt wurde. Das Kind kann jederzeit eine frühere Stufe wiederholen. Die Eltern können alle Stufen freischalten.

## Hilfen für schwache Leser

- **Silbenfarben** (🎨, abschaltbar): Silben abwechselnd rot und blau
- **Vorlesen:** 🔊 liest die Aufgabe vor (auf Wunsch automatisch), **jedes Wort in einer Aufgabe ist antippbar** und wird vorgelesen. Auch ein Tipp auf eine falsche Wortkarte liest diese vor.
- **Wort zeigen** (👁) bei der Schreibaufgabe, blinkender Buchstabe nach 3 Fehlern
- Fehler kosten nie etwas: falsche Buchstaben/Wörter werden einfach nicht eingetragen
- Wörter, die schwerfallen, kommen automatisch häufiger dran (Gewichtung nach Fehlern und Können)

## Hooked-Elemente

- **Variable Belohnung:** 1–3 bzw. 2–4 Gegenstände je Aufgabe, **Schatztruhe** (nach 8 Schritten) mit 3 zufälligen Gegenständen und 12 % Chance auf einen **seltenen Fund** (🏰 🐉 🌈 🦄 🚀 👑), Inhalt erst beim Öffnen sichtbar
- **Hunt:** Sammeln der Gegenstände · **Self:** Wort-Buch mit bis zu 3 Sternen pro Wort, Stufen freischalten · **Tribe:** „Zeig deine Welt jemandem!"
- **Offene Schleife:** Truhen-Leiste, gesperrte Biome mit Ziel, Wort-Buch mit „???"-Lücken
- **Gespeicherter Wert:** Inventar, eigene Welt, Wort-Buch, Tages-Serie 🔥
- **Sofort spielbar:** ein Tipp auf „Los geht's!", erste Aufgabe: ein Wort aus vier Karten
- **Flow-Kanal:** automatische Empfehlung der höchsten freigeschalteten Stufe, Hilfen nehmen mit den Stufen ab
- **Ethik:** keine Zeitlimits, keine Käufe, Belohnung nur für gelöste Aufgaben, Pause-Hinweis nach 2 Runden (je 3 Aufgaben, also ca. 10 Minuten). „Für Erwachsene": Übersicht der Stufen und der schwierigsten Wörter.

## Datenschutz & Technik

Eine einzige `index.html`, kein CDN, keine Bilder (Emojis, CSS), keine externen Requests. Keine Accounts, keine Namen, kein Tracking. Spielstand nur lokal (`localStorage`, Schlüssel `wortWerkstatt_v1`). Kleine Töne per Web Audio (abschaltbar 🔔), Sprachausgabe über die Systemstimme (`de-DE`).

## QA-Checkliste (LERNAPP-BAUANLEITUNG.md)

- ✅ JS-Syntax (`bun build`)
- ✅ Automatischer Logiktest (Bun, ohne Browser): alle 60 Wörter schreibbar, Silben setzen sich zum Wort zusammen, nötige Buchstaben immer vorhanden, 500 Finden-Aufgaben je Stufe (Ziele vorhanden, Ablenker nie identisch), 6 000 Schreib-Aufgaben, Sätze, 1 600 Bau-Aufgaben (zu wenig, zu viel, korrekt), Plural-Texte, 120 komplette Runden, Truhen (seltene Funde plausibel), Welt (setzen, ersetzen, aufnehmen), Freischaltung. 0 Fehler.
- ✅ Layout bei iPad-Breite im Headless-Chrome angesehen (Start, Finden, Schreiben, Bauen, Welt)
- ✅ Sperrlisten-Check: kein gesperrter Text (alle Wörter und Sätze selbst geschrieben, nichts aus Klausuren)
- ✅ Offline, keine externen Requests · localStorage-Schlüssel einzigartig · Hooked-Pflichtelemente · Grundregeln 1–8
- ➖ Abweichung: Die Buchstaben-Tastatur hat 6 Spalten (Tasten ca. 76–100 px), das reicht auf dem iPad, ist aber knapp unter der 80-px-Regel auf kleinen Geräten.
- ➖ **Noch nicht getestet:** echtes Antippen auf dem iPad (Gefühl, Sprachausgabe, Töne). Am besten die erste Runde gemeinsam mit dem Kind spielen und beobachten, wo es hakt.

## Weiterentwicklung / Ideen

- Eigene Wörter der Familie (Name, Haustier, Lieblingsdinge) in einer „Meine Wörter"-Stufe
- Großschreibung der Nomen gezielt üben (aktuell wird Groß/Klein nicht bewertet, der erste Buchstabe erscheint automatisch groß)
- Mehr Rezepte und Sätze, Wortschatz an die Fibel/Lehrwerk der Klasse anpassen
