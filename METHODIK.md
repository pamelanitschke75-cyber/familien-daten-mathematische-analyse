# Methodik

## Version 1.0

Diese Datei definiert die mathematischen Verfahren der Untersuchung.

Ziel ist, jede Berechnung eindeutig und reproduzierbar zu machen. Ausgangspunkt sind ausschließlich die in `DATEN.md` dokumentierten Werte.

## 1. Darstellung eines Datums

Ein vollständiges Datum wird für bestimmte Berechnungen als achtstellige Zahlenfolge im Format

`TTMMJJJJ`

verwendet.

Beispiel:

`18.03.1975 → 18031975`

Führende Nullen gehören zur Darstellung des Datums.

Für die Umwandlung in eine ganze Zahl haben führende Nullen keinen Einfluss auf den Zahlenwert.

---

## 2. Modulo – allgemeine Definition

`n mod m` bezeichnet den Rest, der bei der ganzzahligen Division von `n` durch `m` übrig bleibt.

Allgemein:

`n = q × m + r`

Dabei gilt:

- `n` = Ausgangszahl
- `m` = Modul
- `q` = ganzzahliger Quotient
- `r` = Rest
- `0 ≤ r < m`

Der Wert von `n mod m` ist `r`.

Modulo-Arithmetik ist ein standardisiertes mathematisches Verfahren.

---

## 3. Modulo 51

Bei dieser Untersuchung wird die vollständige Datumszahl `n` durch 51 geteilt und der Rest bestimmt.

Formel:

`n mod 51`

Das Ergebnis liegt immer zwischen:

`0` und `50`

Beispielverfahren:

1. Datum in `TTMMJJJJ` schreiben.
2. Diese Folge als ganze Zahl `n` verwenden.
3. `n` durch 51 teilen.
4. Nur den ganzzahligen Rest notieren.

Wichtig:

Die mathematische Operation Modulo ist allgemein definiert.

Die Verwendung des speziellen Moduls `51` für diesen Datensatz ist eine festgelegte Untersuchungsmethode dieses Projekts. Daraus folgt für sich allein noch keine besondere Bedeutung der Zahl 51.

---

## 4. Modulo 64

Analog wird berechnet:

`n mod 64`

Das Ergebnis liegt immer zwischen:

`0` und `63`.

Die Verwendung von 64 erlaubt außerdem die eindeutige Darstellung jedes möglichen Ergebnisses mit sechs Binärstellen.

---

## 5. 6-Bit-Darstellung

Ein Ergebnis von `n mod 64` wird zusätzlich als sechsstellige Binärzahl dargestellt.

Beispiele:

`0  → 000000`

`1  → 000001`

`51 → 110011`

`63 → 111111`

Die Binärdarstellung verändert den mathematischen Wert nicht. Sie stellt denselben Wert lediglich in einem anderen Zahlensystem dar.

---

## 6. Ziffernsumme des vollständigen Datums

Alle Ziffern der achtstelligen Datumsdarstellung werden addiert.

Beispiel:

`18.03.1975`

wird zu:

`1 + 8 + 0 + 3 + 1 + 9 + 7 + 5`

Das Ergebnis ist die Ziffernsumme.

Führende oder innerhalb des Datums vorkommende Nullen werden als Ziffer `0` berücksichtigt.

---

## 7. Jahresziffernsumme

Hier werden ausschließlich die vier Ziffern des Jahres addiert.

Beispiel:

`1975`

ergibt:

`1 + 9 + 7 + 5 = 22`

Diese Berechnung wird getrennt von der Ziffernsumme des vollständigen Datums dokumentiert.

---

## 8. Tag plus Monat

Tag und Monat werden als Zahlen addiert.

Formel:

`Tag + Monat`

Beispiel für `18.03.1975`:

`18 + 3 = 21`

Das Jahr spielt bei dieser Berechnung keine Rolle.

---

## 9. Tag mal Monat

Tag und Monat werden multipliziert.

Formel:

`Tag × Monat`

Beispiel für `18.03.1975`:

`18 × 3 = 54`

Auch hierbei wird das Jahr nicht einbezogen.

---

## 10. Differenzen

Differenzen dürfen nur zwischen bereits vorhandenen und eindeutig bezeichneten Werten berechnet werden.

Allgemein:

`A - B`

oder, wenn ausschließlich der Abstand untersucht wird:

`|A - B|`

In `BERECHNUNGEN.md` muss jeweils angegeben werden:

- welche beiden Werte verwendet wurden,
- in welcher Reihenfolge gerechnet wurde,
- ob eine gerichtete Differenz oder der absolute Abstand gemeint ist.

Es werden keine zusätzlichen Ausgangswerte eingeführt, nur um eine gewünschte Differenz zu erhalten.

---

## 11. Referenzwerte

Ein Wert, der in `DATEN.md` ausdrücklich als Referenzwert geführt wird, darf mathematisch untersucht werden.

Beispiel:

`1911 | AR`

Da `1911` nicht als vollständiges Datum dokumentiert ist, wird dieser Wert nicht nachträglich als achtstelliges Datum behandelt.

Berechnungen mit diesem Wert müssen ausdrücklich als Berechnungen mit dem Referenzwert `1911` gekennzeichnet werden.

---

## 12. Koordinaten

Ein mathematisch berechneter Wert wird nicht allein aufgrund seiner Größe automatisch zu einer geografischen Koordinate.

Falls untersucht wird, ob ein Ergebnis mit einem Breiten- oder Längengrad übereinstimmt, wird diese Untersuchung getrennt in `KOORDINATEN.md` dokumentiert.

Dabei werden unterschieden:

1. vorhandener Ausgangswert,
2. verwendete mathematische Operation,
3. berechnetes Ergebnis,
4. möglicher geografischer Vergleich,
5. Interpretation oder Hypothese.

Eine numerische Übereinstimmung allein gilt nicht als Nachweis eines geografischen Zusammenhangs.

---

## 13. Trennung von Berechnung und Interpretation

Für sämtliche Methoden gilt:

**Berechnung:**  
Was ergibt sich mathematisch aus den festgelegten Ausgangswerten?

**Beobachtung:**  
Welche Übereinstimmungen oder wiederkehrenden Ergebnisse treten tatsächlich auf?

**Hypothese:**  
Welche mögliche Bedeutung könnte anschließend untersucht werden?

Diese drei Ebenen werden in der Dokumentation getrennt gehalten.

---

## 14. Keine nachträgliche Anpassung

Eine mathematische Methode wird nicht nachträglich verändert, nur weil ein anderes Verfahren ein interessanteres Ergebnis erzeugen würde.

Zusätzliche Untersuchungsmethoden dürfen getestet werden, müssen jedoch ausdrücklich als zusätzliche Methode dokumentiert werden.

Die ursprünglichen Ergebnisse bleiben erhalten.

---

## 15. Reproduzierbarkeit

Jede veröffentlichte Berechnung soll mindestens enthalten:

- Ausgangswert
- verwendete Methode
- Rechenoperation
- Ergebnis

Damit kann eine andere Person oder ein unabhängiges Rechenprogramm dasselbe Ergebnis überprüfen.

---

## Status

**Methodik-Version:** 1.0  
**Ausgangsdaten:** `DATEN.md`  
**Berechnungen:** `BERECHNUNGEN.md`  
**Koordinatenprüfung:** `KOORDINATEN.md`  
**Interpretationen:** `HYPOTHESEN.md`

---

Diese Methodik bildet die festgelegte mathematische Grundlage der Version 1.0.