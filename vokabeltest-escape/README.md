# 🔐 Vokabeltest – Escape Room (wiederverwendbare Vorlage)

Eigenständiges Lernspiel (Weg A, neues Genre: Escape Room) für die regelmäßigen Vokabeltests (Rhythmus siehe `01_STANDARDS/leistungsbewertung_standard.md`). Automatische Korrektur, große Ergebniskarte mit Note – **kein Scannen, keine Datenübertragung**, die Note wird einfach auf dem Bildschirm angezeigt und der Lehrkraft gezeigt.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-escape/

## Konzept

Jede richtig **geschriebene** Antwort öffnet ein Schloss auf dem Weg aus dem eingeschlossenen Klassenzimmer. Einmaliger Versuch pro Frage (keine Wiederholung – ist ein Test, kein Übungsspiel), sofortiges Feedback, am Ende eine große, eindeutig ablesbare Ergebniskarte (Punkte, Prozent, Note).

- **Freitext-Eingabe, kein Multiple-Choice:** Die SuS sollen das Wort wirklich aus dem Gedächtnis schreiben (produktiver Wortschatz inkl. Rechtschreibung), nicht nur erkennen. Verbindlich seit Nutzerfeedback 12.07.2026, siehe `01_STANDARDS/leistungsbewertung_standard.md`. Vergleich ist case-insensitive (Groß-/Kleinschreibung egal), Tippfehler zählen als falsch.
- **Zufällige Auswahl aus einem größeren Pool (`POOL`):** Jeder Testabschnitt hat 20+ Items hinterlegt; bei jedem Start werden `TEST_SIZE` (Standard 13) davon zufällig gezogen und in zufälliger Reihenfolge gestellt. Zwei Personen nebeneinander sehen unterschiedliche Fragen (Abschreiben wird erschwert), und ein zweiter Versuch prüft tendenziell andere Wörter als der erste – wichtig ist am Ende, dass wirklich der ganze Wortschatz sitzt, nicht nur 13 auswendig gelernte Fragen.
- Notenschlüssel (Prozent-Schwellen) ganz oben im Script als eigener Block – **unbedingt gegen den tatsächlichen schulinternen Notenschlüssel prüfen und bei Bedarf anpassen**, der hier verwendete ist eine gängige Standardskala, aber nicht offiziell für diese Schule bestätigt.

## Wiederverwendung für den nächsten Vokabeltest

Den `POOL`-Block ganz oben im `<script>` durch die neuen Vokabeln/Sätze ersetzen (gleiche Struktur: `type`, `q`, `correct` als Liste akzeptierter Schreibweisen). `TEST_SIZE` bei Bedarf anpassen. Sonst nichts ändern nötig.

## Bewusste Abweichungen von den Hooked-Pflichtelementen

Dies ist ein **Bewertungswerkzeug**, kein Übungsspiel zum Gewöhnen – deshalb bewusst **kein** Belohnungs-/Streak-/Sammel-System, keine Session-Bremse, kein `localStorage` (nichts, was über eine Sitzung hinaus gespeichert werden müsste oder sollte). Grundregeln 1–5 (offline, anonym, iPad-first, kein Pay-to-win, kein Bestrafen als Standard) gelten weiterhin.

## QA-Checkliste

- ✅ JS-Syntax geprüft (bun build, fehlerfrei)
- ✅ Freitext-Vergleich manuell geprüft (Groß-/Kleinschreibung + Leerzeichen werden normalisiert, mehrere akzeptierte Schreibweisen möglich)
- ✅ Zufallsauswahl geprüft: bei wiederholtem Start wechseln Auswahl und Reihenfolge
- ✅ Offline, keine externen Requests
- ✅ Grundregeln 1, 3, 4, 5, 8 eingehalten; Grundregel 2 (localStorage) bewusst nicht relevant (siehe oben)
- ➖ Echter Kamera-QR-Scan zur automatischen Notenübermittlung **nicht** umgesetzt – ohne Möglichkeit, das live zu testen (kein Browser-Zugriff in der Bau-Session), wäre das Risiko eines unlesbaren/fehlerhaften Codes zu hoch. Stattdessen: große, eindeutig ablesbare Ergebniskarte, die der Lehrkraft direkt gezeigt wird.
