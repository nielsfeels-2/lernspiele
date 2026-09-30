# 🎭 Telling or Showing? · EF Englisch · UV 1 „Growing up"

Kleines Lernspiel zur **direkten und indirekten Charakterisierung** — Aufgabe 2 der
Klausur vom 09.10.2026. 15 Sätze, zwei große Buttons, sofortiges Feedback mit
Begründung und Zeilenangabe.

**▶️ Live spielen:** https://nielsfeels-2.github.io/lernspiele/telling-or-showing-ef/

## Konzept (Weg A, eigenständiges Spiel)

- **Lernziel:** *telling* (der Text sagt direkt, wie jemand ist) von *showing*
  (der Text zeigt es durch Handlung, Rede, Reaktion) unterscheiden.
- **Mechanik:** Zitat lesen → TELLING oder SHOWING tippen → sofort Rückmeldung
  mit einer Zeile Begründung. Danach das nächste Zitat, Reihenfolge jedes Mal neu.
- **Belohnung:** Jede richtige Antwort gibt ein Belegkärtchen aus wechselndem
  Vorrat; drei richtige in Folge machen es golden. Sterne für die Runde,
  ein teilbarer Ergebnis-Code am Ende, eine Sammlung, die über Sessions wächst.

## Inhalt — abgeleitet aus zwei Charakterisierungen

