# part-db_quicksearch_addon
Schnellsuche für Part-DB

Workaround für https://github.com/Part-DB/Part-DB-server/issues/305

Das part-db_quicksearch_addon ist eine einfache HTML-Datei, die es erlaubt, schnell in der Part-DB zu suchen.

Die Programmierung erfolgte mit viel Hilfe von ChatGPT, wobei meine Programmierfähigkeiten und Codequalität auf einem Anfängerniveau sind.

Das addon wird von Part-DB offiziell nicht unterstützt. Es ruft die Ergebnisse der `<Part-DB-Server>`/de/typeahead/parts/search API und gibt diese als Tabelle aus.
Eine Implementierung über die neue API wäre sicher besser.

![preview](https://github.com/RaptorDE/part-db_quicksearch_addon/assets/37591931/8fce4785-9ee9-4919-aef6-2d744413ac32)

## Funktionen
- :white_check_mark: Suche beim Schreiben
- :white_check_mark: freie Suche (Die Reihenfolge der Anfragen ist egal)
- :white_check_mark: einfache Benutzeroberfläche
- :white_check_mark: Ausgabe von Bild, Name, Beschreibung, Kategorie, Footprint und ID
- :white_check_mark: Mehrsprachig (Deutsch und Englisch)

## Einrichtung
Für den Anfang setzte ich Grundkenntnisse mit HTML voraus.
In Zukunft werde ich die Anleitung evtl. erweitern.

Die aktuelle Version wurde mit Part-DB Version: 1.10.6, mit MySQL Datenbank, Reverse Proxy und Docker getestet.

1. Download search.html [search.html](https://github.com/RaptorDE/part-db_quicksearch_addon/blob/main/search.html) 

2. Datei in `public_media` oder `public/media` Verzeichnis kopieren

4. Schnellsuche aufrufen `<Part-DB-Server-url>/media/search.html`

5. (Optional) Link in banner.md einfügen
`[Neue Schnellsuche](/media/search.html)`

## Bugreports

Wenn es zu Fehlern kommt, bitte immer einen Screenshot von der [Web-Konsole](https://firefox-source-docs.mozilla.org/devtools-user/web_console/) mit `XHR` und `Anfragen`.
![Screenshot 2024-02-03 203905](https://github.com/RaptorDE/part-db_quicksearch_addon/assets/37591931/4d530d19-fd9b-4e78-af04-10057791ae1e)

## Danksagung

Vielen Dank an das Part-DB-Projekt [https://github.com/Part-DB/Part-DB-server](https://github.com/Part-DB/Part-DB-server)

### Third party libraries
*
