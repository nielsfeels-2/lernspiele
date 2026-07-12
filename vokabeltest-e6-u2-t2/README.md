# 🔐 Vokabeltest – Unit 2 – In the spotlight (Escape Room)

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `ITEMS`-Block
ausgetauscht). Automatische Korrektur, große Ergebniskarte mit Note – kein Scannen, keine
Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-e6-u2-t2/

## Inhalt

Unit 2 – In the spotlight – Reading + Sprachmittlung + Berufe. 13 Fragen (5 Deutsch→Englisch, 5 Englisch→Deutsch, 3 Lückensätze/Übersetzung),
Multiple-Choice, Wortschatz identisch zur zugehörigen Vokabeltest-Folie in der Unit-Präsentation.

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft (bun build, fehlerfrei)
- ✅ Alle Items: richtige Antwort in den Optionen, keine identischen Distraktoren
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
