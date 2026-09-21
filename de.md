# Datenschutzerklärung

Stand: Mai 2026

## 1. Einleitung

Vielen Dank, dass Sie diese Anwendung („App“) nutzen. Wir legen großen Wert auf den Schutz Ihrer Privatsphäre. Diese Datenschutzerklärung erläutert, wie wir Ihre personenbezogenen Daten erfassen, verwenden, speichern und weitergeben, wenn Sie die App nutzen.

## 2. Welche Informationen wir erfassen

### 1) Spielleistungsdaten

- Abweichungszeit: Die Differenz zwischen dem Zeitpunkt, an dem Sie auf die Stopp-Taste tippen, und der Zielzeit (9,9 Sekunden) für jedes Spiel, mit vier Nachkommastellen in Sekunden, einschließlich positiver und negativer Werte.
- Spielzeitstempel: Der Zeitpunkt, zu dem jedes Spiel abgeschlossen wurde.
- Bewertungsinformationen: Bewertungen basierend auf Ihrer Abweichung (Perfect / Master / Expert / Good / Miss) und ob Sie die perfekte Abweichung getroffen haben (Perfect Hit).

### 2) Geräteinformationen

- Gerätemodell (z. B. iPhone 15 Pro): Wird zur Analyse der Leistung auf verschiedenen Geräten verwendet.
- Betriebssystemversion (z. B. iOS 18.0): Wird für Kompatibilitätsanalysen und statistische Auswertungen verwendet.
- Eindeutiger Geräteidentifikator: Eine lokal gespeicherte, vom System automatisch erzeugte UUID, die verwendet wird, um dasselbe Gerät über verschiedene Spielsitzungen hinweg zu identifizieren. Sie wird nicht auf den Server hochgeladen, außer Sie entscheiden sich dafür, eine Punktzahl auf die Rangliste zu senden.

### 3) Informationen, die Sie freiwillig bereitstellen

- Spitzname: Optional, kann beim Senden einer Punktzahl an die Rangliste eingegeben werden. Wenn leer gelassen, zeigt das System „Anonymous“ an. Ihr Spitzname wird zusammen mit den Bewertungsdaten an den Ranglistenserver übermittelt.

### 4) App-Einstellungen (nur lokal gespeichert)

- Status der Soundeffekte
- Status der haptischen Rückmeldung
- Spracheinstellung
- Datum des ersten Starts

Diese Einstellungen werden nur auf Ihrem Gerät gespeichert und nicht an Server übertragen.

## 3. Wie wir Ihre Informationen verwenden

1. Kernfunktionalität: Berechnung und Anzeige Ihrer Zeitabweichung und Bereitstellung von Spielbewertungsfeedback.
2. Lokale Datenspeicherung: Speichern Ihrer Spielhistorie auf Ihrem Gerät mit Core Data.
3. Ranglistenservice: Mit Ihrer Zustimmung werden Spielresultate (Abweichung, Bewertung, Spitzname, Gerätemodell, Systemversion) an den Cloud-Ranglistenserver übermittelt, damit Sie und andere darauf Bezug nehmen können.
4. Geräteidentifikation: Verwendung der lokalen UUID als Identifikationsmerkmal, um Aufzeichnungen auf verschiedenen Geräten zu unterscheiden.
5. Produktverbesserung: Analyse anonymisierter Statistiken zur Optimierung der Benutzererfahrung.

## 4. Audio-Funktionshinweis

Diese App nutzt die folgenden audiobezogenen Technologien:

| Technologie | Zweck | Mikrofonberechtigung erforderlich |
| --- | --- | --- |
| AVAudioSession | Konfiguration der Audio-Session und gemeinsame Nutzung mit anderen Audio-Apps (Mix-Modus) | Nein |
| AVAudioEngine / AVAudioPlayerNode | Wiedergabe von Soundeffekten in der App (Countdown, Herzschlag, Stopp, Perfect Hit, Fehlermeldungen) | Nein |
| CoreHaptics | Bereitstellung von haptischem Feedback (Vibration) | Nein |

Wichtiger Hinweis: Diese App verwendet kein Mikrofon und erfasst keine Audioeingabedaten. Alle Töne werden aus Sounddateien innerhalb der App abgespielt, und es ist keine Mikrofonberechtigung erforderlich.

Gemäß der App-Store-Berechtigungserklärung ist die von dieser App deklarierte Audio-Berechtigung auf das Management der System-Audio-Session begrenzt und beinhaltet keine Mikrofonerfassung. Die App spielt nur integrierte Soundeffekte ab und greift nicht auf die Audioeingabe des Benutzers zu oder zeichnet sie auf.

