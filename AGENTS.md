# Projektübergreifende Arbeitsregeln

Stand: 06.10.2026. Diese Regeln ergänzen bestehende Projekt-, Schutz- und Datenschutzregeln; sie ersetzen sie nicht.

## Bestehenden Stand fortsetzen

- Vor jeder Änderung den tatsächlich vorhandenen technischen Stand und vorhandene Nachweise prüfen.
- Exakt am letzten bestätigten Stand fortsetzen. Bereits erledigte Arbeit nicht ohne sachlichen Grund neu beginnen.
- Bestehendes weiterverwenden und nur tatsächlich fehlende Teile ergänzen. Keine zweite Architektur, unnötige Parallelstruktur, Doppel-Branch, Doppel-PR oder doppelte Dokumentation.
- Eine Baustelle nach der anderen. Fachfremde Funde melden, aber nicht ungefragt als Nebenbaustelle bearbeiten.
- Bestehende Inhalte, Funktionen, Daten, Einstellungen, Schutzregeln und historische Nachweise erhalten.

## Rollen und Identitäten

- Pam = Pam, der reale Mensch.
- Frau Sol/ChatGPT = Koordinatorin.
- Worker/Codex = technische Ausführung.
- Slack = ausschließlich optionaler technischer Hinweis-/Rückmeldeweg.
- Rollen und Identitäten weder technisch noch dokumentarisch vermischen.
- Der technische Bestand ist die vorhandene Technik; „realer Bestand“ nicht als Bezeichnung für Technik verwenden.

## Verbindlicher Koordinationsweg

Soweit ein Auftrag den Pam-Holo-Koordinationsweg betrifft, bleibt der maßgebliche Weg:

**Pam → Frau Sol/ChatGPT → Worker/Codex → Frau Sol/ChatGPT → Pam**

Ein Worker-Ergebnis allein ist kein vollständiger Ende-zu-Ende-Nachweis, wenn der Auftrag ausdrücklich den vollständigen Rückweg verlangt.

## Slack bleibt optional

- Slack darf einen bestehenden Koordinationsweg ergänzen, aber niemals ersetzen.
- Ein Slack-Ausfall oder fehlender Slack-Hinweis darf einen Worker-Auftrag, dessen Ergebnis oder den bestehenden Rückweg nicht blockieren oder auf „failed“ setzen.
- Slack ist keine Person, kein Koordinator, kein Worker und keine zweite Aufgabenverwaltung.
- Eine Slack-Nachricht darf nicht stillschweigend zur neuen Befehlsquelle werden. Eine künftige autorisierte Slack-Befehlsfunktion wäre eine eigene, ausdrücklich zu entscheidende Architekturänderung.

## Task-ID und Duplikatschutz

- Grundsatz: **1 Auftrag = 1 logischer Vorgang = 1 maßgebliche Task-ID.**
- Bestehende Task-ID-, Zustands-, Retry-, Konflikt- und Idempotenzlogik weiterverwenden.
- Ein zusätzlicher Hinweis mit derselben Task-ID darf keine unbeabsichtigte zweite Worker-Ausführung oder zweite Task erzeugen.
- Technisch notwendige Teil-IDs müssen eindeutig der maßgeblichen Task-ID zugeordnet bleiben.

## Autorisierung und Datenschutz

- Authentifizierung, Berechtigungen und Schutzmechanismen niemals umgehen, nur um einen Test oder Auftrag abzuschließen.
- Fehlt ein autorisierter Anschluss, keinen Ersatzweg oder eine Ersatz-Authentifizierung bauen; den konkreten Blocker dokumentieren und den Punkt als **NOCH OFFEN ⏳** kennzeichnen.
- Keine Tokens, Passwörter, API-Schlüssel, privaten Authentifizierungsdaten, privaten Nachrichten oder unnötigen personenbezogenen Daten in GitHub, Slack, Tests oder Logs speichern.
- Für Tests nur harmlose, notwendige Testdaten verwenden.

## Praxisnachweis

- **BESTANDEN ✅** = tatsächlich ausgeführt und nachvollziehbar bestätigt.
- **NOCH OFFEN ⏳** = noch nicht praktisch geprüft oder notwendige autorisierte Voraussetzung fehlt.
- **NICHT BESTANDEN ❌** = praktisch geprüft und erwartetes Verhalten nicht erreicht.
- Theoretisch vorhandene Funktionen, Simulationen, Builds oder grüne automatische Tests nicht als echten Praxistest ausgeben.
- Keine Produktivlogik nur für einen grünen Test verbiegen. Wird ein echtes fehlendes Stück gefunden, minimal innerhalb der bestehenden Architektur ergänzen und denselben relevanten Test erneut ausführen.
- Historische Nachweise erhalten. Temporäre Testreste nur gefahrlos und ohne Beweisverlust bereinigen.

## Abschluss

Vor Abschluss Änderungen und Dokumentation zurücklesen und auf Widersprüche, Doppelungen und unbeabsichtigte Nebenänderungen prüfen.

**Bestehendes erhalten. Nur Fehlendes ergänzen. Keine Nebenbaustellen. Keine Schutzmechanismen umgehen. Erst praktisch nachgewiesen = BESTANDEN.**
