# 🔐 Vokabeltest Woche 1 – People in England

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `POOL`-Block
ausgetauscht). Freitext-Eingabe – die SuS schreiben das Wort selbst. Automatische Korrektur, große
Ergebniskarte mit Note – kein Scannen, keine Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-e7-uv1-w1/

## Inhalt

Jg. 7 G-Kurs · UV 7.1-1 · Check in und Station 1 (V SB S. 206, p. 8–10) · Pool von 44 Items (Deutsch→Englisch, Englisch→Deutsch,
Lückensätze). Bei jedem Start werden 13 davon zufällig gezogen und in zufälliger Reihenfolge gestellt.

**Quelle des Wortschatzes:** Orange Line 3 G-Kurs, Unit 1 „People in England", Vocabulary SB S. 206 (Check in p. 8–9, Station 1 p. 10). Alle Woerter der Seiten 8–10; auf SB S. 206 sind sie einheitlich blau gesetzt, gruene (freiwillige) Woerter kommen dort nicht vor. Ergaenzt 14.09.2026: Die Station-1-Woerter laufen auf SB S. 207 weiter (on time bis knife, knives) — sie gehoeren noch zu p. 10. Gruene (freiwillige) Woerter sind nicht enthalten.

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft
- ✅ Freitext-Vergleich (case-insensitive, mehrere akzeptierte Schreibweisen je Item)
- ✅ Zufallsauswahl aus dem Pool
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
- ✅ QR-Code erzeugt (`qr-vokabeltest-e7-uv1-w1.png`)