## 5. Informationenaustausch und Offenlegung

Wir verkaufen, vermieten oder teilen Ihre personenbezogenen Daten nicht mit Dritten.

Die einzige Ausnahme besteht darin, dass Ihre Spieldaten an unseren Cloud-Server (Supabase) übertragen werden, wenn Sie sich dafür entscheiden, eine Punktzahl an die Rangliste zu senden. Der Serveranbieter erfüllt die geltenden Datenschutzbestimmungen, und wir haben angemessene Maßnahmen ergriffen, um die Sicherheit Ihrer Daten zu gewährleisten.

## 6. Datenspeicherung und Aufbewahrung

- Lokale Daten: Ihre Spielhistorie wird dauerhaft auf Ihrem Gerät gespeichert. Sie können den Verlauf über die App-Einstellungen löschen.
- Cloud-Daten: Ranglistenpunkte werden auf dem Supabase-Server gespeichert und je nach täglichem Übermittlungslimit aufbewahrt. Punktzahlen, die das Limit überschreiten, werden nicht übermittelt, beeinflussen aber Ihre lokalen Einträge nicht.
- Datenbereinigung: Wenn die Anzahl der lokalen Einträge 1.000 überschreitet, entfernt das System automatisch die ältesten Einträge, um Speicherplatz freizugeben.

## 7. Ihre Rechte

Nach geltendem Datenschutzrecht haben Sie folgende Rechte:

1. Auskunftsrecht: Sie können Ihre in der App erzeugten personenbezogenen Daten jederzeit einsehen.
2. Recht auf Berichtigung: Korrektur unrichtiger Informationen (z. B. Spitzname).
3. Recht auf Löschung: Bitte um Löschung Ihrer Spielpunktzahlen.
4. Widerrufsrecht: Sie können jederzeit entscheiden, keine Punktzahlen an die Rangliste zu senden. Dies hat keine Auswirkungen auf die weitere Nutzung der Kernfunktionen der App.
5. Widerspruchsrecht: Wenn Sie der Ansicht sind, dass wir personenbezogene Daten in unangemessener Weise verarbeiten, können Sie Widerspruch einlegen.

Um diese Rechte auszuüben, kontaktieren Sie uns bitte unter yufei.cjn@outlook.com.

## 8. Datensicherheit

Wir treffen angemessene technische und organisatorische Maßnahmen zum Schutz Ihrer personenbezogenen Daten, unter anderem:

- Verwendung von HTTPS zur Verschlüsselung aller Netzübertragungen
- Implementierung von Zeilenebenen-Sicherheit (RLS) auf dem Server, um den Datenzugriff zu begrenzen
- Verschlüsselung der lokalen Datenspeicherung

Wir können jedoch keine absolute Sicherheit für Internetübertragungen garantieren. Bitte bewahren Sie Ihre persönlichen Informationen sorgfältig auf.

## 9. Schutz von Minderjährigen

Diese App richtet sich an Nutzer aller Altersgruppen. Für minderjährige Nutzer empfehlen wir die Nutzung unter Aufsicht eines Erziehungsberechtigten. Wir erfassen nicht absichtlich personenbezogene Daten von Minderjährigen. Wenn wir feststellen, dass ohne Zustimmung der Erziehungsberechtigten personenbezogene Daten von Minderjährigen erfasst wurden, werden wir diese so schnell wie möglich löschen.

## 10. Aktualisierung der Richtlinie

Wir können diese Datenschutzerklärung von Zeit zu Zeit aktualisieren. Aktualisierte Richtlinien werden in der App angekündigt oder auf andere geeignete Weise mitgeteilt. Wir empfehlen Ihnen, diese Richtlinie regelmäßig zu prüfen, um zu verstehen, wie wir Ihre Informationen schützen.

## 11. Kontakt

Wenn Sie Fragen, Anregungen oder Vorschläge zu dieser Datenschutzerklärung haben oder Ihre Datenschutzrechte ausüben möchten, kontaktieren Sie uns bitte über:

- E-Mail: yufei.cjn@outlook.com

Wir werden nach Eingang Ihrer Anfrage so schnell wie möglich antworten.

---

Diese Datenschutzerklärung tritt mit dem Datum der Veröffentlichung in Kraft. Vielen Dank für Ihr Vertrauen und Ihre Unterstützung.
