# Changelog

Alle signifikanten Änderungen an diesem Projekt werden in dieser Datei dokumentiert.


## [v]
### Hinzugefügt
* README und CHANGELOG erstellt.
### Geändert
* TODO ist nun eine .md

## [v1.8.0]
### Hinzugefügt
* Anzeige für gesperrte Episoden integriert.
* Markierung von Episoden als "FreeToPlay" (Kostenlos) implementiert.
* Admin-Feature: Episoden können gezielt für einzelne Spieler freigegeben oder gesperrt werden.
* Visuelles Feedback für Buttons hinzugefügt.
* Funktion für Spieler hinzugefügt, um den eigenen Fortschritt zurückzusetzen.
* Episoden-Titel in die Benutzeroberfläche eingebunden.
* Ladefunktion für neue Episoden implementiert.
### Geändert
* Admin-Tabellen strukturell angepasst.
* Tipp-System von einem auf drei Tipps erweitert.

## [v1.6.0]
### Hinzugefügt
* News-Bereich implementiert.
* Funktion zum globalen Aktivieren von Episoden hinzugefügt.
### Geändert
* Admin-Bereich neu sortiert und strukturiert.

## [v1.5.0]
### Hinzugefügt
* Speicherfunktion für gegebene Antworten implementiert.
* Speicherfunktion für abgerufene Tipps integriert.
### Geändert
* Datenbank-Architektur optimiert: Umstellung auf ein Episoden-Objekt.
* Design-Optimierungen durchgeführt.
### Behoben
* Allgemeine Fehlerbehebungen.

## [v1.4.6]
### Geändert
* Login-Prozess verbessert.

## [v1.4.5]
### Behoben
* Fehler beim Ladevorgang behoben.

## [v1.4.4]
### Behoben
* Allgemeine Fehlerbehebungen.

## [v1.4.3]
### Geändert
* Interne Funktionen optimiert.
* Button-Verhalten und -Design verbessert.
### Behoben
* Allgemeine Fehlerbehebungen.

## [v1.4.2]
### Geändert
* Nomenklatur-Update: "Gruppen" werden nun als "Spieler" geführt.
* Validierung hinzugefügt: Spielernamen sind nun gegen Sonderzeichen abgesichert.

## [v1.4.1]
### Behoben
* Kleinere Bugfixes.

## [v1.4.0]
### Hinzugefügt
* Zähler für geprüfte Antworten implementiert.

## [v1.3.0]
### Hinzugefügt
* Tipps für Spieler sind abrufbar.
* Globale Freigabe-Funktion für Tipps implementiert.
* Zähler für abgerufene Tipps integriert.
### Geändert
* Performance-Optimierung: Anzahl der Datenbankzugriffe reduziert.

## [v1.2.0]
### Hinzugefügt
* Unterstützung für mehrere parallele Fragenkataloge.
### Geändert
* Struktur-Update: Aufteilung der Architektur auf unterschiedliche HTML-Seiten.
* Admin-Bereich um neue Verwaltungsfunktionen erweitert.

## [v1.1.2]
### Hinzugefügt
* Projekt-Logo eingebunden.
* Globales Design und Styling implementiert.
### Behoben
* Allgemeine Bugfixes.

## [v1.1.1]
### Behoben
* Kleinere Bugfixes zur Stabilität.

## [v1.1.0]
### Hinzugefügt
* Dedizierte Login-Seite und Spiel-Seite erstellt.
* Admin-Feature: Fragen können nun direkt im Panel bearbeitet werden.
### Entfernt
* Lokaler/statischer Fragencontainer gelöscht.

## [v1.0.0]
### Hinzugefügt
* System-Logik: Anmeldung läuft ab sofort über die Datenbank.
### Geändert
* Admin-Bereich strukturell stark ausgebaut.
* Daten-Migration: Alle Fragen werden nun vollständig über die Datenbank geladen und verwaltet.