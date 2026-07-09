# 🎮 Lernspiele

Sammel-Repo für gamifizierte, browserbasierte Lernspiele für den Schulunterricht – über alle Jahrgangsstufen und Themen hinweg. Jedes Spiel ist eine eigenständige, offline-fähige `index.html` in einem eigenen Unterordner (GitHub Pages).

**Live:** https://nielsfeels-2.github.io/lernspiele/

## Spiele

| Ordner | Spiel | Thema |
|---|---|---|
| [`verb-ninja/`](verb-ninja/) | 🥷 Verb Ninja | Simple Present, Englisch Jg. 7 |
| [`city-builder-progressive/`](city-builder-progressive/) | 🏗️ City Builder | Present Progressive, Englisch Jg. 7 |

Jeder Ordner hat eine eigene `README.md` mit Lernziel, Spielprinzip und QA-Checkliste.

## Prinzipien

- Eine einzige `index.html` pro Spiel, kein Build-Schritt, kein Framework, kein CDN.
- Offline-fähig, anonym, kein Login, keine Accounts. Fortschritt nur lokal (`localStorage`).
- Kein Pay-to-win, kein Bestrafen als Standard – Belohnung ausschließlich für echte Lernleistung.
- Details/Bauregeln: siehe `LERNAPP-BAUANLEITUNG.md` und `GAME-DESIGN-PRINZIPIEN.md` im Lehrerassistenz-Projekt (`14_LERNAPPS/`).

## Datenschutz

Keine Accounts, kein Tracking, keine personenbezogenen Daten. Jedes Spiel speichert Fortschritt ausschließlich lokal im Browser des Geräts.
