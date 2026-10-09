# Ergebnisse

**Aktueller Ergebnisstand:** Version 1.2 (Neubewertung am Ende); Kennungsstand 1.2.1 mit P01–P25. Die historischen Vergleiche verwenden nun dieselben P-Kennungen für unveränderte Datensätze; die frühere N-Bezeichnung ist im `CHANGELOG.md` zugeordnet.

## Version 1.0

## 1. Zweck dieser Datei

Diese Datei dokumentiert die Ergebnisse der auf die festgelegten Ausgangsdaten angewendeten Berechnungen.

Erfasst werden insbesondere:

- Modulo-51-Werte
- Modulo-64-Werte
- Ziffernsummen
- Jahresziffernsummen
- Berechnungen aus Tag und Monat
- direkt beobachtbare numerische Wiederholungen

Personenbezogene Kürzel werden nicht verwendet. Die Datensätze sind ausschließlich mit den neutralen Kennungen `P01` bis `P23` bezeichnet.

Ereignis- und Referenzdaten, die keiner Kennung `P01` bis `P23` zugeordnet sind, bleiben als solche gekennzeichnet.

Die hier aufgeführten Übereinstimmungen sind zunächst mathematische Beobachtungen. Eine numerische Übereinstimmung allein gilt nicht als Beweis für die untersuchte Hypothese.

---

## 2. Ergebnisse Modulo 51

Für jede festgelegte Datumszahl `n` wurde der Rest bei Division durch `51` bestimmt.

Mehrfach auftretende Restwerte sind:

- Wert `25`: `P05` (05081920) und `P22` (29052022)
- Wert `28`: `P06` (19111921) und `P23` (24082024)
- Wert `21`: `P08` (12041937) und `P19` (25021998)

Weitere dokumentierte Ergebnisse sind unter anderem:

- `P04` (09051910) → `22`
- `P07` (23031937) → `31`
- `P12` (12081965) → `14`
- `P01` (18031975) → `7`
- Ereignisdatum `15082023` → `48`

Die vollständigen Einzelberechnungen sind in `BERECHNUNGEN.md` dokumentiert.

---

## 3. Ergebnisse Modulo 64

Bei Anwendung von `n mod 64` treten ebenfalls gleiche Restwerte bei unterschiedlichen Datensätzen auf.

Dokumentierte Wiederholungen sind:

- `P12` (12081965) → `45`
- `P02` (08101997) → `45`

- `P11` (02091963) → `59`
- `P20` (10102011) → `59`

- `P13` (16051978) → `10`
- `P14` (22091978) → `10`

- `P01` (18031975) → `39`
- Ereignisdatum `13082023` → `39`
- Ereignisdatum `15082023` → `39`

Weitere dokumentierte Ergebnisse sind:

- `P03` (02041907) → `51`
- `P06` (19111921) → `49`
- `P07` (23031937) → `1`
- `P08` (12041937) → `17`
- `P21` (06092016) → `48`
- Ereignisdatum `20041968` → `48`

Die vollständigen Einzelberechnungen sind in `BERECHNUNGEN.md` dokumentiert.

---

## 4. Ergebnisse der Ziffernsummen

Für jede Datumszahl wurde die Summe ihrer einzelnen Ziffern gebildet.

Eine dokumentierte Wiederholung ist:

- `P13` (16051978) → Ziffernsumme `37`
- `P17` (16061986) → Ziffernsumme `37`

Beispiel:

`16051978`

`1 + 6 + 0 + 5 + 1 + 9 + 7 + 8 = 37`

und:

`16061986`

`1 + 6 + 0 + 6 + 1 + 9 + 8 + 6 = 37`

Weitere Ziffernsummen sind vollständig in `BERECHNUNGEN.md` dokumentiert.

---

## 5. Ergebnisse der Jahresziffernsummen

Für jedes Datum wurde zusätzlich die Ziffernsumme ausschließlich des vierstelligen Jahres berechnet.

Eine dokumentierte Wiederholung ist der Wert `20`:

- `P07` (23031937) → Jahr `1937` → `1 + 9 + 3 + 7 = 20`
- `P08` (12041937) → Jahr `1937` → `1 + 9 + 3 + 7 = 20`
- `P15` (04061982) → Jahr `1982` → `1 + 9 + 8 + 2 = 20`

Die vollständigen Jahresziffernsummen aller Datensätze sind in `BERECHNUNGEN.md` dokumentiert.

---

## 6. Ergebnisse aus Tag und Monat

Zusätzlich wurden für die festgelegten Datumswerte die Operationen `Tag + Monat` und `Tag × Monat` untersucht.

Eine dokumentierte Wiederholung bei `Tag × Monat` ist der Wert `80`:

