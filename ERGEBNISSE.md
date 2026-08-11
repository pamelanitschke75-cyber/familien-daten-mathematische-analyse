# Ergebnisse

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

Personenbezogene Kürzel werden nicht verwendet. Die Datensätze sind ausschließlich mit den neutralen Kennungen `N01` bis `N23` bezeichnet.

Ereignis- und Referenzdaten, die keiner Kennung `N01` bis `N23` zugeordnet sind, bleiben als solche gekennzeichnet.

Die hier aufgeführten Übereinstimmungen sind zunächst mathematische Beobachtungen. Eine numerische Übereinstimmung allein gilt nicht als Beweis für die untersuchte Hypothese.

---

## 2. Ergebnisse Modulo 51

Für jede festgelegte Datumszahl `n` wurde der Rest bei Division durch `51` bestimmt.

Mehrfach auftretende Restwerte sind:

- Wert `25`: `N05` (05081920) und `N22` (29052022)
- Wert `28`: `N06` (19111921) und `N23` (24082024)
- Wert `21`: `N08` (12041937) und `N19` (25021998)

Weitere dokumentierte Ergebnisse sind unter anderem:

- `N04` (09051910) → `22`
- `N07` (23031937) → `31`
- `N12` (12081965) → `14`
- `N01` (18031975) → `7`
- Ereignisdatum `15082023` → `48`

Die vollständigen Einzelberechnungen sind in `BERECHNUNGEN.md` dokumentiert.

---

## 3. Ergebnisse Modulo 64

Bei Anwendung von `n mod 64` treten ebenfalls gleiche Restwerte bei unterschiedlichen Datensätzen auf.

Dokumentierte Wiederholungen sind:

- `N12` (12081965) → `45`
- `N02` (08101997) → `45`

- `N11` (02091963) → `59`
- `N20` (10102011) → `59`

- `N13` (16051978) → `10`
- `N14` (22091978) → `10`

- `N01` (18031975) → `39`
- Ereignisdatum `13082023` → `39`
- Ereignisdatum `15082023` → `39`

Weitere dokumentierte Ergebnisse sind:

- `N03` (02041907) → `51`
- `N06` (19111921) → `49`
- `N07` (23031937) → `1`
- `N08` (12041937) → `17`
- `N21` (06092016) → `48`
- Ereignisdatum `20041968` → `48`

Die vollständigen Einzelberechnungen sind in `BERECHNUNGEN.md` dokumentiert.

---

## 4. Ergebnisse der Ziffernsummen

Für jede Datumszahl wurde die Summe ihrer einzelnen Ziffern gebildet.

Eine dokumentierte Wiederholung ist:

- `N13` (16051978) → Ziffernsumme `37`
- `N17` (16061986) → Ziffernsumme `37`

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

- `N07` (23031937) → Jahr `1937` → `1 + 9 + 3 + 7 = 20`
- `N08` (12041937) → Jahr `1937` → `1 + 9 + 3 + 7 = 20`
- `N15` (04061982) → Jahr `1982` → `1 + 9 + 8 + 2 = 20`

Die vollständigen Jahresziffernsummen aller Datensätze sind in `BERECHNUNGEN.md` dokumentiert.

---

## 6. Ergebnisse aus Tag und Monat

Zusätzlich wurden für die festgelegten Datumswerte die Operationen `Tag + Monat` und `Tag × Monat` untersucht.

Eine dokumentierte Wiederholung bei `Tag × Monat` ist der Wert `80`:

- `N13` (16051978) → `16 × 5 = 80`
- `N02` (08101997) → `8 × 10 = 80`
- Ereignisdatum `20041968` → `20 × 4 = 80`

Weitere Beispiele:

- `N08` (12041937) → `12 + 4 = 16` und `12 × 4 = 48`
- `N01` (18031975) → `18 + 3 = 21` und `18 × 3 = 54`
- `N21` (06092016) → `6 + 9 = 15` und `6 × 9 = 54`

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

Die Ergebnisse dieser Datei beruhen ausschließlich auf den in `DATEN.md` festgelegten Ausgangswerten und den in `METHODIK.md` beschriebenen Verfahren.

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