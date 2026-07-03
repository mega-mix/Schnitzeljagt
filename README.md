# Schnitzeljagd Web-App

Eine webbasierte Schnitzeljagd-Anwendung. Spieler können verschiedene Episoden durchspielen, Stationen absolvieren und Tipps abrufen. Administratoren haben die Möglichkeit, Episoden freizugeben und den Fortschritt der Spieler zu überwachen.

## Tech-Stack

* **Frontend:** Vanilla HTML, CSS, JavaScript
* **Backend/Datenbank:** Firebase Firestore
* **Authentifizierung:** Firebase Auth

## Architektur & Dateistruktur

Das Projekt ist in klare Verantwortlichkeiten getrennt:

* `/index.html` & `/start.html`: Einstiegspunkte und Episodenauswahl für den Spieler.
* `/game.html`: Die eigentliche Spieloberfläche für die Stationen.
* `/admin.html`: Dashboard für die Verwaltung von Spielern und Episoden.
* `/js/classes/FirebaseService.js`: Zentrale Schnittstelle für alle Lese- und Schreibzugriffe auf die Firestore-Datenbank.
* `/assets/`: Beinhaltet alle statischen Ressourcen wie Icons und SVGs.

## Voraussetzungen & Setup

1. **Firebase Projekt:** Ein aktives Firebase-Projekt mit aktivierter Firestore-Datenbank ist zwingend erforderlich.
2. **Konfiguration:** Die Firebase-Konfigurationsparameter müssen im Projekt hinterlegt werden (siehe entsprechende Auth/Firebase-Skripte).
3. **Lokaler Server:** Das Projekt muss über einen lokalen Webserver (z.B. Live Server Extension in VSC) ausgeführt werden, um CORS-Fehler bei Modul-Importen zu vermeiden.