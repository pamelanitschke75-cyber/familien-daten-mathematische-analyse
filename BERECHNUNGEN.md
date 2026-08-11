# Berechnungen

## Version 1.0

Diese Datei enthält die reproduzierbaren Berechnungen auf Grundlage von `DATEN.md` und `METHODIK.md`.

Alle Werte wurden mit den aktuell festgelegten Ausgangsdaten neu berechnet.

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