# Berechnungen

**Aktueller Berechnungsstand:** Version 1.1 (vollständige Tabelle unten). Die Version 1.0 bleibt als historischer Vergleich erhalten.

## Version 1.0

Diese Datei enthält die reproduzierbaren Berechnungen auf Grundlage von `DATEN.md` und `METHODIK.md`.

Die folgende Tabelle dokumentiert den historischen Stand der Version 1.0 mit N01 bis N23. Die vollständige Neuberechnung für Version 1.1 steht unten.

## Familiendaten
 | Zahlenfolge | Kürzel | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---|---:|---:|---|---:|---:|---:|---:|
| 02041907 | N03 | 20 | 51 | 110011 | 23 | 17 | 6 | 8 |
| 09051910 | N04 | 22 | 6 | 000110 | 25 | 11 | 14 | 45 |
| 05081920 | N05 | 25 | 0 | 000000 | 25 | 12 | 13 | 40 |
| 19111921 | N06 | 28 | 49 | 110001 | 25 | 13 | 30 | 209 |
| 23031937 | N07 | 31 | 1 | 000001 | 28 | 20 | 26 | 69 |
| 12041937 | N08 | 21 | 17 | 010001 | 27 | 20 | 16 | 48 |
| 18011942 | N09 | 17 | 38 | 100110 | 26 | 16 | 19 | 18 |
| 09121952 | N10 | 41 | 32 | 100000 | 29 | 17 | 21 | 108 |
| 02091963 | N11 | 45 | 59 | 111011 | 30 | 19 | 11 | 18 |
| 12081965 | N12 | 14 | 45 | 101101 | 32 | 21 | 20 | 96 |
| 18031975 | N01 | 7 | 39 | 100111 | 34 | 22 | 21 | 54 |
| 16051978 | N13 | 34 | 10 | 001010 | 37 | 25 | 21 | 80 |
| 22091978 | N14 | 2 | 10 | 001010 | 38 | 25 | 31 | 198 |
| 04061982 | N15 | 36 | 30 | 011110 | 30 | 20 | 10 | 24 |
| 05091984 | N16 | 42 | 16 | 010000 | 36 | 22 | 14 | 45 |
| 16061986 | N17 | 46 | 34 | 100010 | 37 | 24 | 22 | 96 |
| 03121989 | N18 | 24 | 5 | 000101 | 33 | 27 | 15 | 36 |
| 08101997 | N02 | 35 | 45 | 101101 | 35 | 26 | 18 | 80 |
| 25021998 | N19 | 21 | 46 | 101110 | 36 | 27 | 27 | 50 |
| 10102011 | N20 | 33 | 59 | 111011 | 6 | 4 | 20 | 100 |
| 06092016 | N21 | 15 | 48 | 110000 | 24 | 9 | 15 | 54 |
| 29052022 | N22 | 25 | 54 | 110110 | 22 | 6 | 34 | 145 |
| 24082024 | N23 | 28 | 40 | 101000 | 22 | 8 | 32 | 192 |

## Ereignis- und Paardaten

| Zahlenfolge | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---:|---:|---|---:|---:|---:|---:|
| 20041968 | 39 | 48 | 110000 | 30 | 24 | 24 | 80 |
| 13082023 | 13 | 39 | 100111 | 19 | 7 | 21 | 104 |
| 15082023 | 48 | 39 | 100111 | 21 | 7 | 23 | 120 |

## Referenzwert AR

Ausgangswert:

`1911 | AR`

Berechnungen:

- `1911 mod 51 = 24`
- `1911 mod 64 = 55`
- 6-Bit-Darstellung von 55: `110111`
- Ziffernsumme: `1 + 9 + 1 + 1 = 12`
- Zerlegung `19 + 11 = 30`

Zusätzlich dokumentierte Differenz:

`2026 - 1911 = 115`

Diese Differenz ist eine mathematisch korrekte Berechnung zwischen dem Referenzwert `1911` und dem Bezugsjahr `2026`.

Eine mögliche geografische Interpretation der Zahl 115 wird getrennt in `KOORDINATEN.md` untersucht.

## Auffällige Wiederholungen

### mod 64
02041907 | N03 → 51
12081965 | N12 → 45
08101997 | N02 → 45
02091963 | N11 → 59
10102011 | N20 → 59
16051978 | N13 → 10
22091978 | N14 → 10
18031975 | N01 → 39
13082023 → 39
15082023 → 39

