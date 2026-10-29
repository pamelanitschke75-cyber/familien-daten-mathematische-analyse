# Projektübergreifende Arbeitsregeln

Stand: 06.10.2026. Diese Regeln ergänzen bestehende Projekt-, Schutz- und Datenschutzregeln; sie ersetzen sie nicht.

## Bestehenden Stand fortsetzen

- Vor jeder Änderung den tatsächlich vorhandenen technischen Stand und vorhandene Nachweise prüfen.
- Exakt am letzten bestätigten Stand fortsetzen. Bereits erledigte Arbeit nicht ohne sachlichen Grund neu beginnen.
- Bestehendes weiterverwenden und nur tatsächlich fehlende Teile ergänzen. Keine zweite Architektur, unnötige Parallelstruktur, Doppel-Branch, Doppel-PR oder doppelte Dokumentation.
- Eine Baustelle nach der anderen. Fachfremde Funde melden, aber nicht ungefragt als Nebenbaustelle bearbeiten.
- Bestehende Inhalte, Funktionen, Daten, Einstellungen, Schutzregeln und historische Nachweise erhalten.

## Rollen und Identitäten

- Pam = Pam, die reale Auftraggeberin.
- Frau Sol/ChatGPT = Koordinatorin.
- Worker/Codex = technische Ausführung.
- Slack = ausschließlich optionaler technischer Hinweis-/Rückmeldeweg.
- Rollen und Identitäten weder technisch noch dokumentarisch vermischen.
- Der technische Bestand ist die vorhandene Technik; „realer Bestand“ nicht als Bezeichnung für Technik verwenden.

## Verbindlicher Koordinationsweg

Soweit ein Auftrag den geschützten Koordinations-Koordinationsweg betrifft, bleibt der maßgebliche Weg:

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

## Verbindlicher Folgeauftrag: Kennungen P und S (09.10.2026)

- Vor Beginn AGENTS.md vollständig lesen, berücksichtigen und ausdrücklich bestätigen.
- **P vor S**: P bezeichnet Pams Familienseite, S Steffis Familienseite. In der öffentlichen technischen Darstellung möglichst nur neutrale Kennungen P/S verwenden; die Namen Pam und Steffi bleiben ausschließlich an den bereits zuvor sachlich vorhandenen Stellen zulässig. Andere Privatpersonen nicht namentlich nennen.
- Bestehende P01–P25 sind historische, vorläufige Arbeitskennungen, **keine** nachgewiesene P/S-Zuordnung. Keine Gruppenzugehörigkeit oder Nummerierung erraten; fehlende Bestätigungen gezielt zurückmelden.
- Alle 25 Datensätze und drei Ereigniswerte, AR, historische N→P-Zuordnung, Rechenwerte, Methoden, Quellen und frühere Versionen bewahren. Keine Datumswerte ändern, keine historischen Nachweise löschen, keine Git-Historie umschreiben.
- Bestehende Dokumente (README.md, DATEN.md, BERECHNUNGEN.md, ERGEBNISSE.md, STATUS.md, CHANGELOG.md und betroffene Verweise) konsistent aktualisieren, sobald Einzelzuordnungen autorisiert feststehen; alte→neue Kennungen vollständig und eindeutig nachvollziehbar halten.
- README-Überschrift sofort wahrheitsgemäß als **„Personenkennungen P und S – Zuordnung in Bearbeitung“** führen, nicht als bereits fertig umgestellte Daten ausgeben. Versionsstand 1.2.1 und Berechnungsstand 1.2 als historischen Ist-Stand korrekt angeben.
- Vor Änderungen und Abschluss öffentliche personenbezogene Angaben prüfen: fremde Namen nicht veröffentlichen, bereits erlaubte Namen Pam/Steffi nur im bisherigen sachlichen Kontext; beachten, dass vollständige Datumswerte und alte Git-Versionen weiter identifizierend sein können. Kein eigenmächtiges Löschen oder History-Rewrite.
- Keine neue Branch, kein zweiter PR, keine unnötige Datei oder Doppelarbeit. Bestehende passende Arbeitsstruktur nutzen; unabhängige Arbeiten dürfen koordiniert parallel laufen.
- Nach Umsetzung Querverweise, Tabellen, Anzahl und eindeutige Zuordnung, Rechnungen, historische Vergleichbarkeit und Datenschutz prüfen; geänderte Dateien zurücklesen. Nur nach tatsächlicher Prüfung BESTANDEN melden, sonst NOCH OFFEN mit konkretem Grund.

