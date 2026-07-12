# 🎮 Lernspiele

Sammel-Repo für gamifizierte, browserbasierte Lernspiele für den Schulunterricht – über alle Jahrgangsstufen und Themen hinweg. Jedes Spiel ist eine eigenständige, offline-fähige `index.html` in einem eigenen Unterordner (GitHub Pages).

**Live:** https://nielsfeels-2.github.io/lernspiele/

## Spiele

| Ordner | Spiel | Thema |
|---|---|---|
| [`verb-ninja/`](verb-ninja/) | 🥷 Verb Ninja | Simple Present, Englisch Jg. 7 |
| [`city-builder-progressive/`](city-builder-progressive/) | 🏗️ City Builder | Present Progressive, Englisch Jg. 7 |

## Vokabeltests (selbstauswertend, Escape Room)

Kein Übungsspiel, sondern Bewertungswerkzeug: Note direkt auf dem Bildschirm, der Lehrkraft zeigen.
Alle nutzen dieselbe Engine (`vokabeltest-escape/index.html`), nur der `ITEMS`-Block ist ausgetauscht.

| Ordner | Unit | Abschnitt |
|---|---|---|
| [`vokabeltest-escape/`](vokabeltest-escape/) | Jg. 7, Orange Line 3 Unit 1 | Station 1 (rules & school) |
| [`vokabeltest-e6-u1-t1/`](vokabeltest-e6-u1-t1/) | Jg. 6, Unit 1 Looking back | Check-in + Station 1 |
| [`vokabeltest-e6-u1-t2/`](vokabeltest-e6-u1-t2/) | Jg. 6, Unit 1 Looking back | Viewing + Listening + Reading |
| [`vokabeltest-e6-u2-t1/`](vokabeltest-e6-u2-t1/) | Jg. 6, Unit 2 In the spotlight | Check-in + Station 2 |
| [`vokabeltest-e6-u2-t2/`](vokabeltest-e6-u2-t2/) | Jg. 6, Unit 2 In the spotlight | Reading + Sprachmittlung + Berufe |
| [`vokabeltest-e6-u3/`](vokabeltest-e6-u3/) | Jg. 6, Unit 3 Nature and me | Check-in + Grammatik |
| [`vokabeltest-e6-u4/`](vokabeltest-e6-u4/) | Jg. 6, Unit 4 Visiting London | Check-in + Grammatik |
| [`vokabeltest-e6-u5/`](vokabeltest-e6-u5/) | Jg. 6, Unit 5 Healthy living | Check-in + Grammatik + Food |
| [`vokabeltest-e6-u6/`](vokabeltest-e6-u6/) | Jg. 6, Unit 6 A changing world | Check-in + Grammatik + Medien |

Jeder Ordner hat eine eigene `README.md` mit Lernziel, Spielprinzip und QA-Checkliste.

## Prinzipien

- Eine einzige `index.html` pro Spiel, kein Build-Schritt, kein Framework, kein CDN.
- Offline-fähig, anonym, kein Login, keine Accounts. Fortschritt nur lokal (`localStorage`).
- Kein Pay-to-win, kein Bestrafen als Standard – Belohnung ausschließlich für echte Lernleistung.
- Details/Bauregeln: siehe `LERNAPP-BAUANLEITUNG.md` und `GAME-DESIGN-PRINZIPIEN.md` im Lehrerassistenz-Projekt (`14_LERNAPPS/`).

## Datenschutz

Keine Accounts, kein Tracking, keine personenbezogenen Daten. Jedes Spiel speichert Fortschritt ausschließlich lokal im Browser des Geräts.
