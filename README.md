# part-db_quicksearch_addon
Schnellsuche für Part-DB

Das part-db_quicksearch_addon ist eine einfache HTML Datei, die es erlaubt schnell in der Part-DB zu suchen.

Die Programmierung erfolgte mit viel Hilfe von ChatGPT, wobei meine Programmierfähigkeiten und Codequalität auf einem Anfängerniveau sind.

Das Addon wird von Part-DB offizell nicht untersützt. Es ruft die Ergebnise der <Part-DB-Server>/de/typeahead/parts/search zu und gibt diese als Tabelle aus.
Eine implemetireung über die neue API währe sicher besser.

## Funktionen
- [] Suche beim schreiben
- [] freie Suche (Dei Reinfoge der Anfrgen ist egal)
- [] einfache Benutzeroberfläche


## Einrichtung
Für den Anfang setzte ich Grundkenntnisse mit der HTML voraus.
In Zukunft werde ich die Anleitung evt. erweitern.

1. Download search.html [evcc_status_display_SSD1306_github_2023_04_05.ino](https://raw.githubusercontent.com/RaptorDE/evcc_status_display/main/evcc_status_display_SSD1306_github_2023_04_05.ino) 

2. In der HTML Datei müssen folgende Zeilen angepasst werden:

``
3. Datei in public media verzeichis kopiren

4. (Optional) Link in banner.md einfügen

## Bekannte Probleme
* Bei verbindung über HTTPS und einem Reverse Proxy muss die vollständige Part-DB URL angegeben werden.

## Bilder

## Bugreports

Wenn es zu Fehlern kommt, bitte immer einen Screenshot vom der [Web-Konsole](https://firefox-source-docs.mozilla.org/devtools-user/web_console/) mit `XHR` und `Anfragen`.

## To-do-Liste
- [ ] 

## Danksagung

Vielen dank an das Part-DB Projekt [https://github.com/Part-DB/Part-DB-server](https://github.com/Part-DB/Part-DB-server)

### Third party libraries
*
