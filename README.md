# SQL Injection – Imperien stürzen

Eine interaktive, webbasierte Präsentation zum Thema SQL-Injection.

## Projektbeschreibung
Dieses Projekt beinhaltet die Folien und interaktiven Demos für ein Referat über SQL Injection. Statt einer klassischen PowerPoint-Präsentation wird eine moderne Single-Page-Webanwendung (HTML/CSS/JS) genutzt, die Live-Demonstrationen der unterschiedlichen Angriffsvektoren erlaubt.

**Referenten:** Jonas & Paul

## Features
* **Vollständig autark:** Alles läuft in einer einzigen `index.html` Datei ohne externe Abhängigkeiten. Es wird kein Backend und keine echte Datenbank benötigt, alle SQL-Abfragen und Injections werden anschaulich per JavaScript simuliert.
* **Kurz & Prägnant:** Die Slides sind in übersichtliche Bulletpoints gegliedert, ideal zur Begleitung des mündlichen Vortrags.
* **Interaktive Live-Demos:**
  * Vulnerabler Code & Admin-Bypass (`admin' --`)
  * Tautologien-Login (`' OR '1'='1`)
  * Time-Based Blind SQLi Simulation
  * Prepared Statements (sicherer Login / Trennung von Code & Daten)
* **Präsentationsmodus:** Navigation über Pfeiltasten, optimiert für Fullscreen-Displays ohne störende Scrollbalken.

## Nutzung / Starten
Einfach die Datei `index.html` in einem beliebigen modernen Webbrowser (Chrome, Firefox, Edge, Safari) öffnen. 
Es wird kein lokaler Webserver wie XAMPP benötigt (kann direkt lokal per `file://` aufgerufen werden, auch wenn es aktuell im `htdocs` Ordner liegt).

## Navigation in der Präsentation
* **Nächste Folie:** Rechte Pfeiltaste, Leertaste oder Klick auf den rechten Bildschirmrand.
* **Vorherige Folie:** Linke Pfeiltaste oder Klick auf den linken Bildschirmrand.
