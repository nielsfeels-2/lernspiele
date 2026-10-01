# Klausurtraining 2.3 · Connectives

**Kriterium 3 · Struktur · 5 Punkte** · Block *Aufbau* · Jahrgang *alle*

Verknüpfen statt aufzählen

**Live:** <https://nielsfeels-2.github.io/lernspiele/klausurtraining-23-connectives/>
· zurück zum [Hub](https://nielsfeels-2.github.io/lernspiele/klausurtraining/)

## Was das Modul trainiert (R1)

Ein Connective ist keine Verzierung. Es ist eine <b>Behauptung</b> darüber, wie zwei Sätze zusammenhängen — und die kann falsch sein.

## Technik

* eine HTML-Datei, offline lauffähig, kein CDN, keine Anmeldung
* `localStorage`-Schlüssel `kt-23-v1` · 8 Aufgaben je Runde
* 16 Items: 12× luecke, 4× wahl
* Quellen: gettysburg, vorgaben

**Nicht hier ändern.** Die Datei wird erzeugt:

```
uv run python 12_SCRIPTS/klausurtraining_bauen.py
```

Inhalte stehen in `12_SCRIPTS/klausurtraining_inhalte.py`.

## Abnahme nach R5

Jedes Item hat eine Begründung, die mehr sagt als die Aufgabe — das ist die
R2-Probe. `pruefe_module` prüft zusätzlich maschinell: Antwortindex,
Optionsdubletten, Lückenzeichen, Fehler- und Heilstellen bei Markieraufgaben,
Punktzahl im Kriterium, Schlüsselkonvention und **jedes Zitat gegen seine
Quelle**.

| # | Aufgabentyp | Format | Was eine richtige Antwort zeigt |
|---|---|---|---|
| 1 | WELCHE VERKNÜPFUNG PASST? | luecke | Gegensatz. Der zweite Satz sagt nicht die Folge, sondern das Gegenteil des Erwarteten. Therefore würde behaup… |
| 2 | WELCHE VERKNÜPFUNG PASST? | luecke | Folge. Weil Worte nicht genügen, bleibt die Tat — das ist genau Lincolns Gedankengang (ll. 14–17). |
| 3 | WELCHE VERKNÜPFUNG PASST? | luecke | Einräumen. Die Kürze spricht eher dagegen, dass ein Text berühmt wird — der Satz räumt das ein und widerspric… |
| 4 | WELCHE VERKNÜPFUNG PASST? | luecke | Hinzufügen. Beides gilt gleichzeitig und zeigt in dieselbe Richtung. Ein Gegensatz wäre falsch: Einfache Wört… |
| 5 | WELCHE VERKNÜPFUNG PASST? | luecke | Despite braucht ein Nomen (despite its length), however einen eigenen Satz. Nur although kann einen Nebensatz… |
| 6 | WELCHE VERKNÜPFUNG PASST? | luecke | Folge. Aus der Prämisse ergibt sich der zweite Satz — genau die Verbindung, die Lincoln in ll. 3–5 herstellt. |
| 7 | WELCHE VERKNÜPFUNG PASST? | luecke | Gegensatz zwischen Erwartung und Wirklichkeit. Therefore hieße: Weil sie eine lange Rede erwarteten, sprach e… |
| 8 | WELCHE VERKNÜPFUNG PASST? | luecke | On the one hand hat genau einen Partner: on the other hand. In the other hand ist kein Englisch, und on the c… |
| 9 | WELCHE VERKNÜPFUNG PASST? | luecke | Am Absatzanfang zeigt das Connective den Aufbau: Hier wird gebündelt, nicht ergänzt. Genau daran erkennt die … |
| 10 | WELCHE VERKNÜPFUNG PASST? | luecke | Reihenfolge. Der Text geht in Schritten vor; das Connective zeigt den Schritt. Eine Folge wäre zu stark — der… |
| 11 | WELCHE VERKNÜPFUNG PASST? | luecke | Zwei Wirkungen desselben Mittels. Das ist weder Folge noch Gegensatz — sie treten zusammen auf. |
| 12 | WELCHE VERKNÜPFUNG PASST? | luecke | Der zweite Satz sagt, was der erste bewirkt — genau der Übergang von Beleg zu Wirkung. In doing so ist dafür … |
| 13 | STIMMT DIE VERKNÜPFUNG? | wahl | Kurze Texte werden nicht durch ihre Kürze berühmt. Therefore behauptet eine Ursache und liegt damit sachlich … |
| 14 | STIMMT DIE VERKNÜPFUNG? | wahl | Der Gegensatz steht so im Text: „The world will little note, nor long remember what we say here but it can ne… |
| 15 | STIMMT DIE VERKNÜPFUNG? | wahl | Eine große Zuhörerschaft und eine kurze Rede widersprechen sich nicht. Das Connective tut so, als wäre da ein… |
| 16 | STIMMT DIE VERKNÜPFUNG? | wahl | Behauptung, dann Beispiel mit Beleg und Zeilenangabe — Verknüpfung und Belegtechnik greifen hier ineinander (… |