**Die Items sind nicht frei gewählt.** Grundlage ist
`…/UV EF1-1 Growing up/CHARAKTERISIERUNGEN_Eleven_KickTheMoon.md`: zwei
vollständige Charakterisierungen der **Hauptfiguren** — Rachel („Eleven") und
Ilyas („Kick the Moon") — aufgebaut nach dem Raster des Fachschafts-EWH
(Kategorie → Merkmal → Beleg, getrennt nach direct und indirect). Aus diesen
Belegtabellen sind die 15 Items rückwärts gezogen.

Jedes Item stiftet also ein **Merkmal der Hauptfigur**; das Feedback nennt es.
Beschreibungen von Nebenfiguren kommen nicht vor — die Klausuraufgabe lautet
„characterizing **the protagonist**".

| Figur | Text | direct | indirect |
|---|---|---|---|
| Rachel | Sandra Cisneros, *Eleven* | 4 | 4 |
| Ilyas | Muhammad Khan, *Kick the Moon* (Extract 1) | 3 | 4 |

Quellen: `…/Texte/Textblaetter/M1_Eleven_Textblatt.pdf` ·
`…/Texte/M6_KickTheMoon_Extract1.md` (Camden Town EF, S. 12–14).
Zeilenangaben nach dem jeweiligen Schülermaterial.

**„Powder" kommt nicht vor.** Die Stunde ist ausgefallen, der Kurs kennt den Text
nicht (Stand 30.09.2026, siehe `00_RESTPLAN_bis_Klausur.md` v4).

**Jedes Item trägt die Behauptung, das Zitat ist der Beleg.** Oben steht das
Merkmal („Ilyas ist nachtragend und rächt sich im Kleinen."), darunter die
Stelle — gefragt wird, ob der Text das Merkmal *sagt* oder *zeigt*. Das ist
derselbe Schritt, den Aufgabe 2 der Klausur verlangt.

### Zwei Korrekturen am 30.09.2026

**(1) Nebenfiguren statt Hauptfigur.** Die erste Fassung hatte Sätze genommen
und etikettiert, ohne vorher zu charakterisieren. Zwei Items betrafen dadurch
Lee und Alice, nicht den Protagonisten. Äußerlichkeiten **gehören** zur
Charakterisierung — der EWH führt „Aussehen" unter direct, Rachels „skinny"
(l. 33) steht deshalb drin —, aber es müssen die der Hauptfigur sein.

**(2) Stimmung statt Eigenschaft.** Die zweite Fassung fragte unter anderem zu
„Humiliation spreads over me like a rash" (l. 92). Der Satz sagt, dass Ilyas
sich gerade gedemütigt fühlt — das würde jeder. Für die Charakterisierung gibt
er nichts her, das „Merkmal" wäre eine Umformulierung. Alle Items, zu denen sich
kein Merkmal *jenseits* der Stelle formulieren lässt, sind raus: momentane
Körperreaktionen (prickelnder Nacken, zitternde Lippe, „feeling sick inside").
An ihrer Stelle stehen jetzt Belege für Haltungen und Verhaltensmuster —
Ilyas' jahrelanges Sparen, seine kleine Rache an Ryan, Rachels Trost für ihre
Mutter, ihre Auflehnung, die nur im Kopf stattfindet.

### Gegenprobe

Jedes Zitat wurde als Wortfolge gegen den Quelltext geprüft — Fußnotenziffern,
Zeilennummern, Anführungszeichen und Silbentrennung am Zeilenende
herausgerechnet. Prüfskript: `12_SCRIPTS/ef_zitate_pruefen.py` —
bei Änderungen am Item-Pool erneut laufen lassen.

## Einordnung im Erwartungshorizont

Der EWH zur Klausur führt **direct** und **indirect characterization** als zwei
eigene Kriterien mit **je 7 Punkten** (von 17). Wer nur eine Sorte liefert, kommt
über rund 10 Punkte nicht hinaus. Genau diese Trennung übt das Spiel.

Eine Besonderheit, die im Spiel bewusst nicht vorkommt: Sätze, die **beides**
sind. Für ein Quiz mit Sofort-Feedback brauchen die Items eindeutige Antworten —
der Doppelblick gehört in den Unterricht (Folie 34 des Decks).

## Grundregeln 1–8 (Bauanleitung)

| | |
|---|---|
| 1 Eine HTML-Datei | ✅ kein CDN, keine externen Fonts, keine Bilder — Grafik aus Emoji und CSS |
| 2 Offline, anonym, DSGVO | ✅ ein `localStorage`-Schlüssel `ef-telling-showing-v1`, keine Namen, keine Übertragung |
| 3 iPad-first | ✅ Buttons ≥ 96 px, `user-scalable=no`, `touch-action: manipulation`, kein Hover nötig |
| 4 Kein Pay-to-win | ✅ Belege gibt es ausschließlich für richtige Antworten |
| 5 Kein Bestrafen | ✅ Fehler brechen nur die Serie; die Sammlung schrumpft nie (im Test geprüft) |
| 6 Lernkopplung | ✅ kein Fortschritt ohne richtige Antwort |
| 7 Sprache | ✅ Oberfläche Deutsch, Zitate Englisch — Zielgruppe EF, Sprachausgabe nicht nötig |
| 8 Curriculum | ✅ KLP EF „Growing up", Lehrwerkstexte der laufenden Reihe |

## Hooked-Pflichtelemente

| | |
|---|---|
| Variable Belohnung | ✅ Beleg aus 10 Motiven zufällig; Serie von 3 → goldener Beleg |
| Hunt · Self · Tribe | ✅ Belegsammlung · Sterne und Rekord · teilbarer Code „Zeig das jemandem" |
| Offene Schleife | ✅ Endbildschirm nennt das nächste Ziel (fehlende Sterne, 5× Gold) |
| Gespeicherter Wert | ✅ Sammlung, Rekord und längste Serie wachsen über Sessions |
| Sofort spielbar | ✅ ein Tap bis zur ersten Frage, Regel steht auf den Buttons |
| Flow-Kanal | ✅ Begründung zu jeder Antwort, Reihenfolge jedes Mal neu |
| Ethik-Check | ✅ Sessionbremse nach 3 Runden, Erwachsenen-Ecke auf dem Startbildschirm |

## QA

| Prüfung | Ergebnis |
|---|---|
| JS-Syntax (JavaScriptCore, `new Function`) | ✅ fehlerfrei |
| Volldurchlauf richtig → 15/15, 3 Sterne, 5 goldene | ✅ automatisiert geprüft |
| Volldurchlauf falsch → 0/15, Sammlung unverändert | ✅ automatisiert geprüft |
| Jedes Item lösbar, Antwort gültig, keine Dubletten | ✅ automatisiert geprüft |
| Alle Zitate im Quelltext belegt | ✅ 15/15 |
| Keine externen Requests | ✅ keine `http(s)`-URL in der Datei außer im Fließtext des READMEs |
| `localStorage`-Schlüssel einzigartig | ✅ `ef-telling-showing-v1` |

> ⚠️ **Noch nicht am Gerät getestet.** Syntax und Logik laufen headless durch;
> ein Blick auf dem iPad vor dem Einsatz schadet nicht.

## Ausliefern

Ordnerinhalt ins Repo `nielsfeels-2/lernspiele` als `telling-or-showing-ef/`
hochladen (GitHub Pages). QR-Code: `qr-telling-or-showing-ef.png`.
