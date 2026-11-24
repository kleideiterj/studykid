# StudyBox

StudyBox ist ein deutschsprachiger Webseite-Prototyp für digitale Starterpakete für Studierende. Die Seiten informieren über passende Technik für verschiedene Studienbereiche und zeigen beispielhaft einen Online-Shop mit Bundles, Warenkorb und Bestellablauf.

## Website lokal starten

Das Projekt besteht aus statischen HTML- und CSS-Dateien. Es benötigt weder eine Installation von Abhängigkeiten noch einen Build-Schritt.

1. Öffne ein Terminal im Projektordner.
2. Starte einen lokalen Webserver, zum Beispiel mit Python:

   ```powershell
   py -m http.server 8000
   ```

3. Rufe im Browser [http://localhost:8000/startseite.html](http://localhost:8000/startseite.html) auf.

Alternativ kannst du die Website mit der VS-Code-Erweiterung **Live Server** starten. Öffne `startseite.html` und wähle **Open with Live Server**.

> Im Projektstamm gibt es keine `index.html`. Öffne deshalb `startseite.html` direkt.

## Inhalte und Seiten

- **Startseite (`startseite.html`)** – Einführung in StudyBox, Hinweise zu Hardware und Richtwerte nach Studienbereich.
- **Bundle-Übersicht (`bundle.html`)** – fünf Starterpakete für Informatik, Ingenieurwesen und Technik, Medien und Gestaltung, Soziales und Gesundheit sowie Wirtschaft und Digitales.
- **Bundle-Details** – einzelne Seiten zu den fünf Paketen: `informatik-bundle.html`, `technik-bundle.html`, `medien-gestaltung-bundle.html`, `soziales-gesundheit-bundle.html` und `wirtschaft-digitales-bundle.html`.
- **Produkte und Zubehör** – weitere Angebotsseiten unter `produkte.html`, `hardware.html` und `zubehoer.html`.
- **Studentenrabatt** – Informationen und eine beispielhafte Rabattstrecke unter `studentenrabatt.html` und `rabattcode.html`.
- **Warenkorb und Bestellung** – statische Ansichten des Warenkorbs, der Kasse, der Bestellübersicht und einer Bestellbestätigung: `warenkorb.html`, `kasse.html`, `bestelluebersicht.html`, `2bestelluebersicht.html` und `bestellt.html`.
- **Profil** – Anmelde- und Registrierungsansichten unter `profilAnmelden.html` und `profilErstellen.html`.
- **Informationen** – FAQ, Über uns, Hilfe, Impressum und Datenschutz unter `FAQ.html`, `ueber.html`, `Hilfe.html`, `impressum.html` und `datenschutz.html`.

Einige Dateien enthalten alternative oder ältere Seitenvarianten, zum Beispiel `bundles.html` und `pages/startseiteneu.html`. Die Hauptnavigation der Startseite führt zu `bundle.html`.

## Projektstruktur

```text
.
├── assets/
│   ├── css/       # Stylesheets für Navigation, Seitenbereiche und einzelne Ansichten
│   └── img/       # Produktbilder, Logos und Zahlungslogos
├── pages/         # Alternative bzw. zusätzliche HTML-Seiten
├── *.html         # Website-Seiten im Projektstamm
└── README.md
```

Die Gestaltung erfolgt mit CSS-Dateien in `assets/css/`. Bilder und Logos liegen in `assets/img/`. Die Website verwendet kein JavaScript- oder Backend-Framework.

## Hinweis zum Funktionsumfang

StudyBox ist ein **Darstellungs- und Demonstrationsprototyp**, kein betriebsbereiter Online-Shop. Warenkorb, Produktbuttons, Anmeldung, Rabattbeantragung, Zahlungsarten und Bestellseiten sind überwiegend statische Beispielansichten. Es gibt keine echte Benutzerverwaltung, Datenverarbeitung, Dateiübertragung, Zahlungsabwicklung oder Bestellspeicherung. Verwende daher keine echten Zugangsdaten, Zahlungsdaten oder persönlichen Dokumente.
