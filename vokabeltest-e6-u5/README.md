# 🔐 Vokabeltest – Unit 5 – Healthy living (Escape Room)

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `POOL`-Block
ausgetauscht). Freitext-Eingabe (kein Multiple-Choice) – die SuS schreiben das Wort selbst. Automatische
Korrektur, große Ergebniskarte mit Note – kein Scannen, keine Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-e6-u5/

## Inhalt

Unit 5 – Healthy living – Check-in + Grammatik + Food. Pool von 22 Items (Deutsch→Englisch, Englisch→Deutsch, Lückensätze/Übersetzung),
Wortschatz identisch/erweitert zur zugehörigen Vokabeltest-Folie in der Unit-Präsentation.
Bei jedem Start werden 13 davon zufällig gezogen und in zufälliger Reihenfolge gestellt.

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft (bun build, fehlerfrei)
- ✅ Freitext-Vergleich geprüft (case-insensitive, mehrere akzeptierte Schreibweisen je Item)
- ✅ Zufallsauswahl aus dem Pool geprüft
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
