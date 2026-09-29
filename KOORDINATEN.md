# Koordinatenprüfung

**Aktueller Prüfstand:** Version 1.1 (unten). Version 1.0 bleibt als historischer Stand erhalten.

## Version 1.0

Diese Datei dokumentiert die gesonderte Untersuchung möglicher geografischer Bezüge mathematisch berechneter Werte.

Grundlage sind ausschließlich die in `DATEN.md` festgelegten Ausgangswerte sowie die in `METHODIK.md` definierten Rechenverfahren.

## 1. Grundsatz

Ein mathematisch berechneter Wert wird nicht allein aufgrund seiner Größe oder Schreibweise als geografische Koordinate interpretiert.

Unterschieden werden:

1. Ausgangswert
2. mathematische Operation
3. berechnetes Ergebnis
4. geografischer Vergleich
5. mögliche Interpretation oder Hypothese

Eine numerische Übereinstimmung allein gilt nicht als Nachweis eines geografischen Zusammenhangs.

---

## 2. Dokumentationsschema

Jeder untersuchte mögliche Koordinatenbezug wird nach demselben Schema dokumentiert.

### Ausgangswert

Der verwendete Wert muss bereits in `DATEN.md` dokumentiert oder aus einem dort dokumentierten Wert nach einer in `METHODIK.md` festgelegten Methode berechnet worden sein.

### Berechnung

Der vollständige Rechenweg wird angegeben.

### Ergebnis

Das mathematische Ergebnis wird ohne geografische Interpretation dokumentiert.

### Geografischer Vergleich

Erst anschließend darf geprüft werden, ob der berechnete Wert mit einem geografischen Wert übereinstimmt oder Bestandteil einer möglichen Koordinatenangabe sein könnte.

### Bewertung

Es wird festgehalten, ob lediglich eine numerische Übereinstimmung vorliegt oder zusätzliche unabhängig überprüfbare Hinweise vorhanden sind.

---

## 3. Referenzwert AR

In `DATEN.md` ist folgender eigenständiger Referenzwert dokumentiert:

`1911 | AR`

Für das Bezugsjahr der Version 1.0 gilt:

`2026`

Daraus ergibt sich:

`2026 - 1911 = 115`

Das mathematische Ergebnis lautet damit:

`115`

Die Berechnung selbst enthält zunächst keine geografische Aussage.

Ob `115` sinnvoll mit einem geografischen Wert verglichen werden kann, wird als gesonderte Fragestellung behandelt.

Insbesondere wird durch die Berechnung allein weder festgelegt, ob `115` einen Längengrad darstellt, noch welcher Ort damit gegebenenfalls verbunden wäre.

---

## 4. Prüfung möglicher Koordinatenwerte

Für mögliche geografische Vergleiche gelten folgende Regeln:

- Koordinaten werden nicht nachträglich verändert, damit sie zu einem Ergebnis passen.
- Zahlen werden nicht ergänzt, entfernt oder umgestellt, sofern eine solche Operation nicht zuvor eindeutig als Untersuchungsmethode definiert wurde.
- Nord/Süd beziehungsweise Ost/West werden nicht allein aus einem Zahlenwert abgeleitet.
- Grad-, Minuten- und Sekundenangaben werden voneinander unterschieden.
- Dezimalgrad und Grad-Minuten-Sekunden-Darstellung werden nicht ohne dokumentierte Umrechnung vermischt.
- Ein geografischer Treffer wird nicht allein aufgrund einer ungefähren Nähe als Übereinstimmung bezeichnet.
- Vergleichsorte und verwendete Koordinatenquellen sollen nachvollziehbar dokumentiert werden.

---

## 5. Prüfstufen

Mögliche Koordinatenbezüge werden in drei Stufen eingeordnet.

### Stufe A – rechnerisches Ergebnis

Es liegt ausschließlich ein mathematisch reproduzierbarer Zahlenwert vor.

### Stufe B – numerischer geografischer Vergleich

