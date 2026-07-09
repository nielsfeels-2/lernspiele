# 🏗️ City Builder – Present Progressive (Englisch Jg. 7)

Eigenständiges Lernspiel (Weg A) zum Present progressive, passend zu Orange Line 3, Unit 1 „People in England" (Station 2, G2, Wortfeld „Our changing cities"). Offline lauffähig, anonym, ohne Anmeldung – optimiert fürs iPad.

**▶️ Lokal spielen:** `index.html` direkt im Browser öffnen (Doppelklick oder AirDrop aufs iPad). QR-Code/Live-Link analog WortWelt, sobald ein Repo/Hosting feststeht.

## Lernziel & Spielprinzip

Trainiert die Bildung des Present progressive (am/is/are + -ing) in Aussagen, Verneinung und Fragen – bewusst mit dem Unit-Wortschatz zu Stadtveränderungen (dig a hole, build a house, plant trees, tear down a building, add a cycle lane, renovate, open …).

- Jede richtige Antwort lässt ein **neues Gebäude in der eigenen Skyline** wachsen – sichtbarer, dauerhaft gespeicherter Baufortschritt (Investment/Self-Reward).
- **4 Levels mit steigendem Schwierigkeitsgrad** (Projektauswahl-Bildschirm, per Sternebewertung freigeschaltet): Level 1 Aussagen → Level 2 Verneinung (isn't/aren't/am not) → Level 3 Fragen (Is/Are) → Level 4 „Endgegner" (Rechtschreibung: run→running, make→making, write→writing … + gemischte Wiederholung). Ab 1 Stern gilt ein Level als abgeschlossen (kein Frust-Lock), mehr Sterne = mehr Bonus-Münzen.
- Alle 4 Gebäude in der Skyline ein **Stadtplaner-Level-Aufstieg** (übergeordnete Meta-Progression über alle Level hinweg) mit kleiner Feier-Animation.
- Seltene „Bonus-Gebäude" (Riesenrad, Turm, Stadion, Brunnen – ~8 % Chance) als Hunt-Reward.
- **„Zeig deine Stadt!"**-Bildschirm alle 6 richtigen Sätze (Tribe-Reward).
- Fehler kosten nie die Stadt – nur kein neues Gebäude in diesem Zug. Nach 15 Aufgaben: freundlicher „Feierabend"-Hinweis (abschaltbar).

## Datenschutz & Technik

Keine Accounts, kein Tracking. Fortschritt ausschließlich lokal (`localStorage`, Schlüssel `cityBuilder_presentProgressive_v2`). Eine einzige `index.html`, kein Build-Schritt, kein Framework, kein CDN.

## QA-Checkliste (LERNAPP-BAUANLEITUNG.md)

- ✅ JS-Syntax geprüft (bun build, fehlerfrei)
- ✅ Jede Aufgabe lösbar, richtige Antwort immer in den Optionen, Distraktoren nie identisch mit der Lösung (28 Items über 4 Level manuell gegengeprüft)
- ✅ Emojis eindeutig genug für die Zielgruppe Jg. 7
- ➖ „Ohne Lesefähigkeit lösbar" nicht relevant (Zielgruppe Jg. 7)
- ✅ Offline, keine externen Requests
- ✅ localStorage-Schlüssel einzigartig (`cityBuilder_presentProgressive_v2`)
- ✅ Alle Hooked-Pflichtelemente: variable Belohnung (Münzen, seltene Gebäude, Level-Sterne), alle 3 Belohnungstypen (Hunt=seltene Gebäude, Self=Level/Skyline/Sterne, Tribe=Share-Screen), offene Schleife (Fortschritt zum nächsten Gebäude/Level sichtbar), gespeicherter Wert (Skyline bleibt dauerhaft), sofort spielbar (<10 Sek.), Flow-Kanal über 4 Schwierigkeitsstufen, Ethik-Check (Session-Bremse nach 15 Aufgaben, kein Level-Lock bei schlechter Leistung)
- ✅ Grundregeln 1–8 eingehalten (kein Pay-to-win, kein Bestrafen als Standard, Lernkopplung, Curriculum-Anlehnung an Orange Line 3 Unit 1)

## Level-Übersicht

| Level | Fokus |
|---|---|
| 1 · Aussagen | am/is/are + -ing in einfachen Sätzen |
| 2 · Verneinung | isn't / aren't / am not |
| 3 · Fragen | Is / Are |
| 4 · Endgegner | Rechtschreibung (Doppelkonsonant, -e weg) + gemischte Wiederholung |

## Weiterentwicklung / offene Punkte

- Aktuell 28 Aufgaben über 4 Level – bei Bedarf leicht erweiterbar (Array `LEVELS` in `index.html`).
- Deployment/QR-Code: eigenes Sammel-Repo für alle Lernspiele geplant (GitHub CLI wird dafür eingerichtet) – Link/QR folgt, sobald das Repo steht.
