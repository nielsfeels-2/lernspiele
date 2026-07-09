# 🔐 Vokabeltest – Escape Room (wiederverwendbare Vorlage)

Eigenständiges Lernspiel (Weg A, neues Genre: Escape Room) für die regelmäßigen Vokabeltests (alle ~2 Wochen, siehe `01_STANDARDS/leistungsbewertung_standard.md`). Automatische Korrektur, große Ergebniskarte mit Note – **kein Scannen, keine Datenübertragung**, die Note wird einfach auf dem Bildschirm angezeigt und der Lehrkraft gezeigt.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-escape/

## Konzept

Jede richtige Antwort öffnet ein Schloss auf dem Weg aus dem eingeschlossenen Klassenzimmer. Einmaliger Versuch pro Frage (keine Wiederholung – ist ein Test, kein Übungsspiel), sofortiges Feedback, am Ende eine große, eindeutig ablesbare Ergebniskarte (Punkte, Prozent, Note).

- Aktuell 13 Fragen (5 Deutsch→Englisch, 5 Englisch→Deutsch, 3 Lückensätze im Simple present) – Inhalt zu Unit 1 „People in England", Station 1 (rules & school).
- Multiple-Choice statt Freitext, damit die automatische Korrektur eindeutig ist (keine Tippfehler-/Schreibweisen-Probleme).
- Notenschlüssel (Prozent-Schwellen) ganz oben im Script als eigener Block – **unbedingt gegen den tatsächlichen schulinternen Notenschlüssel prüfen und bei Bedarf anpassen**, der hier verwendete ist eine gängige Standardskala, aber nicht offiziell für diese Schule bestätigt.

## Wiederverwendung für den nächsten Vokabeltest

Den `ITEMS`-Block ganz oben im `<script>` durch die neuen Vokabeln/Sätze ersetzen (gleiche Struktur: `type`, `q`, `options`, `correct`). Sonst nichts ändern nötig.

## Bewusste Abweichungen von den Hooked-Pflichtelementen

Dies ist ein **Bewertungswerkzeug**, kein Übungsspiel zum Gewöhnen – deshalb bewusst **kein** Belohnungs-/Streak-/Sammel-System, keine Session-Bremse, kein `localStorage` (nichts, was über eine Sitzung hinaus gespeichert werden müsste oder sollte). Grundregeln 1–5 (offline, anonym, iPad-first, kein Pay-to-win, kein Bestrafen als Standard) gelten weiterhin.

## QA-Checkliste

- ✅ JS-Syntax geprüft (bun build, fehlerfrei)
- ✅ Alle 13 Items manuell gegengeprüft: richtige Antwort immer in den Optionen, Distraktoren nie identisch mit der Lösung (bewusste False-Friend-Distraktoren wie „Mobbing"/„Chöre")
- ✅ Offline, keine externen Requests
- ✅ Grundregeln 1, 3, 4, 5, 8 eingehalten; Grundregel 2 (localStorage) bewusst nicht relevant (siehe oben)
- ➖ Echter Kamera-QR-Scan zur automatischen Notenübermittlung **nicht** umgesetzt – ohne Möglichkeit, das live zu testen (kein Browser-Zugriff in der Bau-Session), wäre das Risiko eines unlesbaren/fehlerhaften Codes zu hoch. Stattdessen: große, eindeutig ablesbare Ergebniskarte, die der Lehrkraft direkt gezeigt wird.
