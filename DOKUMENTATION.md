streamly-plus/
├── backend/ # Node.js Backend
│ ├── server.js # Hauptserver-Datei
│ ├── routes/ # API-Routen (z. B. /movies, /users)
│ ├── controllers/ # Logik für die Endpunkte
│ ├── models/ # Datenmodelle (z. B. Movie, User)
│ └── config/ # Datenbankverbindung & Umgebungsvariablen
│
├── frontend/ # React Frontend
│ ├── public/ # Statische Dateien
│ └── src/
│   ├── components/ # Wiederverwendbare UI-Komponenten
│   ├── pages/ # Seiten (Home, Details, Login)
│   ├── App.js # Haupt-App-Komponente
│   └── index.js # Einstiegspunkt
│
├── database/ # SQL-Dateien für Tabellenstruktur & Seed-Daten
│ └── schema.sql
│
├── README.md # Kurzbeschreibung
├── DOKUMENTATION.md # Dokumentation
└── package.json # Projekt- und Abhängigkeitsverwaltung