# part-db_quicksearch_addon
Quick search for Part-DB

Deutsche Anleitung: [![de](https://img.shields.io/badge/lang-de-green.svg)](https://github.dev/RaptorDE/part-db_quicksearch_addon/blob/main/README.de.md)

Workaround for https://github.com/Part-DB/Part-DB-server/issues/305

The part-db_quicksearch_addon is a simple HTML file that allows you to search quickly in the Part-DB.

The programming was done with a lot of help from ChatGPT, although my programming skills and code quality are at a beginner level.

The addon is not officially supported by Part-DB. It retrieves the results of the `<Part-DB-Server>`/typeahead/parts/search API and outputs them as a table.
An implementation via the new API would certainly be better.

![preview](https://github.com/RaptorDE/part-db_quicksearch_addon/assets/37591931/8fce4785-9ee9-4919-aef6-2d744413ac32)

## Functions
:white_check_mark: search while typing
:white_check_mark: free search (the order of the queries does not matter)
:white_check_mark: simple user interface
:white_check_mark: output of image, name, description, category, footprint and ID
:white_check_mark: Multilingual (German and English)

## Setup
For the beginning I assume basic knowledge of HTML.
I may expand the instructions in the future.

The current version was tested with Part-DB version: 1.10.6, with MySQL database, reverse proxy and Docker.

1. download search.html file [search.html](https://github.com/RaptorDE/part-db_quicksearch_addon/blob/main/search.html) 

2. the following lines must be adapted in the HTML file:
* Language in line no. 1 `<html lang="en">` (`en` or `de`)
* Part-DB server URL in line no. 85 `var baseURL = '<Part-DB-Server-url>/en/typeahead/parts/search/';`

3. copy file to `public_media` or `public/media` directory

4. access quick search `<Part-DB-Server-url>/media/search.html`

5. (Optional) Insert link in banner.md
`[New quick search](/media/search.html)`

## Known problems
* When connecting via HTTPS and a reverse proxy, the complete Part-DB URL must be specified.
* Why is there no pull request in the Part DB server? I don't know how to create pages with Symfony. 😁
* maximum 100 results, API limit

## Images
![Screenshot 2024-02-03 204032](https://github.com/RaptorDE/part-db_quicksearch_addon/assets/37591931/1245374e-421f-4316-8ba8-bcd54d101929)


## Bugreports
If you are experiencing bugs, please provide a screenshot of the [Web console](https://firefox-source-docs.mozilla.org/devtools-user/web_console/) with 'XHR' and 'Requests'.
![Screenshot 2024-02-03 203905](https://github.com/RaptorDE/part-db_quicksearch_addon/assets/37591931/4d530d19-fd9b-4e78-af04-10057791ae1e)

## To-do list
- [ ] Image as link
- [ ] Footer with link to GitHub and Part-DB
- [ ] Show the number of search results

## Acknowledgments
Many thanks to the Part-DB project [https://github.com/Part-DB/Part-DB-server](https://github.com/Part-DB/Part-DB-server)

### Third party libraries
*