### mod 51

- Wert `22`: `09051910 | N04`
- Wert `25`: `05081920 | N05` und `29052022 | N22`
- Wert `28`: `19111921 | N06` und `24082024 | N23`
- Wert `21`: `12041937 | N08` und `25021998 | N19`

### Weitere direkte Wiederholungen

- Ziffernsumme `37`: `16051978 | N13` und `16061986 | N17`
- Jahresziffernsumme `20`: `23031937 | N07`, `12041937 | N08`, `04061982 | N15`
- Tag×Monat `80`: `16051978 | N13`, `08101997 | N02`, `20041968`

## Hinweis

Diese Datei enthält ausschließlich mathematische Berechnungen und direkt beobachtbare Wiederholungen.

Eine Interpretation dieser Ergebnisse wird getrennt dokumentiert.

---

## Hinweis

Diese Datei enthält ausschließlich mathematische Berechnungen und direkt beobachtbare Wiederholungen.

Eine Interpretation dieser Ergebnisse wird getrennt dokumentiert.

---

**Berechnungsstand:** Version 1.0  
**Grundlage:** `DATEN.md`  
**Methodik:** `METHODIK.md`

---

## Version 1.1 – vollständige Neuberechnung (29.09.2026)

Grundlage sind alle 24 Familiendatensätze, alle drei Ereignis-/Paardaten und der eigenständige Referenzwert aus `DATEN.md`. Die Methoden aus `METHODIK.md` (Version 1.0) bleiben unverändert. Die vorangehende Version 1.0 bleibt als historischer 23-Datensatz-Stand erhalten.

### Alle Familiendaten N01–N24

| Kennung | Zahlenfolge | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---:|---:|---:|---|---:|---:|---:|---:|
| N01 | 18031975 | 7 | 39 | `100111` | 34 | 22 | 21 | 54 |
| N02 | 08101997 | 35 | 45 | `101101` | 35 | 26 | 18 | 80 |
| N03 | 02041907 | 20 | 51 | `110011` | 23 | 17 | 6 | 8 |
| N04 | 09051910 | 22 | 6 | `000110` | 25 | 11 | 14 | 45 |
| N05 | 05081920 | 25 | 0 | `000000` | 25 | 12 | 13 | 40 |
| N06 | 19111921 | 28 | 49 | `110001` | 25 | 13 | 30 | 209 |
| N07 | 23031937 | 31 | 1 | `000001` | 28 | 20 | 26 | 69 |
| N08 | 12041937 | 21 | 17 | `010001` | 27 | 20 | 16 | 48 |
| N09 | 18011942 | 17 | 38 | `100110` | 26 | 16 | 19 | 18 |
| N10 | 09121952 | 41 | 32 | `100000` | 29 | 17 | 21 | 108 |
| N11 | 02091963 | 45 | 59 | `111011` | 30 | 19 | 11 | 18 |
| N12 | 12081965 | 14 | 45 | `101101` | 32 | 21 | 20 | 96 |
| N13 | 16051978 | 34 | 10 | `001010` | 37 | 25 | 21 | 80 |
| N14 | 22091978 | 2 | 10 | `001010` | 38 | 25 | 31 | 198 |
| N15 | 04061982 | 36 | 30 | `011110` | 30 | 20 | 10 | 24 |
| N16 | 05091984 | 42 | 16 | `010000` | 36 | 22 | 14 | 45 |
| N17 | 16061986 | 46 | 34 | `100010` | 37 | 24 | 22 | 96 |
| N18 | 03121989 | 24 | 5 | `000101` | 33 | 27 | 15 | 36 |
| N19 | 25021998 | 21 | 46 | `101110` | 36 | 27 | 27 | 50 |
| N20 | 10102011 | 33 | 59 | `111011` | 6 | 4 | 20 | 100 |
| N21 | 06092016 | 15 | 48 | `110000` | 24 | 9 | 15 | 54 |
| N22 | 29052022 | 25 | 54 | `110110` | 22 | 6 | 34 | 145 |
| N23 | 24082024 | 28 | 40 | `101000` | 22 | 8 | 32 | 192 |
| N24 | 21101970 | 6 | 18 | `010010` | 21 | 17 | 31 | 210 |

### Alle Ereignis- und Paardaten

