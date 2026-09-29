# Berechnungen

**Aktueller Berechnungsstand:** Version 1.2 (vollständige Tabelle am Ende); Kennungsstand 1.2.1 mit P01–P25. Alle Zahlenwerte bleiben gleich. Die historischen Tabellen zeigen dieselben Datensätze mit den aktuellen P-Kennungen; die ursprünglichen N-Bezeichnungen sind im `CHANGELOG.md` zugeordnet.

## Version 1.0

Diese Datei enthält die reproduzierbaren Berechnungen auf Grundlage von `DATEN.md` und `METHODIK.md`.

Die folgende Tabelle dokumentiert den historischen Stand der Version 1.0 mit P01 bis P23. Die vollständige Neuberechnung für Version 1.1 steht unten.

## Familiendaten
 | Zahlenfolge | Kürzel | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---|---:|---:|---|---:|---:|---:|---:|
| 02041907 | P03 | 20 | 51 | 110011 | 23 | 17 | 6 | 8 |
| 09051910 | P04 | 22 | 6 | 000110 | 25 | 11 | 14 | 45 |
| 05081920 | P05 | 25 | 0 | 000000 | 25 | 12 | 13 | 40 |
| 19111921 | P06 | 28 | 49 | 110001 | 25 | 13 | 30 | 209 |
| 23031937 | P07 | 31 | 1 | 000001 | 28 | 20 | 26 | 69 |
| 12041937 | P08 | 21 | 17 | 010001 | 27 | 20 | 16 | 48 |
| 18011942 | P09 | 17 | 38 | 100110 | 26 | 16 | 19 | 18 |
| 09121952 | P10 | 41 | 32 | 100000 | 29 | 17 | 21 | 108 |
| 02091963 | P11 | 45 | 59 | 111011 | 30 | 19 | 11 | 18 |
| 12081965 | P12 | 14 | 45 | 101101 | 32 | 21 | 20 | 96 |
| 18031975 | P01 | 7 | 39 | 100111 | 34 | 22 | 21 | 54 |
| 16051978 | P13 | 34 | 10 | 001010 | 37 | 25 | 21 | 80 |
| 22091978 | P14 | 2 | 10 | 001010 | 38 | 25 | 31 | 198 |
| 04061982 | P15 | 36 | 30 | 011110 | 30 | 20 | 10 | 24 |
| 05091984 | P16 | 42 | 16 | 010000 | 36 | 22 | 14 | 45 |
| 16061986 | P17 | 46 | 34 | 100010 | 37 | 24 | 22 | 96 |
| 03121989 | P18 | 24 | 5 | 000101 | 33 | 27 | 15 | 36 |
| 08101997 | P02 | 35 | 45 | 101101 | 35 | 26 | 18 | 80 |
| 25021998 | P19 | 21 | 46 | 101110 | 36 | 27 | 27 | 50 |
| 10102011 | P20 | 33 | 59 | 111011 | 6 | 4 | 20 | 100 |
| 06092016 | P21 | 15 | 48 | 110000 | 24 | 9 | 15 | 54 |
| 29052022 | P22 | 25 | 54 | 110110 | 22 | 6 | 34 | 145 |
| 24082024 | P23 | 28 | 40 | 101000 | 22 | 8 | 32 | 192 |

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
02041907 | P03 → 51
12081965 | P12 → 45
08101997 | P02 → 45
02091963 | P11 → 59
10102011 | P20 → 59
16051978 | P13 → 10
22091978 | P14 → 10
18031975 | P01 → 39
13082023 → 39
15082023 → 39

### mod 51

- Wert `22`: `09051910 | P04`
- Wert `25`: `05081920 | P05` und `29052022 | P22`
- Wert `28`: `19111921 | P06` und `24082024 | P23`
- Wert `21`: `12041937 | P08` und `25021998 | P19`

### Weitere direkte Wiederholungen

- Ziffernsumme `37`: `16051978 | P13` und `16061986 | P17`
- Jahresziffernsumme `20`: `23031937 | P07`, `12041937 | P08`, `04061982 | P15`
- Tag×Monat `80`: `16051978 | P13`, `08101997 | P02`, `20041968`

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

### Alle Familiendaten P01–P24

