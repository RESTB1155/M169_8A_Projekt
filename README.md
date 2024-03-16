# M169_8A_Projekt Gruppenarbeit
https://gitlab.com/kerest/M169_8A_Projekt

[Dokumentation](https://docs.google.com/document/d/1rS9CFPCXiShLRO7wt9GWhbCPPX2VK8LE81hM7tWcOFA/edit?usp=sharing)

## Auftrag

Für ein Informatik-KMU sollst du einige Dienste einrichten. Folgende Anforderungen wurden vom Auftraggeber formuliert:

1. Das KMU möchte ein Media-Wiki für firmeninterne Zwecke. Das Portal soll auf Port 8085 verfügbar sein.

2. Das KMU möchte die Open-Source Filesharing- und Collaborationsplattform Nextcloud einsetzen. Das Webinterface soll auf Port 8080 erreichbar sein.

3. Das Unternehmen möchte den Quellcode firmenintern auf einer eigenen Gitlab- oder gogs Instanz verwalten.

4. Alle Daten der Dienste müssen persistent gespeichert werden.

5. Die Dienste sollen mit Portainer überwacht werden.

6. Die notwendigen Dateien sowie die Systemdokumentation sollen auf deinem privaten Github-Account versioniert werden.

## Empfohlenes Vorgehen gemäss IPERKA:

1. Informieren: Anforderungen genau analysieren.

2. Planen: Arbeitsplan mit Zeiten erstellen.

3. Entscheiden:
   - Systemüberblick aussagekräftig skizzieren.
   - Testkonzept und Testplan erstellen.
   - Sicherheitsanforderungen definieren.

4. Realisieren (für jedes Teilsystem):
   - docker-compose erstellen.
   - Testen und protokollieren.

5. Kontrollieren: Welche Abweichungen gab es vom Arbeitsplan?

6. Auswerten: Was habe ich gelernt?

## Hinweis:

Zum Starten des Gitlab-Containers benötigt die VM mindestens 4GB RAM und 6GB freie SSD. Starten und Stoppen dauert einige Minuten. Die Alternative gogs ist deutlich ressourcenschonender und bietet ebenfalls ein vollständige Multiuser-Codeversionierungsplattform.

## Bewertungsgrundlage pro Gruppe:

- Repository
- Dokumentation (ein Dokument das zB an einen Auftraggeber übergeben werden könnte)
- Testkonzept
- Arbeitsjournal (soll eure Tätigkeiten für mich besser nachvollziehbar machen, sollte auch Probleme enthalten die aufgetaucht sind und gelöst wurden etc., der Beitrag der einzelnen Teammitglieder soll ersichtlich sein)

Es gibt grundsätzlich eine gemeinsame Note pro Gruppe!
