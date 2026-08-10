# Berechnungen

## Version 1.0

Diese Datei enthält die reproduzierbaren Berechnungen auf Grundlage von `DATEN.md` und `METHODIK.md`.

Alle Werte wurden mit den aktuell festgelegten Ausgangsdaten neu berechnet.

## Familiendaten

| Zahlenfolge | Kürzel | mod 51 | mod 64 | 6 Bit | Ziffernsumme | Jahres-QS | Tag+Monat | Tag×Monat |
|---|---|---:|---:|---|---:|---:|---:|---:|
| 02041907 | EN | 20 | 51 | 110011 | 23 | 17 | 6 | 8 |
| 09051910 | EN | 22 | 6 | 000110 | 25 | 11 | 14 | 45 |
| 05081920 | RW | 25 | 0 | 000000 | 25 | 12 | 13 | 40 |
| 19111921 | GW | 28 | 49 | 110001 | 25 | 13 | 30 | 209 |
| 23031937 | KH | 31 | 1 | 000001 | 28 | 20 | 26 | 69 |
| 12041937 | WH | 21 | 17 | 010001 | 27 | 20 | 16 | 48 |
| 18011942 | WPN | 17 | 38 | 100110 | 26 | 16 | 19 | 18 |
| 09121952 | BMN | 41 | 32 | 100000 | 29 | 17 | 21 | 108 |
| 02091963 | KRH | 45 | 59 | 111011 | 30 | 19 | 11 | 18 |
| 12081965 | GWKK | 14 | 45 | 101101 | 32 | 21 | 20 | 96 |
| 18031975 | PCN | 7 | 39 | 100111 | 34 | 22 | 21 | 54 |
| 16051978 | FS | 34 | 10 | 001010 | 37 | 25 | 21 | 80 |
| 22091978 | SBH | 2 | 10 | 001010 | 38 | 25 | 31 | 198 |
| 04061982 | VV | 36 | 30 | 011110 | 30 | 20 | 10 | 24 |
| 05091984 | SS | 42 | 16 | 010000 | 36 | 22 | 14 | 45 |
| 16061986 | ES | 46 | 34 | 100010 | 37 | 24 | 22 | 96 |
| 03121989 | SBM | 24 | 5 | 000101 | 33 | 27 | 15 | 36 |
| 08101997 | SRH | 35 | 45 | 101101 | 35 | 26 | 18 | 80 |
| 25021998 | DVS | 21 | 46 | 101110 | 36 | 27 | 27 | 50 |
| 10102011 | MLH | 33 | 59 | 111011 | 6 | 4 | 20 | 100 |
| 06092016 | KS | 15 | 48 | 110000 | 24 | 9 | 15 | 54 |
| 29052022 | NH | 25 | 54 | 110110 | 22 | 6 | 34 | 145 |
| 24082024 | MH | 28 | 40 | 101000 | 22 | 8 | 32 | 192 |

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

- `02041907 | EN → 51`
- `12081965 | GWKK → 45`
- `08101997 | SRH → 45`
- `02091963 | KRH → 59`
- `10102011 | MLH → 59`
- `16051978 | FS → 10`
- `22091978 | SBH → 10`
- `18031975 | PCN → 39`
- `13082023 → 39`
- `15082023 → 39`

### mod 51

- Wert `22`: `09051910 | EN`
- Wert `25`: `05081920 | RW` und `29052022 | NH`
- Wert `28`: `19111921 | GW` und `24082024 | MH`
- Wert `21`: `12041937 | WH` und `25021998 | DVS`

### Weitere direkte Wiederholungen

- Ziffernsumme `37`: `16051978 | FS` und `16061986 | ES`
- Jahresziffernsumme `20`: `23031937 | KH`, `12041937 | WH`, `04061982 | VV`
- Tag×Monat `80`: `16051978 | FS`, `08101997 | SRH`, `20041968`

## Hinweis

Diese Datei enthält ausschließlich mathematische Berechnungen und direkt beobachtbare Wiederholungen.

Eine Interpretation dieser Ergebnisse wird getrennt dokumentiert.

---

**Berechnungsstand:** Version 1.0  
**Grundlage:** `DATEN.md`  
**Methodik:** `METHODIK.md`