Der Zahlenwert kann mit einem Bestandteil einer realen geografischen Koordinate verglichen werden.

Dies stellt zunächst nur eine numerische Übereinstimmung dar.

### Stufe C – unabhängig gestützter Bezug

Zusätzlich zum numerischen Vergleich existieren weitere unabhängig überprüfbare Informationen, die einen geografischen Zusammenhang begründen könnten.

Erst solche zusätzlichen Hinweise können zur weiteren Prüfung einer Hypothese herangezogen werden.

---

## 6. Abgrenzung zu Hypothesen

Diese Datei dokumentiert die mathematische und geografische Prüfung.

Weitergehende Aussagen über die mögliche Bedeutung eines Ortes gehören in `HYPOTHESEN.MD`.

Insbesondere wird aus einer Koordinatenübereinstimmung allein keine Aussage über Personen, Ereignisse, Ursachen oder Zusammenhänge abgeleitet.

---

## 7. Reproduzierbarkeit

Für jeden aufgenommenen Koordinatenvergleich sollen mindestens dokumentiert werden:

- verwendeter Ausgangswert
- verwendete Berechnung
- mathematisches Ergebnis
- verwendetes Koordinatenformat
- geografischer Vergleichswert
- Quelle des geografischen Vergleichswerts
- Ergebnis der Prüfung
- Prüfstufe

Dadurch soll eine unabhängige Person den Vergleich nachvollziehen und überprüfen können.

---

## Status

**Koordinatenprüfung:** Version 1.0  
**Ausgangsdaten:** `DATEN.md`  
**Methodik:** `METHODIK.md`  
**Berechnungen:** `BERECHNUNGEN.md`  
**Interpretationen:** `HYPOTHESEN.MD`

---

Diese Datei trennt mathematische Ergebnisse, geografische Vergleiche und weitergehende Hypothesen voneinander.

---

## Version 1.1 – Prüfung nach Ergänzung von P24

Alle 24 Familiendaten, drei Ereignis-/Paardaten und AR wurden nach den unveränderten Rechenregeln erneut ausgewertet (Einzelwerte in `BERECHNUNGEN.md`). P24 liefert mod 51 = `6`, mod 64 = `18`, Ziffernsumme = `21`, Jahres-QS = `17`, Tag+Monat = `31` und Tag×Monat = `210`. Das sind Werte der **Stufe A**, also mathematische Ergebnisse ohne geografische Zuordnung.

Der eigenständige Referenzwert AR ergibt weiterhin `2026 - 1911 = 115`. Die Ergänzung von P24 verändert diese Rechnung nicht. Für keinen neuen Wert ist in diesem Repository ein vorab bestimmter Vergleichsort mit überprüfbarer Koordinatenquelle und Format dokumentiert; ein neuer Nachweis der Stufe B oder C ergibt sich daher aus der Neuberechnung nicht. Die möglichen Bezüge zu Area 51, einer „Black Box“ oder MH370 bleiben offene Hypothesen.

**Koordinatenprüfstand:** Version 1.1 · Rechenwerte aktualisiert; externe geografische Prüfung offen.


---

## Version 1.2 – Prüfung nach Ergänzung von P25

P25 hat dieselbe Datumszahl wie P02. Die nach unveränderter Methode berechneten Werte (mod 51 = `35`, mod 64 = `45`, Ziffernsumme = `35`, Jahres-QS = `26`, Tag+Monat = `18`, Tag×Monat = `80`) sind rechnerisch geprüft, aber keine unabhängige zweite geografische Beobachtung. Die AR-Differenz `2026 - 1911 = 115` bleibt unverändert. Es liegt kein neuer vorab definierter Ort mit überprüfbarer Quelle und Koordinatenformat vor; die bisherigen offenen Prüfungen bleiben offen.

**Koordinatenprüfstand:** Version 1.2 · Stufe A für P25 geprüft; kein neuer Nachweis der Stufen B oder C.