| Zahlenfolge | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---:|---:|---:|---|---:|---:|---:|---:|
| 20041968 | 39 | 48 | `110000` | 30 | 24 | 24 | 80 |
| 13082023 | 13 | 39 | `100111` | 19 | 7 | 21 | 104 |
| 15082023 | 48 | 39 | `100111` | 21 | 7 | 23 | 120 |

### Eigenständiger Referenzwert AR

- `1911 mod 51 = 24` (1911 = 37 × 51 + 24)
- `1911 mod 64 = 55` (1911 = 29 × 64 + 55); sechs Bit: `110111`
- Ziffernsumme `1 + 9 + 1 + 1 = 12`; dokumentierte Zerlegung `19 + 11 = 30`
- Zeitbezogene Differenz mit dem Untersuchungsjahr: `2026 - 1911 = 115`

AR ist kein vollständiges Datum; Tag/Monat- und Jahres-QS-Datumsspalten werden darauf nicht angewendet.

### Rechenprobe N24

- `21101970 = 413764 × 51 + 6` → mod 51 = `6`
- `21101970 = 329718 × 64 + 18` → mod 64 = `18` → sechs Bit `010010`
- Ziffernsumme: `2 + 1 + 1 + 0 + 1 + 9 + 7 + 0 = 21`
- Jahres-QS: `1 + 9 + 7 + 0 = 17`
- Tag+Monat: `21 + 10 = 31`; Tag×Monat: `21 × 10 = 210`

### Sämtliche Wiederholungen nach Methode (24 Familiendaten + 3 Ereignisdaten)

Nur Gruppen mit mindestens zwei gleichen Ergebnissen sind aufgeführt. Die Bezeichnung „Ereignis“ verweist auf die Zahlenfolge aus der Ereignistabelle und ist keine zusätzliche Familienkennung.

### mod 51

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 21 | N08, N19 |
| 25 | N05, N22 |
| 28 | N06, N23 |

### mod 64

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 10 | N13, N14 |
| 39 | N01, Ereignis 13082023, Ereignis 15082023 |
| 45 | N02, N12 |
| 48 | N21, Ereignis 20041968 |
| 59 | N11, N20 |

### Ziffernsumme

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 21 | N24, Ereignis 15082023 |
| 22 | N22, N23 |
| 25 | N04, N05, N06 |
| 30 | N11, N15, Ereignis 20041968 |
| 36 | N16, N19 |
| 37 | N13, N17 |

### Jahres-QS

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 7 | Ereignis 13082023, Ereignis 15082023 |
| 17 | N03, N10, N24 |
| 20 | N07, N08, N15 |
| 22 | N01, N16 |
| 24 | N17, Ereignis 20041968 |
| 25 | N13, N14 |
| 27 | N18, N19 |

### Tag+Monat

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 14 | N04, N16 |
| 15 | N18, N21 |
| 20 | N12, N20 |
| 21 | N01, N10, N13, Ereignis 13082023 |
| 31 | N14, N24 |

### Tag×Monat

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 18 | N09, N11 |
| 45 | N04, N16 |
| 54 | N01, N21 |
| 80 | N02, N13, Ereignis 20041968 |
| 96 | N12, N17 |

### Vergleich des eigenständigen Referenzwerts AR mit den Datumsrechnungen

AR ergibt bei mod 51 den Rest `24`, ebenso N18. Bei mod 64 ergibt AR `55`, bei der Ziffernsumme `12`; dafür gibt es in den 27 Datumswerten keine Gleichheit. AR bleibt dabei ein vierstelliger Referenzwert, kein Familien- oder Ereignisdatum. Die Zerlegung `19 + 11 = 30` und die Jahresdifferenz `115` sind andere Operationen und werden nicht als identische Methoden-Treffer gezählt.

N24 erzeugt keinen gleichen mod-51- oder mod-64-Rest und keinen gleichen Tag×Monat-Wert innerhalb des aktuellen Datensatzes. Seine Ziffernsumme `21` stimmt mit Ereignis `15082023`, seine Jahres-QS `17` mit N03 und N10, und Tag+Monat `31` mit N14 überein. Diese Gleichheiten sind rechnerische Beobachtungen, keine Belege für einen realen Zusammenhang.

**Berechnungsstand:** Version 1.1 · 24 + 3 Datumswerte und AR geprüft.
