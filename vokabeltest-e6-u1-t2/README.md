# 🔐 Vokabeltest E6 · Unit 1 · Station 1 (SB S. 242–243)

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `POOL`-Block
ausgetauscht). Freitext-Eingabe – die SuS schreiben das Wort selbst. Automatische Korrektur, große
Ergebniskarte mit Note – kein Scannen, keine Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-e6-u1-t2/

## Inhalt

Orange Line 2, Unit 1 – Station 1, p. 10 und p. 11 (SB S. 242–243) · Pool von 50 Items (Deutsch→Englisch, Englisch→Deutsch,
Lückensätze). Bei jedem Start werden 13 davon zufällig gezogen und in zufälliger Reihenfolge gestellt.

**Quelle des Wortschatzes:** Orange Line 2, Vokabelverzeichnis S. 242–243, Abschnitt Station 1 – alle Einträge, unverändert.

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft
- ✅ Freitext-Vergleich (case-insensitive, mehrere akzeptierte Schreibweisen je Item)
- ✅ Zufallsauswahl aus dem Pool
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
- ✅ QR-Code erzeugt (`qr-vokabeltest-e6-u1-t2.png`)

## Lückensätze: die Lücke ist die Vokabel

**Nutzerregel 15.09.2026:** „wenn du die Sätze nimmst sollst du da die items abfragen. also zB *Katie and her cousin _____ in Wales* und nicht *Katie and her cousin went sailing in …*"

Gelückt wird immer der Vokabeleintrag selbst, nie ein anderes Wort des Satzes. *to go sailing* → `Katie and her cousin ___ ___ in Wales.` Die Zahl der Lücken entspricht der Zahl der Wörter in der Lösung.

Die Beispielsätze des Buches werden dafür gekürzt oder angepasst — sie eins zu eins zu übernehmen und irgendein Wort zu lücken war der Fehler.