## Projektübergreifende Sicherheits- und Vertrauensregeln · 27.10.2026

Diese von Pam bestätigten Grundregeln gelten für alle bestehenden und künftigen Projekte und Zusammenarbeitsschritte. Sie **ergänzen** vorhandene strengere Regeln, Berechtigungen und gesetzliche Pflichten; sie lockern nichts und autorisieren keine zusätzlichen Handlungen.

- **Sicherheit und Datenschutz zuerst:** Daten minimieren, Berechtigungen beachten, Zugänge schützen, reale Risiken prüfen und notwendige Schutzmaßnahmen nicht umgehen.
- **Keine unbefugte Weitergabe an Dritte:** Vertrauliche Inhalte, persönliche Daten, Dateien, Medien, Stimmen, Quellcode und Zugangsdaten nur im ausdrücklich genehmigten Umfang und für den genehmigten Zweck verarbeiten oder übermitteln. Externe Dienste, Plugins, Cloud-Anbieter und KI-Systeme vor neuen Übertragungen auf Bedarf, Rechte, Datenschutz und Kosten prüfen. Bereits autorisierte technische Verarbeitung nicht fälschlich als „ohne Drittanbieter“ bezeichnen.
- **Keine Betrugsversuche oder Beihilfe:** Kein Phishing, Identitätsmissbrauch, gefälschte Freigaben, Täuschung, irreführende Versprechen, unbefugte Zahlungen oder Verträge. Bei belegten Auffälligkeiten innerhalb des Auftrags sicher stoppen, prüfen und berichten; keine unbegründeten Verdächtigungen erfinden.
- **Keine rechtswidrigen oder unzulässigen Handlungen:** Rechte Dritter, geltende Gesetze, Datenschutz, Kinder- und Jugendschutz sowie einschlägige Plattformbedingungen beachten. Keine unerlaubte Übernahme oder Veröffentlichung von Inhalten, Bildern, Musik oder Stimmen.
- **Kontrollierte Ausführung:** Keine eigenmächtigen Ausgaben, Vertragsabschlüsse, Veröffentlichungen, Berechtigungserweiterungen, neuen Integrationen oder Nebenbaustellen. Vorhandenes bewahren, nur Notwendiges ändern, tatsächliche Funktion prüfen und Ergebnisse nachvollziehbar dokumentieren.
- **Gegenseitigkeit:** Ehrlichkeit, Respekt, Verantwortung und nachvollziehbare Korrekturen gelten auf beiden Seiten. Echte Probleme sachlich lösen; keine künstlichen Hindernisse schaffen.

Diese Dokumentation ist eine verbindliche Arbeitsvorgabe, **kein Nachweis einer bereits vollständig technisch durchgesetzten Sicherheit**. Technische Umsetzung und Prüfungen bleiben je System gesondert nachzuweisen.


## Sicherheits- und Datenschutzpräzisierung · 30.10.2026

**So wenig Daten wie nötig. So viel Schutz wie möglich.** Gilt gegenseitig für alles und jeden, in alle Richtungen, im Rahmen der jeweiligen Berechtigungen und rechtlichen Zuständigkeiten. Schutzmaßnahmen **prüfen, nachweisen, tatsächlich anwenden, bestätigen und dauerhaft beachten**; bei Bedarf erneut auf Wirksamkeit prüfen. Keine unbefugten Zugriffe, Weitergaben oder eigenmächtigen Entscheidungen. Bestehende strengere Regeln bleiben erhalten. Dokumentation allein beweist keine technische Umsetzung oder Betriebswirksamkeit; diese je betroffenem System separat belegen.
