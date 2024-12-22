# DMS
Ein Dokument Management System (DMS) ist ein System zur Verwaltung von Dokumenten.

## Features

### Document Management
- Zentrales System zur Speicherung, Verwaltung und Archivierung von Dokumenten
- Möglichkeit, Dokumente zu suchen, mit Metadaten zu versehen und zu kategorisieren
- Speicherung aller Metadaten in einer Datenbank und Ablage der Dokumente in einem Dateisystem
- Unterstützung verschiedener Dokumentformate (z.B. PDF, Word, Excel, Text, Bild, Audio, Video)
- Erstellung von Unterdokumenten, die zu einem Hauptdokument gehören
- Markierung wichtiger Dokumente innerhalb einer Kategorie
- Kommentierung und Hinzufügung von Anmerkungen zu Dokumenten
- Automatische Archivierung und Löschung von Dokumenten

### Search and Retrieval
- Suche nach Dokumenten anhand von Metadaten, Kategorien oder Inhalten
- Extraktion und Durchsuchung von Text aus Dokumenten
- Filter- und Sortiermöglichkeiten für Dokumente

### Backup and Recovery
- Erstellung von Snapshots aller Dokumente zur Sicherung
- Wiederherstellung von Snapshots

### Version Control
- Versionskontrolle zur Nachverfolgung von Änderungen

### Integration
- API zur Integration des DMS in andere Systeme
- Zentrales System zur Speicherung, Verwaltung und Archivierung von Dokumenten
- Möglichkeit, Dokumente zu suchen, mit Metadaten zu versehen und zu kategorisieren
- Speicherung aller Metadaten in einer Datenbank und Ablage der Dokumente in einem Dateisystem
- Unterstützung verschiedener Dokumentformate (z.B. PDF, Word, Excel, Text, Bild, Audio, Video)
- Suche nach Dokumenten anhand von Metadaten, Kategorien oder Inhalten
- Erstellung von Snapshots aller Dokumente zur Sicherung
- Wiederherstellung von Snapshots
- Extraktion und Durchsuchung von Text aus Dokumenten
- Filter- und Sortiermöglichkeiten für Dokumente
- Erstellung von Unterdokumenten, die zu einem Hauptdokument gehören
- Markierung wichtiger Dokumente innerhalb einer Kategorie
- Versionskontrolle zur Nachverfolgung von Änderungen
- API zur Integration des DMS in andere Systeme
- Kommentierung und Hinzufügung von Anmerkungen zu Dokumenten
- Automatische Archivierung und Löschung von Dokumenten

## Workflow
### Uploading a Document
1. Dokument wird über die App hochgeladen
2. Metadaten werden erfasst und Dokument wird kategorisiert
3. Dokument wird im Dateisystem abgelegt und Metadaten in der Datenbank gespeichert
4. Dokument kann durchsucht, angezeigt, bearbeitet und gelöscht werden

### Searching for a Document
1. Suche nach Dokumenten anhand von Metadaten, Kategorien oder Inhalten
2. Dokumente werden angezeigt und können geöffnet, bearbeitet oder gelöscht werden

### Archiving a Document
1. Dokumente können archiviert werden und sind nicht mehr sichtbar, können aber wiederhergestellt werden
2. Es gitbt ein knopf zum einblenden der archivierten Dokumente / ausblenden

### Version Control
1. Änderungen an Dokumenten werden nachverfolgt und können rückgängig gemacht werden
2. Es gibt eine Versionshistorie, die alle Änderungen anzeigt

## Technologies
Das ganze soll in der .Net Umgebung umgesetzt werden.
- Blazor WebAssembly für die Frontend-Entwicklung
- ASP.NET Core für die Backend-Entwicklung
- Entity Framework Core für die Datenbankanbindung
- SQLite Server für die Datenbank

## Roadmap
## Roadmap

### Phase 1: Database and Schema
- Design the database schema using Entity Framework Core
- Create tables for documents, metadata, categories, and versions
- Implement relationships between tables
- Set up SQLite as the database provider
- Write migration scripts to create the database schema

### Phase 2: Backend Development
- Set up ASP.NET Core project
- Implement API endpoints for document management (CRUD operations)
- Implement API endpoints for search and retrieval
- Implement API endpoints for backup and recovery
- Implement API endpoints for version control
- Implement API endpoints for integration with other systems

### Phase 3: Frontend Development
- Set up Blazor WebAssembly project
- Create UI components for document upload, search, and retrieval
- Create UI components for document management (view, edit, delete)
- Create UI components for version control and history
- Create UI components for backup and recovery
- Implement user authentication and authorization

### Phase 4: Testing and Deployment
- Write unit tests for backend and frontend components
- Perform integration testing
- Set up CI/CD pipeline for automated testing and deployment
- Deploy the application to a cloud provider
