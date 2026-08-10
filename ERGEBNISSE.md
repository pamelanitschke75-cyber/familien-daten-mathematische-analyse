# Ergebnisse

## Version 1.0

Diese Datei fasst die Ergebnisse der mathematischen Untersuchung zusammen.

Grundlage sind ausschließlich die in `DATEN.md` festgelegten Ausgangsdaten und die in `METHODIK.md` definierten Rechenverfahren.

Die vollständigen Einzelberechnungen befinden sich in `BERECHNUNGEN.md`.

---

## 1. Grundsatz

In dieser Datei wird zwischen drei Ebenen unterschieden:

1. **Berechnetes Ergebnis** – mathematisch reproduzierbar.
2. **Beobachtete Übereinstimmung** – gleiche oder auffällige Werte innerhalb des Datensatzes.
3. **Interpretation/Hypothese** – eine mögliche Bedeutung, die gesondert geprüft werden muss.

Eine numerische Übereinstimmung wird nicht automatisch als Beweis für einen sachlichen Zusammenhang gewertet.

---

## 2. Ergebnisse Modulo 51

Bei Anwendung von `n mod 51` auf die festgelegten Datumszahlen entstehen verschiedene Restwerte.

Mehrfach auftretende Ergebnisse sind unter anderem:

- `25`: RW (`05081920`) und NH (`29052022`)
- `28`: GW (`19111921`) und MH (`24082024`)
- `21`: WH (`12041937`) und DVS (`25021998`)

Weitere für die Untersuchung dokumentierte Werte sind beispielsweise:

- EN (`09051910`) → `22`
- KH (`23031937`) → `31`
- GWKK (`12081965`) → `14`
- PCN (`18031975`) → `7`
- Ereignisdatum `15082023` → `48`

Diese Werte sind zunächst ausschließlich Ergebnisse der festgelegten Modulo-51-Berechnung.

---

## 3. Ergebnisse Modulo 64

Bei `n mod 64` treten ebenfalls Wiederholungen auf.

Dokumentierte Beispiele:

- GWKK (`12081965`) → `45`
- SRH (`08101997`) → `45`

- KRH (`02091963`) → `59`
- MLH (`10102011`) → `59`

- FS (`16051978`) → `10`
- SBH (`22091978`) → `10`

- PCN (`18031975`) → `39`
- Ereignisdatum `13082023` → `39`
- Ereignisdatum `15082023` → `39`

Weitere dokumentierte Ergebnisse:

- EN (`02041907`) → `51`
- GW (`19111921`) → `49`
- KH (`23031937`) → `1`
- WH (`12041937`) → `17`
- KS (`06092016`) → `48`
- Ereignisdatum `20041968` → `48`

---

## 4. Ergebnisse der Ziffernsummen

Auch bei den Ziffernsummen treten gleiche Werte bei unterschiedlichen Ausgangsdaten auf.

Beispiele:

- FS (`16051978`) → Ziffernsumme `37`
- ES (`16061986`) → Ziffernsumme `37`

Weitere Werte werden vollständig in `BERECHNUNGEN.md` geführt.

---

## 5. Ergebnisse der Jahresziffernsummen

Für die Jahreszahl `1937` gilt:

`1 + 9 + 3 + 7 = 20`

Daher besitzen sowohl

- KH (`23.03.1937`)
- WH (`12.04.1937`)

die Jahresziffernsumme `20`.

Weitere dokumentierte Übereinstimmung:

- VV (`04.06.1982`) → Jahresziffernsumme `20`

---

## 6. Ergebnisse aus Tag und Monat

Die getrennte Untersuchung von Tag und Monat liefert weitere Werte.

Beispiele:

### Tag + Monat

KH:

`23 + 3 = 26`

EN (`09.05.1910`):

`9 + 5 = 14`

SS (`05.09.1984`):

`5 + 9 = 14`

### Tag × Monat

WH:

`12 × 4 = 48`

FS:

`16 × 5 = 80`

SRH:

`8 × 10 = 80`

Ereignisdatum `20.04.1968`:

`20 × 4 = 80`

---

## 7. Referenzwert 1911 | AR

Der in `DATEN.md` separat dokumentierte Referenzwert lautet:

`1911 | AR`

Daraus ergeben sich unter anderem:

`1911 mod 51 = 24`

`1911 mod 64 = 55`

Ziffernsumme:

`1 + 9 + 1 + 1 = 12`

Zusätzlich ist in `BERECHNUNGEN.md` die Differenz

`2026 - 1911 = 115`

dokumentiert.

Die Rechnung selbst ist eindeutig.

Ob die daraus entstehende Zahl `115` eine weitergehende Bedeutung besitzt, ist eine getrennte Hypothese und wird nicht durch die Differenzrechnung allein bewiesen.

---

## 8. Vergleich mit Area-51-Koordinaten

Im Rahmen der Untersuchung wird separat geprüft, ob berechnete Werte Bestandteilen einer geografischen Positionsangabe für Area 51 entsprechen.

Innerhalb der bereits definierten Berechnungen treten unter anderem die Zahlen

`37`, `14`, `26`, `49`, `7`, `48`, `30` und `51`

auf.

Einige davon können Bestandteilen gebräuchlicher Koordinatendarstellungen des Gebiets gegenübergestellt werden.

Dieser Vergleich wird jedoch ausdrücklich von der eigentlichen Berechnung getrennt.

Insbesondere gilt:

**Das Auftreten einzelner passender Zahlen beweist nicht, dass die Familiendaten geografische Koordinaten codieren.**

Eine vollständige geografische Untersuchung wird deshalb getrennt in `KOORDINATEN.md` dokumentiert.

---

## 9. Der Wert 115 und der historische Brief

Es besteht ein offener Prüfpunkt, ob ein historischer Brief unabhängig von der Rechnung

`2026 - 1911 = 115`

einen nachvollziehbaren Bezug zur Zahl `115` enthält.

Solange der Brief dies nicht unabhängig bestätigt, wird dieser Zusammenhang nicht als Ergebnis gewertet.

Der Prüfpunkt wird in `HYPOTHESEN.md` geführt.

---

## 10. Zwischenfazit Version 1.0

Die Untersuchung zeigt reproduzierbare mathematische Ergebnisse und mehrere Wiederholungen innerhalb des festgelegten Datensatzes.

Festgestellt werden kann:

- Mehrere unterschiedliche Ausgangsdaten erzeugen identische Modulo-Ergebnisse.
- Bestimmte Ziffernsummen und Tag-Monat-Ergebnisse wiederholen sich.
- Mehrere Zahlen, die bei einem Vergleich mit geografischen Koordinaten interessant erscheinen, entstehen tatsächlich durch die vorher festgelegten Rechenmethoden.
- Der Referenzwert `1911 | AR` liefert mit dem Bezugsjahr 2026 die Differenz `115`.

Nicht festgestellt ist bislang:


- dass die Wiederholungen statistisch außergewöhnlich sind,
- dass eine einzige festgelegte Rechenregel aus den Ausgangsdaten eine vollständige Area-51-Koordinate erzeugt,
- oder dass der historische Brief unabhängig die Zahl `115` bestätigt.



---

## Dokumentationsstand

**Version:** 1.0  
**Ausgangsdaten:** `DATEN.md`  
**Methodik:** `METHODIK.md`  
**Einzelberechnungen:** `BERECHNUNGEN.md`  
**Geografische Prüfung:** `KOORDINATEN.md`  
**Offene Interpretationen:** `HYPOTHESEN.md`