- `P13` (16051978) → `16 × 5 = 80`
- `P02` (08101997) → `8 × 10 = 80`
- Ereignisdatum `20041968` → `20 × 4 = 80`

Weitere Beispiele:

- `P08` (12041937) → `12 + 4 = 16` und `12 × 4 = 48`
- `P01` (18031975) → `18 + 3 = 21` und `18 × 3 = 54`
- `P21` (06092016) → `6 + 9 = 15` und `6 × 9 = 54`

Die vollständigen Ergebnisse für `Tag + Monat` und `Tag × Monat` sind in `BERECHNUNGEN.md` dokumentiert.

---

## 7. Referenzwert AR

Der in `DATEN.md` dokumentierte Referenzwert lautet:

`1911 | AR`

Die dazu dokumentierten mathematischen Ergebnisse sind:

- `1911 mod 51 = 24`
- `1911 mod 64 = 55`
- 6-Bit-Darstellung von `55` → `110111`
- Ziffernsumme → `12`
- Zerlegung `19 + 11 = 30`

Für das Bezugsjahr `2026` ergibt sich außerdem:

`2026 - 1911 = 115`

Die Zahl `115` ist damit ein berechnetes Ergebnis der zeitabhängigen Differenz zwischen dem Referenzwert `1911` und dem Bezugsjahr `2026`.

Eine mögliche geografische Interpretation wird nicht in dieser Datei vorgenommen, sondern getrennt in `KOORDINATEN.md` untersucht.

---

## 8. Zusammenfassung

Die angewendeten Rechenverfahren erzeugen mehrere dokumentierte Wiederholungen und numerische Übereinstimmungen innerhalb der festgelegten Datensätze.

Die vorangehenden Ergebnisse der Version 1.0 beruhen auf dem damaligen Stand P01 bis P23 in `DATEN.md` und den in `METHODIK.md` beschriebenen Verfahren.

Die vollständigen Rechenwege befinden sich in `BERECHNUNGEN.md`.

Mathematische Ergebnisse werden von ihrer möglichen Bedeutung getrennt dokumentiert.

Weiterführende geografische Vergleiche befinden sich in `KOORDINATEN.md`.

Daraus entstandene Fragestellungen und mögliche Zusammenhänge werden getrennt in `HYPOTHESEN.md` behandelt.

Numerische Übereinstimmungen werden als Beobachtungen dokumentiert. Ob sie eine Hypothese stützen und welche Bedeutung sie besitzen, muss anhand weiterer unabhängig überprüfbarer Hinweise untersucht werden.

---

**Ergebnisstand:** Version 1.0  
**Ausgangsdaten:** `DATEN.md`  
**Methodik:** `METHODIK.md`  
**Berechnungen:** `BERECHNUNGEN.md`

---

Diese Datei dokumentiert mathematische Ergebnisse und direkt beobachtbare numerische Übereinstimmungen. Interpretationen und Hypothesen werden getrennt geführt.

---

## Version 1.1 – Ergebnis der vollständigen Neuberechnung (29.09.2026)

Die aktuelle Untersuchung umfasst **P01 bis P24 (24 Familiendaten)**, **drei Ereignis-/Paardaten** und den eigenständigen Referenzwert **AR = 1911**. `BERECHNUNGEN.md` enthält sämtliche Einzelwerte und alle Wiederholungsgruppen für jede Methode. Die vorangehenden Ergebnisse der Version 1.0 bleiben als historischer Stand mit P01 bis P23 erhalten.

### Neue Ergebnisse durch P24

| Methode | P24 | Vergleich im aktuellen Datensatz |
|---|---:|---|
| mod 51 | 6 | kein weiterer gleicher Rest |
| mod 64 | 18 | kein weiterer gleicher Rest; sechs Bit: `010010` |
| Ziffernsumme | 21 | gleich Ereignis `15082023` |
| Jahresziffernsumme | 17 | gleich P03 und P10 |
| Tag+Monat | 31 | gleich P14 |
| Tag×Monat | 210 | kein weiterer gleicher Wert |

Gleiche 6-Bit-Folgen entsprechen genau gleichen mod-64-Ergebnissen und sind keine zusätzliche unabhängige Übereinstimmung. Die Ziffernsumme `21` ist ein Vergleich zwischen einer Familienkennung und einem getrennten Ereignisdatum; sie ist **keine** Wiederholung zwischen zwei Familiendatensätzen.

### Vollständige Wiederholungen in der aktuellen Datengrundlage