| Kennung | Zahlenfolge | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---:|---:|---:|---|---:|---:|---:|---:|
| P01 | 18031975 | 7 | 39 | `100111` | 34 | 22 | 21 | 54 |
| P02 | 08101997 | 35 | 45 | `101101` | 35 | 26 | 18 | 80 |
| P03 | 02041907 | 20 | 51 | `110011` | 23 | 17 | 6 | 8 |
| P04 | 09051910 | 22 | 6 | `000110` | 25 | 11 | 14 | 45 |
| P05 | 05081920 | 25 | 0 | `000000` | 25 | 12 | 13 | 40 |
| P06 | 19111921 | 28 | 49 | `110001` | 25 | 13 | 30 | 209 |
| P07 | 23031937 | 31 | 1 | `000001` | 28 | 20 | 26 | 69 |
| P08 | 12041937 | 21 | 17 | `010001` | 27 | 20 | 16 | 48 |
| P09 | 18011942 | 17 | 38 | `100110` | 26 | 16 | 19 | 18 |
| P10 | 09121952 | 41 | 32 | `100000` | 29 | 17 | 21 | 108 |
| P11 | 02091963 | 45 | 59 | `111011` | 30 | 19 | 11 | 18 |
| P12 | 12081965 | 14 | 45 | `101101` | 32 | 21 | 20 | 96 |
| P13 | 16051978 | 34 | 10 | `001010` | 37 | 25 | 21 | 80 |
| P14 | 22091978 | 2 | 10 | `001010` | 38 | 25 | 31 | 198 |
| P15 | 04061982 | 36 | 30 | `011110` | 30 | 20 | 10 | 24 |
| P16 | 05091984 | 42 | 16 | `010000` | 36 | 22 | 14 | 45 |
| P17 | 16061986 | 46 | 34 | `100010` | 37 | 24 | 22 | 96 |
| P18 | 03121989 | 24 | 5 | `000101` | 33 | 27 | 15 | 36 |
| P19 | 25021998 | 21 | 46 | `101110` | 36 | 27 | 27 | 50 |
| P20 | 10102011 | 33 | 59 | `111011` | 6 | 4 | 20 | 100 |
| P21 | 06092016 | 15 | 48 | `110000` | 24 | 9 | 15 | 54 |
| P22 | 29052022 | 25 | 54 | `110110` | 22 | 6 | 34 | 145 |
| P23 | 24082024 | 28 | 40 | `101000` | 22 | 8 | 32 | 192 |
| P24 | 21101970 | 6 | 18 | `010010` | 21 | 17 | 31 | 210 |

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

### Rechenprobe P24

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
| 21 | P08, P19 |
| 25 | P05, P22 |
| 28 | P06, P23 |

### mod 64

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 10 | P13, P14 |
| 39 | P01, Ereignis 13082023, Ereignis 15082023 |
| 45 | P02, P12 |
| 48 | P21, Ereignis 20041968 |
| 59 | P11, P20 |

### Ziffernsumme

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 21 | P24, Ereignis 15082023 |
| 22 | P22, P23 |
| 25 | P04, P05, P06 |
| 30 | P11, P15, Ereignis 20041968 |
| 36 | P16, P19 |
| 37 | P13, P17 |

### Jahres-QS

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 7 | Ereignis 13082023, Ereignis 15082023 |
| 17 | P03, P10, P24 |
| 20 | P07, P08, P15 |
| 22 | P01, P16 |
| 24 | P17, Ereignis 20041968 |
| 25 | P13, P14 |
| 27 | P18, P19 |

### Tag+Monat

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 14 | P04, P16 |
| 15 | P18, P21 |
| 20 | P12, P20 |
| 21 | P01, P10, P13, Ereignis 13082023 |
| 31 | P14, P24 |

### Tag×Monat

| Wert | Datensätze mit demselben Ergebnis |
|---:|---|
| 18 | P09, P11 |
| 45 | P04, P16 |
| 54 | P01, P21 |
| 80 | P02, P13, Ereignis 20041968 |
| 96 | P12, P17 |

### Vergleich des eigenständigen Referenzwerts AR mit den Datumsrechnungen

