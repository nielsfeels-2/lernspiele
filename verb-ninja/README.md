# 🥷 Verb Ninja – Simple-Present-Dojo (Englisch Jg. 7)

Eigenständiges Lernspiel (Weg A) zum Simple Present, passend zu Orange Line 3, Unit 1 „People in England" (Station 1, G1). Offline lauffähig, anonym, ohne Anmeldung – optimiert fürs iPad.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/verb-ninja/

![QR-Code](qr-verb-ninja.png)

## Lernziel & Spielprinzip

Trainiert gezielt die im G-Kurs häufigste Fehlerquelle: das **-s bei he/she/it** im Simple Present (Aussagen, Verneinung mit don't/doesn't, Fragen mit Do/Does). Sätze aus dem Wortfeld „school rules" der Unit.

- Sensei-Ninja-Setting: zu jedem Satz mit Lücke zwei Antwort-Shuriken, schnelle richtige Antwort (< 3 Sek.) = **kritischer Treffer** mit Bonus.
- **4 Levels mit steigendem Schwierigkeitsgrad** (Levelauswahl-Bildschirm, per Sternebewertung freigeschaltet): Level 1 Aussagen → Level 2 Verneinung (don't/doesn't) → Level 3 Fragen (Do/Does) → Level 4 „Endgegner" (Rechtschreibung: study→studies, watch→watches, go→goes … + gemischte Wiederholung, kürzeres Zeitlimit). Ein Level gilt ab 1 Stern als abgeschlossen und schaltet das nächste frei (kein Frust-Lock bei schlechter Leistung), mehr Sterne = mehr Bonus-Münzen.
- **Gürtel-System** (Weiß → Gelb → Orange → Grün → Blau → Braun → Schwarz) als übergeordneter Fortschritt über alle Level hinweg (Self-Reward).
- **Schatztruhen** alle 5 richtigen Antworten mit variabler Münzmenge, seltener „goldener Shuriken" (~5 %) (Hunt-Reward).
- **„Zeig deinen Gürtel!"**-Bildschirm bei jedem Gürtelaufstieg (Tribe-Reward).
- Fehler kosten nie Fortschritt – nur der Streak setzt zurück. Nach 15 Aufgaben in einer Sitzung: freundlicher Pause-Hinweis (abschaltbar).

## Datenschutz & Technik

Keine Accounts, kein Tracking. Fortschritt ausschließlich lokal (`localStorage`, Schlüssel `verbNinja_simplePresent_v2`). Eine einzige `index.html`, kein Build-Schritt, kein Framework, kein CDN – Grafik aus Emojis und CSS.

## QA-Checkliste (LERNAPP-BAUANLEITUNG.md)

- ✅ JS-Syntax geprüft (bun build, fehlerfrei)
- ✅ Jede Aufgabe lösbar, richtige Antwort immer in den Optionen, Distraktoren nie identisch mit der Lösung (30 Items über 4 Level manuell gegengeprüft)
- ✅ Emojis eindeutig genug für die Zielgruppe Jg. 7 (kein Klasse-1-Anspruch auf Bildlesbarkeit ohne Text)
- ➖ „Ohne Lesefähigkeit lösbar" nicht relevant (Zielgruppe Jg. 7, keine Sprachausgabe eingebaut)
- ✅ Offline, keine externen Requests (geprüft: keine `http`, `<link>`, `fetch`, CDN)
- ✅ localStorage-Schlüssel einzigartig (`verbNinja_simplePresent_v2`)
- ✅ Alle Hooked-Pflichtelemente: variable Belohnung (Truhen, Krit-Treffer, Level-Sterne), alle 3 Belohnungstypen (Hunt=Truhen, Self=Gürtel+Level-Sterne, Tribe=Share-Screen), offene Schleife (Gürtelbalken „X/Y XP", nächstes Level sichtbar gesperrt), gespeicherter Wert (Münzen, XP, bester Streak, Level-Sterne), sofort spielbar (<10 Sek.), Flow-Kanal über 4 Schwierigkeitsstufen mit sinkendem Zeitlimit, Ethik-Check (Session-Bremse nach 15 Aufgaben, kein Level-Lock bei schlechter Leistung)
- ✅ Grundregeln 1–8 eingehalten (kein Pay-to-win, kein Bestrafen als Standard, Lernkopplung, Curriculum-Anlehnung an Orange Line 3 Unit 1)

## Level-Übersicht

| Level | Fokus | Zeitlimit |
|---|---|---|
| 1 · Aussagen | he/she/it + -s in Aussagesätzen | 9 Sek. |
| 2 · Verneinung | don't / doesn't | 9 Sek. |
| 3 · Fragen | Do / Does | 8 Sek. |
| 4 · Endgegner | Rechtschreibung (-es, y→ies) + gemischte Wiederholung | 6,5 Sek. |

## Weiterentwicklung / offene Punkte

- Aktuell 30 Aufgaben über 4 Level – bei Bedarf leicht erweiterbar (Array `LEVELS` in `index.html`).
- Repo: `nielsfeels-2/lernspiele` (Sammel-Repo für alle Lernspiele aller Jahrgänge/Themen).
