# 🔐 Vokabeltest Woche 5 – Reading

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `POOL`-Block
ausgetauscht). Freitext-Eingabe – die SuS schreiben das Wort selbst. Automatische Korrektur, große
Ergebniskarte mit Note – kein Scannen, keine Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-e7-uv1-w5/

## Inhalt

Jg. 7 G-Kurs · UV 7.1-1 · V SB S. 209 (p. 22) · Pool von 21 Items (Deutsch→Englisch, Englisch→Deutsch,
Lückensätze). Bei jedem Start werden 13 davon zufällig gezogen und in zufälliger Reihenfolge gestellt.

**Quelle des Wortschatzes:** Orange Line 3 G-Kurs, Vocabulary SB S. 209, Reading (p. 22). NUR die blauen Woerter; after, kingdom und colony stehen dort gruen und sind nicht enthalten. Auf S. 23 folgt kein neuer Wortschatz mehr — dort beginnt Unit 2.

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft
- ✅ Freitext-Vergleich (case-insensitive, mehrere akzeptierte Schreibweisen je Item)
- ✅ Zufallsauswahl aus dem Pool
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
- ✅ QR-Code erzeugt (`qr-vokabeltest-e7-uv1-w5.png`)
