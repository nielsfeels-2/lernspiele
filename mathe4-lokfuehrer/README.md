# 🚂 Lokführer-Express – Mathe Klasse 4

Eigenständiges Lernspiel (Weg A, neues Genre: Zug-Sammelspiel mit Bahnhof/Fahrten) zu drei Themen der Klasse 4: **Zeitspannen**, **schriftliche Addition** und **halbschriftliche Multiplikation**. Offline lauffähig, anonym, ohne Anmeldung – optimiert fürs iPad.

**▶️ Live spielen (nach dem Hochladen):** https://nielsfeels-2.github.io/lernspiele/mathe4-lokfuehrer/

![QR-Code](qr-mathe4-lokfuehrer.png)

▲ Der QR-Code funktioniert erst, wenn der Ordner ins Repo `nielsfeels-2/lernspiele` hochgeladen ist (LERNAPP-BAUANLEITUNG.md, Schritt 6). Das ist ein Schritt von Niels.

## Spielprinzip

Die Kinder sind Lokführer:innen. Jede **Fahrt** besteht aus 6 Aufgaben (eine Station oder gemischt). Für gelöste Aufgaben gibt es **Kohle** 🪨; ein voller **Kessel** (40 Kohle) bringt eine **Waggon-Truhe** mit einem zufälligen Waggon (20 Waggons in 4 Seltenheitsstufen, nur kosmetisch). Der Zug wächst mit jeder Truhe.

| Station | Thema | Stufe 1 | Stufe 2 | Stufe 3 |
|---|---|---|---|---|
| 🕰️ Fahrplan-Turm | Zeitspannen | volle/halbe/Viertelstunden | 5-Minuten-Schritte, Umrechnen | beliebige Minuten, rückwärts rechnen |
| 📦 Lade-Rampe | schriftliche Addition | zwei Zahlen bis 999 | zwei Zahlen, 5-stellig | drei Zahlen, 6-stellig (< 1 Mio.) |
| 🔧 Waggon-Werkstatt | halbschriftliche Multiplikation | 7 · 48 | 6 · 235 | 12 · 34 |

**Aufgabenformate** (alle zufällig erzeugt, daher unbegrenzt viele Varianten):

- **Zeitspannen:** Ankunft berechnen, Dauer berechnen, Abfahrt rückwärts berechnen, Stunden/Minuten umrechnen. Analoguhren zeigen Abfahrt/Ankunft. Eingabe über Zahlenfeld (Stunden/Minuten getrennt).
- **Schriftliche Addition:** echtes Stellenwertschema (E, Z, H, T, ZT, HT). Spalte für Spalte von rechts, Ergebnisziffer und Übertrag werden einzeln eingetragen. Falsche Ziffer → Tipp mit der Spaltenrechnung (z. B. „7 + 6 + 9 + 1 (Übertrag)").
- **Halbschriftliche Multiplikation:** (1) richtige Zerlegung in Stellenwerte wählen, (2) Teilaufgaben rechnen, (3) Teilergebnisse addieren. Rechenbaum zeigt den Weg.

**Hilfen (stufig):** 1. Fehler → Strategie-Tipp, 2. Fehler → Rechenhinweis, 3. Fehler → Lösung des Schritts wird gezeigt, danach eine ähnliche Übungsaufgabe. 🔊-Knopf liest jede Aufgabe vor (Sprachausgabe, hilft u. a. DaZ-Kindern).

## Hooked-Elemente (GAME-DESIGN-PRINZIPIEN.md)

- **Variable Belohnung:** Kohle 1–5 pro Aufgabe, seltene **Goldkohle** (+8, ~10 % bei Treffer im ersten Versuch), Waggon-Truhen mit Seltenheit (55/28/12/5 %), Inhalt erst beim Öffnen sichtbar.
- **Hunt:** Waggon-Sammlung (20), **Self:** Sterne je Stufe (★ bis ★★★), Rang (Bahnhofs-Azubi bis Bahnchef) mit XP-Leiste, **Tribe:** „Zeig deinen Zug jemandem!" (Mein-Zug-Bildschirm, Rang-Aufstieg-Hinweis).
- **Offene Schleife:** Kessel-Leiste „Noch X Kohle bis zur nächsten Truhe", XP-Leiste zum nächsten Rang, Sammlung mit sichtbaren Lücken, gesperrte Stufen mit Stern-Ziel.
- **Gespeicherter Wert:** Waggons, Kohle, XP, Sterne, Tages-Serie (🔥), alles in `localStorage` (Schlüssel `lokfuehrerMathe4_v1`).
- **Sofort spielbar:** ein Tipp auf „Losfahren!" startet eine gemischte Fahrt.
- **Flow-Kanal:** 3 Stufen je Station, „empfohlen"-Markierung passt sich an (3 Sterne ohne Hilfe → nächste Stufe empfohlen). Stufen schalten mit 1 Stern frei, kein Frust-Lock.
- **Ethik:** Fehler kosten nie Besitz oder Rang. Pause-Hinweis nach 3 Fahrten (abschaltbar), keine Zeitlimits, keine Käufe. Belohnung nur für gelöste Aufgaben (Lösung gezeigt = keine Kohle). „Für Erwachsene": Übersicht, was geübt wird, plus Zahlen je Station.

## Datenschutz & Technik

Eine einzige `index.html`, kein CDN, keine Bilder, keine externen Requests. Grafik aus Emojis, CSS und Inline-SVG (Uhren). Keine Accounts, kein Tracking. Spielstand nur lokal im Browser.

## QA-Checkliste (LERNAPP-BAUANLEITUNG.md)

- ✅ JS-Syntax geprüft (`bun build`, fehlerfrei)
- ✅ Automatischer Logiktest (Bun, ohne Browser): je 2 000 Zeit-, 3 000 Additions- und 3 000 Multiplikationsaufgaben pro Stufe. Geprüft wurde unabhängig: Ergebnis stimmt mit direkter Rechnung überein (Ankunft = Abfahrt + Dauer usw., Ziffern des Ergebnisses = Summe, Teilprodukte = Produkt), die richtige Zerlegung ist die einzige mit passender Summe, Distraktoren enthalten nie die Lösung, Hinweise enthalten kein `NaN`/`undefined`, drei Fehler → Lösung wird angezeigt. Dazu je eine komplette Fahrt pro Station/Stufe inkl. Ergebnisbildschirm, Truhen (keine Dubletten, alle 20 Waggons erreichbar, danach Medaillen).
- ✅ Layout im Headless-Chrome bei iPad-Breite (820 px) angesehen: Uhren, Stellenwertschema, Rechenbaum, Zahlenfeld, Ergebnis, Zug-Sammlung
- ✅ Sperrlisten-Check (`klausurtexte_sperrliste.py`): kein gesperrter Text (alle Aufgaben sind selbst erzeugt)
- ✅ Offline, keine externen Requests · localStorage-Schlüssel einzigartig
- ✅ Alle Hooked-Pflichtelemente (siehe oben) · Grundregeln 1–8
- ➖ **Noch nicht getestet:** echtes Antippen auf dem iPad (Sprachausgabe, Zahlenfeld-Gefühl). Vor dem Einsatz einmal selbst eine Fahrt auf dem iPad spielen.

## Weiterentwicklung / offene Punkte

- Ideen: Stufe 4 mit mehr als 3 Summanden bzw. Subtraktion, Zeitspannen mit Tagen/Wochen, Klassencode-Wettbewerb (Tribe).
- Repo: `nielsfeels-2/lernspiele` (Sammel-Repo für alle Lernspiele).
