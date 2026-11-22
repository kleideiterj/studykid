# StudyBox

StudyBox ist eine selbst gestaltete Webseite mit digitalen Starterpaketen für Studierende. Sie zeigt, welche Technik für verschiedene Studienbereiche sinnvoll ist, und stellt beispielhaft dar, wie ein Online-Shop mit Paketen, Warenkorb und Bestellung aussehen könnte.

## Webseite ansehen

Die Webseite besteht aus HTML- und CSS-Dateien. Eine Installation ist nicht erforderlich.

1. Den Projektordner in VS Code öffnen.
2. Die Datei `index.html` öffnen und **Open with Live Server** auswählen.
   Alternativ kann `index.html` direkt per Doppelklick im Browser geöffnet werden.

## Inhalte und Seiten

- **Startseite** (`index.html`): Einführung in StudyBox, Hinweise zur Technik und Richtwerte für die einzelnen Studienbereiche.
- **Pakete** (Ordner `pages/bundles/`): Die Übersicht `bundle.html` zeigt sechs Starterpakete für Informatik, Ingenieurwesen und Technik, Medien und Gestaltung, Soziales und Gesundheit, Wirtschaft und Digitales sowie Wirtschaft und Management. Die einzelnen Pakete sind in eigenen Seiten beschrieben: `informatik-bundle.html`, `technik-bundle.html`, `medien-gestaltung-bundle.html`, `soziales-gesundheit-bundle.html`, `wirtschaft-digitales-bundle.html` und `wirtschaft-management.html`.
- **Warenkorb und Bestellung** (Ordner `pages/warenkorb/`): Beispielansichten für Warenkorb, Kasse, Bestellübersicht und Bestätigung (`warenkorb.html`, `kasse.html`, `bestelluebersicht.html`, `2bestelluebersicht.html`, `bestellt.html`). Dort befinden sich auch die Seiten zum Studentenrabatt (`studentenrabatt.html`, `rabattcode.html`).
- **Konto** (Ordner `pages/konto/`): Ansichten zum Anmelden und Registrieren (`profilAnmelden.html`, `profilErstellen.html`).
- **Informationen** (Ordner `pages/footer/`): FAQ, Über uns, Impressum und Datenschutz (`faq.html`, `ueber.html`, `impressum.html`, `datenschutz.html`).

## Aufbau des Projekts

studybox
├── .vscode/
│   └── launch.json
├── assets/
│   ├── css/            # Gestaltung (Navigation, Seitenbereiche, einzelne Seiten)
│   └── img/            # Produktbilder, Logos und Zahlungslogos
├── pages/
│   ├── bundles/        # Paketübersicht und sechs Starterpakete
│   ├── footer/         # FAQ, Über uns, Impressum, Datenschutz
│   ├── konto/          # Anmelden und Registrieren
│   └── warenkorb/      # Warenkorb, Kasse, Bestellung, Studentenrabatt
├── index.html          # Startseite
└── README2.md

Das Aussehen der Seiten wird über die CSS-Dateien in `assets/css/` festgelegt. Bilder und Logos liegen in `assets/img/`.

## Wichtiger Hinweis

StudyBox ist ein Projekt zur Darstellung und kein funktionsfähiger Online-Shop. Warenkorb, Buttons, Anmeldung, Rabattantrag, Zahlungsarten und Bestellseiten sind reine Beispielansichten ohne Funktion. Es werden weder Nutzerkonten angelegt noch Daten gespeichert, und Zahlungen oder Bestellungen werden nicht ausgeführt. Echte Zugangsdaten, Zahlungsdaten oder persönliche Dokumente sollten daher nicht eingegeben werden.