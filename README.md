# Familien-Daten – Mathematische Analyse

## Version 1.2.1 – Personenkennungen P01–P25

Dieses derzeit öffentliche Repository dokumentiert die mathematische Untersuchung einer festgelegten Sammlung von Familiendaten und ergänzenden Referenzwerten.

Ziel des Projekts ist es, Ausgangsdaten, mathematische Verfahren, Berechnungen, Ergebnisse und weiterführende Hypothesen so zu dokumentieren, dass der gesamte Untersuchungsweg nachvollziehbar und reproduzierbar bleibt.

## KI-Unterstützung

Bei der Aufbereitung und Dokumentation dieses Projekts wird ChatGPT von OpenAI als KI-Werkzeug eingesetzt.

Die KI-Unterstützung umfasst insbesondere:

- Erklärung mathematischer Verfahren
- Durchführung und Überprüfung von Berechnungen
- Strukturierung der Datensätze
- Erstellung und Überarbeitung der Projektdokumentation
- Suche nach rechnerischen Übereinstimmungen und Mustern
- Unterstützung bei der Entwicklung reproduzierbarer Prüfverfahren
- sprachlich verständliche Darstellung der Ergebnisse

Die Verwendung von ChatGPT bedeutet nicht, dass OpenAI dieses Projekt offiziell unterstützt, daran beteiligt ist oder die darin beschriebenen Hypothesen und Schlussfolgerungen bestätigt.

KI-generierte Berechnungen und Texte können Fehler enthalten. Entscheidende Berechnungen sollen deshalb reproduzierbar dokumentiert und überprüft werden.

## Aktueller Datenstand

`DATEN.md` enthält 25 Personen (P01–P25) mit 24 verschiedenen Familiendatumswerten, drei getrennte Ereignis-/Paardaten und den Referenzwert AR. Die aktuelle vollständige Neuberechnung steht in `BERECHNUNGEN.md`, die Neubewertung in `ERGEBNISSE.md` (jeweils Version 1.2 am Ende). Die Methoden der Version 1.0 und alle Rechenwerte der Version 1.2 gelten unverändert. Die redaktionell vereinheitlichten Kennungen heißen nun P01–P25; die frühere N-Bezeichnung ist im `CHANGELOG.md` zugeordnet. Frühere Versionen 1.0 und 1.1 bleiben als historische Vergleiche erhalten.

P02 und P25 sind Zwillinge mit demselben Datum. Die daraus folgenden gleichen Werte sind keine unabhängigen Datumsbeobachtungen. Die P-Kennungen sind vorläufige Arbeitskennungen; die spätere Ordnung folgt den Familienbeziehungen, nicht den Geburtstagen. Steffi soll in dieser Ordnung neben Pam und neben ihrem Zwillingsbruder stehen. Weitere Beziehungen werden erst nach Klärung zugeordnet; die Liste bleibt über P25 hinaus erweiterbar. Daraus folgt keine bestätigte geografische oder sachliche Verbindung.

## Grundsätze der Untersuchung

Für dieses Projekt gelten folgende Regeln:

1. Die festgelegten Ausgangsdaten werden nicht verändert, um ein gewünschtes Ergebnis zu erzeugen.
2. Es werden keine zusätzlichen Zahlen, Codes, Daten oder Koordinaten erfunden, um ein Ergebnis passend zu machen.
3. Sollte sich ein ursprünglich falsch notiertes Datum herausstellen, darf es sachlich korrigiert werden.
4. Jede solche Korrektur wird im Änderungsprotokoll dokumentiert.
5. Mathematische Ergebnisse und deren Interpretation werden voneinander getrennt.
6. Jeder verwendete Rechenweg wird so beschrieben, dass er unabhängig nachgerechnet werden kann.
7. Ergebnisse, die einer Hypothese nicht entsprechen, werden nicht entfernt.
8. Neue Untersuchungsmethoden werden als neue Methoden gekennzeichnet und nicht rückwirkend als ursprüngliche Regeln dargestellt.

## Mathematische Verfahren

Zu den untersuchten Verfahren gehören:

- Modulo 51 (`n mod 51`)
- Modulo 64 (`n mod 64`)
- 6-Bit-Darstellung der Modulo-64-Ergebnisse
- Ziffernsummen
- Jahresziffernsummen
- Tag + Monat
- Tag × Monat
- eindeutig definierte Differenzen zwischen vorhandenen Referenzwerten

Modulo-Arithmetik und die verwendeten Grundrechenarten sind etablierte mathematische Verfahren.

Die Entscheidung, diese Verfahren auf die vorliegenden Datums- und Referenzwerte anzuwenden, gehört zur Methodik dieses Projekts.

## Trennung von Ergebnis und Hypothese

Eine mathematisch korrekte Übereinstimmung ist zunächst ausschließlich ein rechnerisches Ergebnis.

Eine darüber hinausgehende Bedeutung – beispielsweise eine Verbindung zu einem geografischen Ort, einer Koordinate, einem Ereignis oder einem Gegenstand – wird getrennt als Hypothese behandelt.

Numerische Übereinstimmungen werden als Beobachtungen dokumentiert. Ob sie die Hypothese stützen und welche Bedeutung sie besitzen, wird anhand weiterer unabhängig überprüfbarer Hinweise untersucht.

## Projektstruktur

Die Dokumentation wird in folgende Dateien gegliedert:

- `README.md` – Einführung, Regeln und Projektübersicht
- `DATEN.md` – festgelegte Ausgangsdaten und Kürzel
- `METHODIK.md` – genaue Definition der Rechenverfahren
- `BERECHNUNGEN.md` – reproduzierbare Berechnungen
- `ERGEBNISSE.md` – mathematisch festgestellte Ergebnisse und Übereinstimmungen
- `KOORDINATEN.md` – gesonderte Untersuchung möglicher Koordinatenbezüge
- `HYPOTHESEN.MD` – Interpretationen und noch zu prüfende Annahmen
- `CHANGELOG.md` – Änderungen und dokumentierte Datenkorrekturen
- `RECHTE.md` – Hinweise zur Nutzung der privaten Daten und Dokumentation

## Datenschutz und Nutzung

Die zugrunde liegenden Daten stammen aus einem privaten familiären Zusammenhang.

Die GitHub-Sichtbarkeit dieses Repositorys ist am 29.09.2026 **öffentlich**. Die frühere Kennzeichnung als „privat“ war falsch. Für familiäre Angaben ist zu entscheiden, ob diese Sichtbarkeit beabsichtigt ist; neutrale Kennungen allein garantieren keine Anonymität.

Öffentliche Sichtbarkeit ist keine Open-Source-Lizenz. Eine Lizenz oder weitergehende Freigabe wurde nicht erteilt.

## Status

**Version:** 1.2.1 (Kennungen; Berechnung 1.2)  
**Status:** Aktuelle Neuberechnung vollständig dokumentiert; Familienordnung noch offen; Hypothesen offen  
**Ausgangsdaten:** 25 Personen (24 verschiedene Familiendaten), 3 Ereignisdaten und AR  
**KI-Unterstützung:** ChatGPT von OpenAI  
**Repository:** öffentlich (GitHub-Metadaten vom 29.09.2026)

---

Version 1.0 bleibt als historische Ausgangsbasis nachvollziehbar; Version 1.1 ergänzt P24. Version 1.2 ergänzt P25 als zweite Person mit Steffis Datum und berechnet den aktuellen Bestand neu.