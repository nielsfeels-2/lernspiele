# 🔐 Vokabeltest – Word bank: analysing a relationship

Selbstauswertender Vokabeltest (Weg B: gleiche Engine wie `vokabeltest-escape/`, nur der `POOL`-Block
ausgetauscht). Freitext-Eingabe – die SuS schreiben das Wort selbst. Automatische Korrektur, große
Ergebniskarte mit Note – kein Scannen, keine Datenübertragung.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/vokabeltest-ef-wordbank/

## Inhalt

EF Englisch · UV EF1-2 „Challenges in Teenage Life" · Test am Wednesday, 25 November · Pool von 34 Items (Deutsch→Englisch, Englisch→Deutsch,
Lückensätze). Bei jedem Start werden 13 davon zufällig gezogen und in zufälliger Reihenfolge gestellt.

**Quelle des Wortschatzes:** Wortbank AB 7 (eigene Zusammenstellung, abgeleitet aus der Auswertung von Klausur 1).

Notenschlüssel: Standardskala (siehe `vokabeltest-escape/README.md`) – bitte gegen den tatsächlichen
schulinternen Notenschlüssel prüfen.

## QA-Checkliste

- ✅ JS-Syntax geprüft
- ✅ Freitext-Vergleich (case-insensitive, mehrere akzeptierte Schreibweisen je Item)
- ✅ Zufallsauswahl aus dem Pool
- ✅ Offline, keine externen Requests, kein Login, kein localStorage
- ✅ QR-Code erzeugt (`qr-vokabeltest-ef-wordbank.png`)