AR ergibt bei mod 51 den Rest `24`, ebenso P18. Bei mod 64 ergibt AR `55`, bei der Ziffernsumme `12`; dafür gibt es in den 27 Datumswerten keine Gleichheit. AR bleibt dabei ein vierstelliger Referenzwert, kein Familien- oder Ereignisdatum. Die Zerlegung `19 + 11 = 30` und die Jahresdifferenz `115` sind andere Operationen und werden nicht als identische Methoden-Treffer gezählt.

P24 erzeugt keinen gleichen mod-51- oder mod-64-Rest und keinen gleichen Tag×Monat-Wert innerhalb des aktuellen Datensatzes. Seine Ziffernsumme `21` stimmt mit Ereignis `15082023`, seine Jahres-QS `17` mit P03 und P10, und Tag+Monat `31` mit P14 überein. Diese Gleichheiten sind rechnerische Beobachtungen, keine Belege für einen realen Zusammenhang.

**Berechnungsstand:** Version 1.1 · 24 + 3 Datumswerte und AR geprüft.


---

## Version 1.2 – vollständige Neuberechnung mit P25 (29.09.2026)

Es wurden alle 25 Personeneinträge und alle drei getrennten Ereignis-/Paardaten mit den unveränderten Methoden der `METHODIK.md` gerechnet. Die 24 verschiedenen Familiendatumswerte wurden jeweils geprüft; P02 und P25 sind zwei Personen mit derselben Datumszahl. Alle bereits in Version 1.1 dokumentierten 24 Personenzeilen und drei Ereigniszeilen wurden rechnerisch erneut überprüft und stimmen überein.

### Familiendaten: alle 25 Personen

| Kennung | Zahlenfolge | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---:|---:|---:|---|---:|---:|---:|---:|
| P01 | 18031975 | 7 | 39 | `100111` | 34 | 22 | 21 | 54 |
| P02 | 08101997 | 35 | 45 | `101101` | 35 | 26 | 18 | 80 |
| P03 | 02041907 | 20 | 51 | `110011` | 23 | 17 | 6 | 8 |
| P04 | 09051910 | 22 | 6 | `000110` | 25 | 11 | 14 | 45 |
| P05 | 05081920 | 25 | 0 | `000000` | 25 | 12 | 13 | 40 |
| P06 | 19111921 | 28 | 49 | `110001` | 25 | 13 | 30 | 209 |
| P07 | 23031937 | 31 | 1 | `000001` | 28 | 20 | 26 | 69 |
| P08 | 12041937 | 21 | 17 | `010001` | 27 | 20 | 16 | 48 |
| P09 | 18011942 | 17 | 38 | `100110` | 26 | 16 | 19 | 18 |
| P10 | 09121952 | 41 | 32 | `100000` | 29 | 17 | 21 | 108 |
| P11 | 02091963 | 45 | 59 | `111011` | 30 | 19 | 11 | 18 |
| P12 | 12081965 | 14 | 45 | `101101` | 32 | 21 | 20 | 96 |
| P13 | 16051978 | 34 | 10 | `001010` | 37 | 25 | 21 | 80 |
| P14 | 22091978 | 2 | 10 | `001010` | 38 | 25 | 31 | 198 |
| P15 | 04061982 | 36 | 30 | `011110` | 30 | 20 | 10 | 24 |
| P16 | 05091984 | 42 | 16 | `010000` | 36 | 22 | 14 | 45 |
| P17 | 16061986 | 46 | 34 | `100010` | 37 | 24 | 22 | 96 |
| P18 | 03121989 | 24 | 5 | `000101` | 33 | 27 | 15 | 36 |
| P19 | 25021998 | 21 | 46 | `101110` | 36 | 27 | 27 | 50 |
| P20 | 10102011 | 33 | 59 | `111011` | 6 | 4 | 20 | 100 |
| P21 | 06092016 | 15 | 48 | `110000` | 24 | 9 | 15 | 54 |
| P22 | 29052022 | 25 | 54 | `110110` | 22 | 6 | 34 | 145 |
| P23 | 24082024 | 28 | 40 | `101000` | 22 | 8 | 32 | 192 |
| P24 | 21101970 | 6 | 18 | `010010` | 21 | 17 | 31 | 210 |
| P25 | 08101997 | 35 | 45 | `101101` | 35 | 26 | 18 | 80 |

