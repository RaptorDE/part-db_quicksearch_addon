# part-db_quicksearch_addon
Schnellsuche für Part-DB

Das part-db_quicksearch_addon ist eine einfache HTML-Datei, die es erlaubt, schnell in der Part-DB zu suchen.

Die Programmierung erfolgte mit viel Hilfe von ChatGPT, wobei meine Programmierfähigkeiten und Codequalität auf einem Anfängerniveau sind.

Das addon wird von Part-DB offiziell nicht unterstützt. Es ruft die Ergebnisse der <Part-DB-Server>/de/typeahead/parts/search API und gibt diese als Tabelle aus.
Eine Implementierung über die neue API wäre sicher besser.

## Funktionen
- :white_check_mark: Suche beim Schreiben
- :white_check_mark: freie Suche (Die Reihenfolge der Anfragen ist egal)
- :white_check_mark: einfache Benutzeroberfläche
- :white_check_mark: Ausgabe von Bild, Name, Beschreibung, Kategorie und Footprint
- :white_check_mark: Mehrsprachig (Deutsch und Englisch)

## Einrichtung
Für den Anfang setzte ich Grundkenntnisse mit HTML voraus.
In Zukunft werde ich die Anleitung evtl. erweitern.

1. Download search.html [search.html](https://raw.githubusercontent.com/RaptorDE/) 

2. In der HTML-Datei müssen folgende Zeilen angepasst werden:

``
3. Datei in public media Verzeichnis kopieren

4. (Optional) Link in banner.md einfügen

## Bekannte Probleme
* Bei Verbindung über HTTPS und einem Reverse Proxy muss die vollständige Part-DB-URL angegeben werden.
* Warum ist es kein Pull Request im Part-DB-Server? Ich weiß nicht, wie man Seiten mit Symfony erstellt. 😁

## Bilder

## Bugreports

Wenn es zu Fehlern kommt, bitte immer einen Screenshot von der [Web-Konsole](https://firefox-source-docs.mozilla.org/devtools-user/web_console/) mit `XHR` und `Anfragen`.

## To-do-Liste
- [ ] ID in Tabelle anzeigen

## Danksagung

Vielen Dank an das Part-DB-Projekt [https://github.com/Part-DB/Part-DB-server](https://github.com/Part-DB/Part-DB-server)

### Third party libraries
*
