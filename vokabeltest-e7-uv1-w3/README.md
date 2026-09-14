# 🔐 Vokabeltest Woche 3 – Station 2, erster Teil

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `POOL`-Block
ausgetauscht). Freitext-Eingabe – die SuS schreiben das Wort selbst. Automatische Korrektur, große
Ergebniskarte mit Note – kein Scannen, keine Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-e7-uv1-w3/

## Inhalt

Jg. 7 G-Kurs · UV 7.1-1 · V SB S. 207–208 (p. 16–17) · Pool von 28 Items (Deutsch→Englisch, Englisch→Deutsch,
Lückensätze). Bei jedem Start werden 13 davon zufällig gezogen und in zufälliger Reihenfolge gestellt.

**Quelle des Wortschatzes:** Orange Line 3 G-Kurs, Vocabulary SB S. 207–208, Station 2 (p. 16–17). NUR die blauen Woerter; to decorate, to develop, to improve und to connect stehen dort gruen und sind nicht enthalten.

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft
- ✅ Freitext-Vergleich (case-insensitive, mehrere akzeptierte Schreibweisen je Item)
- ✅ Zufallsauswahl aus dem Pool
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
- ✅ QR-Code erzeugt (`qr-vokabeltest-e7-uv1-w3.png`)