### Ereignis- und Paardaten: alle drei Werte

| Kennung | Zahlenfolge | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---:|---:|---:|---|---:|---:|---:|---:|
| Ereignis 20041968 | 20041968 | 39 | 48 | `110000` | 30 | 24 | 24 | 80 |
| Ereignis 13082023 | 13082023 | 13 | 39 | `100111` | 19 | 7 | 21 | 104 |
| Ereignis 15082023 | 15082023 | 48 | 39 | `100111` | 21 | 7 | 23 | 120 |

### Referenzwert AR (separat, kein Datum)

- `1911 mod 51 = 24` (`1911 = 37 × 51 + 24`), gleich P18 bei derselben Methode.
- `1911 mod 64 = 55` (`1911 = 29 × 64 + 55`); sechs Bit: `110111`.
- Ziffernsumme: `1 + 9 + 1 + 1 = 12`; gesonderte Zerlegung: `19 + 11 = 30`.
- Zeitbezogene Differenz: `2026 - 1911 = 115`. AR ist kein Datum; Jahres-QS, Tag+Monat und Tag×Monat werden nicht auf AR angewendet.

### Rechenprobe P25 = P02 (08.10.1997)

- `08101997` als Ganzzahl `8101997 = 158862 × 51 + 35` → mod 51 `35`.
- `8101997 = 126593 × 64 + 45` → mod 64 `45` → `101101`.
- Ziffernsumme: `0+8+1+0+1+9+9+7 = 35`; Jahres-QS: `1+9+9+7 = 26`.
- Tag+Monat: `8+10 = 18`; Tag×Monat: `8×10 = 80`.

### Sämtliche Wiederholungsgruppen (25 Personen + 3 Ereignisse)

Die Tabellen enthalten je Methode alle Ergebniswerte, die mindestens zweimal vorkommen. Derselbe Zahlenwert für P02 und P25 ist erwartbar, weil beide dasselbe vollständige Datum haben. Die sechs Bit kodieren den mod-64-Wert lediglich erneut.

#### mod 51

| Wert | Gleiche Datensätze |
|---:|---|
| 21 | P08, P19 |
| 25 | P05, P22 |
| 28 | P06, P23 |
| 35 | P02, P25 |

#### mod 64 / sechs Bit

| Wert | Gleiche Datensätze |
|---:|---|
| 10 | P13, P14 |
| 39 | P01, Ereignis 13082023, Ereignis 15082023 |
| 45 | P02, P12, P25 |
| 48 | P21, Ereignis 20041968 |
| 59 | P11, P20 |

#### Ziffernsumme

| Wert | Gleiche Datensätze |
|---:|---|
| 21 | P24, Ereignis 15082023 |
| 22 | P22, P23 |
| 25 | P04, P05, P06 |
| 30 | P11, P15, Ereignis 20041968 |
| 35 | P02, P25 |
| 36 | P16, P19 |
| 37 | P13, P17 |

#### Jahresziffernsumme

| Wert | Gleiche Datensätze |
|---:|---|
| 7 | Ereignis 13082023, Ereignis 15082023 |
| 17 | P03, P10, P24 |
| 20 | P07, P08, P15 |
| 22 | P01, P16 |
| 24 | P17, Ereignis 20041968 |
| 25 | P13, P14 |
| 26 | P02, P25 |
| 27 | P18, P19 |

#### Tag+Monat

| Wert | Gleiche Datensätze |
|---:|---|
| 14 | P04, P16 |
| 15 | P18, P21 |
| 18 | P02, P25 |
| 20 | P12, P20 |
| 21 | P01, P10, P13, Ereignis 13082023 |
| 31 | P14, P24 |

#### Tag×Monat

| Wert | Gleiche Datensätze |
|---:|---|
| 18 | P09, P11 |
| 45 | P04, P16 |
| 54 | P01, P21 |
| 80 | P02, P13, P25, Ereignis 20041968 |
| 96 | P12, P17 |

**Berechnungsstand:** Version 1.2 · 25 Personen, drei Ereigniswerte und AR getrennt geprüft. Die Familienordnung ist noch nicht endgültig nummeriert.
