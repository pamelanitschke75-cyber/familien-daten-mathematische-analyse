# Änderungsprotokoll

Dieses Dokument protokolliert Änderungen und Korrekturen an der dokumentierten Untersuchung.

Ziel ist, Änderungen nachvollziehbar zu machen, ohne frühere Angaben stillschweigend zu überschreiben.

---

## Version 1.0

### Ausgangsdaten

Der Ausgangsdatensatz wurde in `DATEN.md` festgelegt.

Vor der endgültigen Festschreibung von Version 1.0 wurden zwei Datumsangaben zu Steffis Großeltern korrigiert.

### Korrektur KH

Frühere Angabe:

`10.12.1937 | 10121937 | KH`

Korrigierte Angabe:

`23.03.1937 | 23031937 | KH`

Für Version 1.0 gilt ausschließlich:

`23031937 | KH`

Alle mathematischen Berechnungen für KH wurden auf Grundlage des korrigierten Datums neu durchgeführt.

### Korrektur WH

Frühere Angabe:

`12.04.1938 | 12041938 | WH`

Korrigierte Angabe:

`12.04.1937 | 12041937 | WH`

Für Version 1.0 gilt ausschließlich:

`12041937 | WH`

Alle mathematischen Berechnungen für WH wurden auf Grundlage des korrigierten Datums neu durchgeführt.

---

## Methodik Version 1.0

Die mathematischen Verfahren wurden in `METHODIK.md` festgelegt.

Dokumentiert wurden unter anderem:

- Modulo 51
- Modulo 64
- 6-Bit-Darstellung
- Ziffernsumme
- Jahresziffernsumme
- Tag + Monat
- Tag × Monat
- eindeutig bezeichnete Differenzen
- getrennte Prüfung möglicher Koordinatenbezüge

---

## Berechnungen Version 1.0

Nach den Datenkorrekturen wurden die Berechnungen mit den korrigierten Ausgangsdaten neu durchgeführt.

Frühere Ergebnisse, die auf den ersetzten Datumsangaben von KH oder WH beruhten, gelten nicht als Ergebnisse der Version 1.0.

---

## Dokumentationsstruktur Version 1.0

Folgende Dokumente bilden die Referenzdokumentation:

- `README.md`
- `DATEN.md`
- `METHODIK.md`
- `BERECHNUNGEN.md`
- `ERGEBNISSE.md`
- `KOORDINATEN.md`
- `HYPOTHESEN.md`
- `CHANGELOG.md`
- `RECHTE.md`

---

## Regel für zukünftige Änderungen

Falls später eine tatsächliche Korrektur eines Ausgangsdatums erforderlich wird:

1. Die bisher dokumentierte Angabe wird hier festgehalten.
2. Die korrigierte Angabe wird eindeutig genannt.
3. Der Grund wird, soweit bekannt, kurz dokumentiert.
4. Betroffene Berechnungen werden vollständig neu durchgeführt.
5. Alte Berechnungsergebnisse werden nicht mit den neuen Ergebnissen vermischt.
6. Änderungen an der Methodik werden ebenfalls ausdrücklich dokumentiert.

---

## Status

**Dokumentationsversion:** 1.0  
**Ausgangsdaten:** festgelegt  
**Methodik:** festgelegt  
**Änderungsprotokoll:** aktiv

---

## Version 1.1 – Ergänzung und vollständige Neuberechnung (29.09.2026)

