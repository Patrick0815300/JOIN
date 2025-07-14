# JOIN – Task Manager

**JOIN** ist ein moderner Task Manager, inspiriert vom Kanban-System. Er ermöglicht das Erstellen, Organisieren und Bearbeiten von Aufgaben mit intuitiven Drag-and-Drop-Funktionen. Nutzer können Aufgaben Personen und Kategorien zuweisen und den Überblick über den Fortschritt behalten.

## Inhaltsverzeichnis

- [Über das Projekt](#über-das-projekt)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Verwendung](#verwendung)
- [Technologien](#technologien)
- [Kontakt](#kontakt)

## Über das Projekt

JOIN ist ein webbasiertes Task-Management-Tool, das die Prinzipien des Kanban-Boards nutzt, um Aufgaben effizient zu verwalten. Ziel ist es, Teams und Einzelpersonen eine einfache, flexible und übersichtliche Möglichkeit zu bieten, Workflows zu organisieren.

## Features

- **Kanban Board:** Aufgaben werden als Karten in den Spalten *To Do*, *In Progress*, *Await Feedback* und *Done* dargestellt. Aufgaben lassen sich per Drag & Drop verschieben.
- **Task Management:** Aufgaben können mit Titel, Beschreibung, Verantwortlichen, Fälligkeitsdatum, Priorität, Kategorie und Subtasks angelegt und bearbeitet werden.
- **Benutzerverwaltung:** Anmeldung als Gast oder Registrierung mit eigenem Account möglich.
- **Summary-Seite:** Übersicht über alle wesentlichen Ereignisse wie Anzahl der offenen, in Bearbeitung befindlichen und abgeschlossenen Aufgaben.
- **Kontakte:** Verwaltung und Bearbeitung von Kontakten mit Name, E-Mail und Telefonnummer. Kontakte können Aufgaben zugewiesen werden.
- **Firebase Integration:** Sichere Speicherung aller Daten in der Cloud.
- **Intuitive Bedienung:** Moderne Benutzeroberfläche und responsive Design.

## Demo

https://join.patrick-nigrin.dev/

## Installation

1. **Repository klonen**
   ```bash
   git clone https://github.com/dein-benutzername/join.git
   cd join
   ```

2. **Abhängigkeiten installieren**
   > Da JOIN mit Vanilla JS entwickelt wurde, sind keine weiteren Build-Tools nötig. Stelle sicher, dass du einen lokalen Webserver verwendest (z.B. mit VS Code Live Server Extension).

3. **Firebase konfigurieren**
   - Lege ein Firebase-Projekt an.
   - Erstelle eine `firebaseConfig.js` mit deinen Zugangsdaten:
     ```js
     // Beispiel
     const firebaseConfig = {
       apiKey: "DEIN_API_KEY",
       authDomain: "DEIN_AUTH_DOMAIN",
       projectId: "DEIN_PROJECT_ID",
       // ...
     };
     ```
   - Weitere Informationen findest du in der Firebase-Dokumentation.

4. **Projekt starten**
   - Öffne `index.html` im Browser oder starte den lokalen Webserver.

## Verwendung

- **Login:** Melde dich als Gast an oder registriere einen neuen Account.
- **Summary:** Verschaffe dir einen Überblick über alle Aufgaben und deren Status.
- **Tasks hinzufügen:** Erstelle neue Aufgaben mit allen relevanten Details.
- **Board:** Organisiere Aufgaben per Drag & Drop auf dem Kanban-Board.
- **Kontakte:** Lege neue Kontakte an oder bearbeite bestehende, um sie Aufgaben zuzuweisen.

## Technologien

| Technologie | Beschreibung                |
|-------------|----------------------------|
| Vanilla JS  | Frontend-Entwicklung       |
| Firebase    | Authentifizierung & Datenbank |
| HTML/CSS    | Struktur & Styling         |


## Kontakt

Bei Fragen oder Anregungen:
- **Patrick Nigrin**
- E-Mail: [mail@patrick-nigrin.dev]

*Halte die README aktuell und passe sie bei Änderungen am Projekt an. Eine gute Dokumentation hilft allen Nutzer*innen!*
