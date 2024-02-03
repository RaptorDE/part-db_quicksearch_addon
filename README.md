# part-db_quicksearch_addon
Schnellsuche für Part-DB

Das part-db_quicksearch_addon ist eine einfache HTML Datei, die es erlaubt schnell in der Part-DB zu suchen.

Die Programmierung erfolgte mit viel Hilfe von ChatGPT, wobei meine Programmierfähigkeiten und Codequalität auf einem Anfängerniveau sind.

Das Addon wird von Part-DB offizell nicht untersützt. Es ruft die Ergebnise der <Part-DB-Server>/de/typeahead/parts/search API und gibt diese als Tabelle aus.
Eine implemetireung über die neue API wäre sicher besser.

## Funktionen
- :white_check_mark: Suche beim schreiben
- :white_check_mark: freie Suche (Dei Reinfoge der Anfrgen ist egal)
- :white_check_mark: einfache Benutzeroberfläche
- :white_check_mark: Ausgabe von Bild, Name, Beschreibung, Kategorie und Footprint
- :white_check_mark: Mehrsprachig (Deutsch und Englisch)

## Einrichtung
Für den Anfang setzte ich Grundkenntnisse mit der HTML voraus.
In Zukunft werde ich die Anleitung evt. erweitern.

1. Download search.html [search.html](https://raw.githubusercontent.com/RaptorDE/) 

2. In der HTML Datei müssen folgende Zeilen angepasst werden:

``
3. Datei in public media verzeichis kopiren

4. (Optional) Link in banner.md einfügen

## Bekannte Probleme
* Bei verbindung über HTTPS und einem Reverse Proxy muss die vollständige Part-DB URL angegeben werden.
* Warum ist es kein Pull request im Part-DB-server? Ich habe keine Ahnung wie man Seiten mit symfony erstellt. 😁

## Bilder

## Bugreports

Wenn es zu Fehlern kommt, bitte immer einen Screenshot vom der [Web-Konsole](https://firefox-source-docs.mozilla.org/devtools-user/web_console/) mit `XHR` und `Anfragen`.

## To-do-Liste
- [ ] 

## Danksagung

Vielen dank an das Part-DB Projekt [https://github.com/Part-DB/Part-DB-server](https://github.com/Part-DB/Part-DB-server)

### Third party libraries
*