- In `DATEN.md` wurde N24 als zusätzlicher, von Pam bestätigter Familiendatensatz für die Cousine aufgenommen. Die ursprünglichen N01–N23 und alle drei Ereignisdaten bleiben unverändert.
- Alle 24 Familiendaten und drei Ereignisdaten wurden mit den bestehenden Methoden vollständig neu berechnet; die 23 bisherigen und drei Ereignis-Einzelrechnungen stimmen mit Version 1.0 überein. AR wurde getrennt erneut geprüft.
- N24 ergibt mod 51 = `6`, mod 64 = `18` (`010010`), Ziffernsumme = `21`, Jahres-QS = `17`, Tag+Monat = `31` und Tag×Monat = `210`. Die neuen Gleichheiten und sämtliche Wiederholungen stehen in `BERECHNUNGEN.md` und `ERGEBNISSE.md`.
- AR ergibt unverändert mod 51 = `24` (auch N18), mod 64 = `55`, Ziffernsumme = `12` sowie `2026 - 1911 = 115`. Ein Referenzwert bleibt von Familien- und Ereignisdaten getrennt.
- Die Koordinaten- und Hypothesenprüfung wurde auf den neuen Rechenstand bezogen; es wurde kein neuer geografischer oder sachlicher Beleg gefunden.
- Die frühere Version 1.0 und die ältere, abweichende `Codes-Projekt`-Arbeitsfassung bleiben als historische Stände erkennbar. Die Methodik wurde nicht verändert.
- Die falsche README-Angabe „privat“ wurde mit der tatsächlichen öffentlichen GitHub-Sichtbarkeit abgeglichen.

**Aktueller Dokumentationsstand:** Version 1.1; Rechnungen vollständig, unabhängige Hypothesenprüfung offen.


---

## Version 1.2 – Zwillingsbruder und offene Familienordnung (29.09.2026)

- N25 als eigene Person für Steffis Zwillingsbruder mit `08.10.1997 | 08101997` ergänzt. N02 und N25 sind zwei Personen mit identischem Datum; 25 Personen, aber 24 verschiedene Familiendatumswerte. Die Daten der Versionen 1.0 und 1.1 bleiben historisch nachvollziehbar.
- Alle 25 Personen und drei Ereignis-/Paardaten mit den bestehenden Methoden neu durchgerechnet. N25 hat dieselben Werte wie N02; alle 24 vorherigen Familienzeilen und drei Ereigniszeilen wurden gegengeprüft. AR getrennt unverändert geprüft.
- Die Wiederholungsgruppen und Interpretation der doppelten Datumszahl in `BERECHNUNGEN.md` und `ERGEBNISSE.md` aktualisiert. Die Zwillings-Doppelung zählt nicht als unabhängig beobachteter zweiter Datumswert.
- Die anfänglich vorgeschlagene Sortierung nach Geburtsdatum wurde verworfen. Eine familienbezogene Anordnung mit Steffi neben Pam und neben ihrem Zwillingsbruder ist gewünscht. Die anderen Beziehungen und eine endgültige Neuvergabe der N-Kennungen bleiben offen; bei einer späteren Umnummerierung wird die alte-neue Zuordnung hier protokolliert. N25 ist keine Obergrenze.
- Die vorhandene Methodik und der offene Status geografischer bzw. sachlicher Hypothesen bleiben erhalten.

**Aktueller Dokumentationsstand:** Version 1.2; Rechnungen vollständig, Familienordnung und unabhängige Hypothesenprüfung offen.


---

## Version 1.2.1 – Personenkennungen N → P (29.09.2026)

Die bisherige Arbeitskennung **N01–N25** wurde in den aktuellen Projektdateien indexgleich in **P01–P25** umbenannt. Die eindeutige Zuordnung lautet für jedes zweistellige `xx`: `Nxx → Pxx`, beispielsweise `N01 → P01`, `N02 → P02`, `N24 → P24` und `N25 → P25`. Frühere Git-Commits und die vorstehenden historischen Einträge behalten die ursprüngliche Bezeichnung, damit die Entwicklung nachvollziehbar bleibt. Historische Berechnungstabellen wurden nur in der Anzeige auf P-Kennungen vereinheitlicht.

Es wurden **keine** Datumswerte, Berechnungen, Gruppenzugehörigkeiten oder Personenbeziehungen geändert. P bezeichnet den Personendatensatz. Die Nummerierung ist weiterhin eine vorläufige Arbeitsfolge und noch keine endgültig sortierte Familienordnung; weitere Personen können ergänzt werden.

**Aktueller Kennungsstand:** 1.2.1 · P01–P25. **Rechenstand:** 1.2.
