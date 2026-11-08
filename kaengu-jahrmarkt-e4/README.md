# 🦘 Kängu-Jahrmarkt – Englisch Klasse 4, „Numbers and time“

Eigenständiges Lernspiel (Weg A, neues Genre: Jahrmarkt mit fünf Mini-Spielen) zur Vorbereitung auf den Englischtest zur Unit **Numbers and time** (Test voraussichtlich Mi, 11.11.2026). Offline, anonym, ohne Anmeldung, iPad-first.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/kaengu-jahrmarkt-e4/

![QR-Code](qr-kaengu-jahrmarkt-e4.png)

## Stationen (je 3 Stufen, 6 Aufgaben pro Runde)

| Station | Format | Stufe 1 | Stufe 2 | Stufe 3 |
|---|---|---|---|---|
| 🎰 Bingo-Bude | Zahl hören → auf Bingo-Karte antippen | 1–20 | Teens & Zehner (13 vs. 30 …) | 21–100 (auch 47 vs. 74) |
| 📞 Zahlen-Telefon | Zahl hören/lesen → Ziffern tippen | Wort sichtbar | nur hören | große Zahlen, 100, 1000, Telefonnummern |
| 🔤 Buchstaben-Zelt | Ziffer → Zahlwort aus Buchstaben bauen | one–twelve | thirteen–one hundred | twenty-two, seventy-eight, one thousand |
| 🕐 Uhren-Karussell | Digitaluhr lesen · hören · stellen („It’s nine thirty.“) | o’clock | :15 :30 :45 | alle 5-Minuten-Zeiten (z. B. three forty) |
| 🥫 Dosenwerfen | Ball (Englisch) auf Dose (Deutsch/Ziffer) | Hello, Bye, Thanks, What time is it? | telephone number, police, school, mobile … | Zahl ↔ Zahlwort |

Dazu die **Jahrmarkts-Tour** (gemischte Runde) und im Bereich „Für Erwachsene“ das **Zahlen-Diktat** aus dem Elternbrief (Eltern sagen die Zahl, Kind schreibt Ziffern).

**Inhalte** stammen aus den Seiten des Activity Books (Numbers, What time is it?), der Vokabelzusammenstellung und dem Elternbrief. Die Aufgaben selbst sind zufällig erzeugt, kein Buchtext wird kopiert. Uhrzeiten werden wie im Buch gelesen („nine thirty“, „three forty“, „o’clock“). *Nicht* enthalten: „quarter past“, „half past“ (kamen im Material nicht vor).

## Hooked-Elemente

- **Variable Belohnung:** 1–3 🎟️ pro Antwort, seltenes **Gold-Ticket** (+6, ~8 %), Bingo-Bonus; Glückskugel (alle 30 Tickets) mit Preis in 4 Seltenheitsstufen (55/28/12/5 %), Inhalt erst beim Öffnen sichtbar.
- **Hunt:** Preisregal mit 20 Preisen · **Self:** Sterne je Stufe, Rang (Schnupper-Gast bis Jahrmarkts-König), **Test-Fit-Balken** je Bereich · **Tribe:** „Zeig dein Regal jemandem“ + Zahlen-Diktat mit Mama/Papa (Familien-Bonus).
- **Offene Schleife:** Glückskugel-Leiste, Rang-Ziel, Test-Fit „alle fünf Balken grün = bereit“, gesperrte Stufen, Test-Countdown.
- **Gespeicherter Wert:** Preise, Tickets, Sterne, Tages-Serie 🔥 – `localStorage`, Schlüssel `kaenguJahrmarktE4_v1`.
- **Sofort spielbar:** ein Tipp auf „Jahrmarkts-Tour“.
- **Flow:** 3 Stufen, „jetzt“-Markierung wandert mit; Hilfen: 🔊 Vorlesen (Englisch, bevorzugt en-GB), „Wort zeigen“, nach 2 Fehlern Hinweis, nach 3 Fehlern wird die Lösung gezeigt (dann kein Ticket).
- **Ethik:** Fehler kosten nie Besitz. Tickets nur für richtige Antworten. Pause-Hinweis nach 3 Runden (abschaltbar). Kein Zeitdruck, keine Käufe.

## Technik

Eine `index.html`, kein CDN, keine externen Requests, Grafik aus Emojis/CSS. Ohne englische Stimme (oder bei ausgeschaltetem Ton) wird das gesprochene Wort stattdessen als Text angezeigt. Beim iPad: Stummschalter aus und Lautstärke an.

## QA (LERNAPP-BAUANLEITUNG.md)

- ✅ JS-Syntax (`bun build`) · ✅ Logiktest im Browser: je 200–500 zufällige Aufgaben pro Stufe (Distraktoren eindeutig und nie die Lösung, Zahlwörter 1–1000 korrekt, Bingo-Karten 9 verschiedene Zahlen, Aufrufe stets auf der Karte, Uhr-Optionen eindeutig), komplette Runden aller Stationen inkl. Fehlerpfad/Lösungsanzeige, Truhe, Hub/Regal/Erwachsenen-Ansicht ohne `undefined`/`NaN`
- ✅ Layout bei 820 px angesehen · ✅ Sperrlisten-Check · ✅ offline, localStorage-Schlüssel einzigartig
- ✅ Hooked-Pflichtelemente · Grundregeln 1–8
- ⚠️ Nicht geprüft: Sprachausgabe auf dem echten iPad (Headless-Test hat keine Stimme)