| Methode | Gleiche Werte und beteiligte Datensätze |
|---|---|
| mod 51 | 21: P08/P19; 24: P18/AR (Referenzwert); 25: P05/P22; 28: P06/P23 |
| mod 64 / sechs Bit | 10: P13/P14; 39: P01 und Ereignisse `13082023`/`15082023`; 45: P02/P12; 48: P21 und Ereignis `20041968`; 59: P11/P20 |
| Ziffernsumme | 21: P24 und Ereignis `15082023`; 22: P22/P23; 25: P04/P05/P06; 30: P11/P15 und Ereignis `20041968`; 36: P16/P19; 37: P13/P17 |
| Jahresziffernsumme | 7: Ereignisse `13082023`/`15082023`; 17: P03/P10/P24; 20: P07/P08/P15; 22: P01/P16; 24: P17 und Ereignis `20041968`; 25: P13/P14; 27: P18/P19 |
| Tag+Monat | 14: P04/P16; 15: P18/P21; 20: P12/P20; 21: P01/P10/P13 und Ereignis `13082023`; 31: P14/P24 |
| Tag×Monat | 18: P09/P11; 45: P04/P16; 54: P01/P21; 80: P02/P13 und Ereignis `20041968`; 96: P12/P17 |

Der Vergleich mit AR gilt nur für dieselbe Operation; AR ist keine vierte Ereignis- oder Familienkennung. Seine Zerlegung `19 + 11 = 30` ist kein Ziffernsummen-Treffer. Alle bisherigen 23 Familiendaten und drei Ereignisdaten wurden erneut berechnet; ihre Einzelwerte stimmen mit Version 1.0 überein. P24 verändert bestehende Rechenwerte nicht, erweitert aber die oben genannten Gruppen.

### Referenzwert, Koordinaten und Hypothesen

Für AR bleiben `1911 mod 51 = 24` (gleich P18), `1911 mod 64 = 55` (sechs Bit `110111`), Ziffernsumme `12` und `2026 - 1911 = 115` unverändert. Der Wert `115` ist ein zeitbezogenes Rechenergebnis, keine bestätigte Koordinate.

P24 liefert rechnerische Werte, aber keine unabhängige Information über einen Ort, die „Black Box“ oder MH370. Eine Übereinstimmung allein bestätigt keine der offenen Hypothesen. Historisch abweichende Datumsangaben im älteren `Codes-Projekt` werden nicht in die aktuelle Ausgangsbasis gemischt.

**Ergebnisstand:** Version 1.1 · vollständig neu berechnet; weitergehende Interpretation offen.


---

## Version 1.2 – Ergebnis mit P25 (29.09.2026)

Der aktuelle Datensatz umfasst **25 Personen mit 24 verschiedenen Familiendatumswerten**, drei getrennte Ereignis-/Paardaten und AR = `1911`. Die vollständige Neuberechnung und sämtliche Wiederholungsgruppen stehen in `BERECHNUNGEN.md` unter Version 1.2.

P25 und P02 sind zwei eigenständige Personendatensätze. Beide tragen das Datum `08.10.1997`. Für P25 ergeben sich mod 51 = `35`, mod 64 = `45` (`101101`), Ziffernsumme = `35`, Jahres-QS = `26`, Tag+Monat = `18` und Tag×Monat = `80`. P02 hat dieselben sechs Ergebnisse. Dadurch kommt bei mod 51 die Gruppe `35: P02/P25` hinzu; bei mod 64 wächst `45: P02/P12/P25`. Die neuen Gruppen sind `35: P02/P25` (Ziffernsumme), `26: P02/P25` (Jahres-QS) und `18: P02/P25` (Tag+Monat). Die Gruppe `80` (Tag×Monat) umfasst nun P02, P13, P25 und Ereignis `20041968`. Alle übrigen Gruppen aus Version 1.1 bleiben unverändert.

P02 und P25 sind **zwei Personen, aber kein zweiter unabhängiger Datumswert**. Eine Auswertung von Häufigkeiten nach Personen und eine Auswertung nach verschiedenen Datumswerten beantworten unterschiedliche Fragen. Die Doppelung darf nicht als unabhängige Bestätigung eines Musters gezählt werden. Auch bei mod 64 und seiner 6-Bit-Schreibweise liegt dieselbe eine Operation vor.

AR bleibt separat: mod 51 = `24` (auch P18), mod 64 = `55`, Ziffernsumme = `12`, `2026 - 1911 = 115`. P25 liefert keinen unabhängigen Beleg zu Area 51, einer „Black Box“ oder MH370. Die Familienordnung und eine mögliche spätere Umnummerierung beeinflussen nur die Bezeichnungen, keine Rechenwerte.

**Ergebnisstand:** Version 1.2 · alle Werte geprüft; Hypothesen weiter offen.
