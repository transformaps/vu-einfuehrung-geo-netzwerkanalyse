VU Einführung in die Netzwerkanalyse
==============================
 
Die Lehrveranstaltung bietet eine Einführung in die Netzwerk Analyse, ins besondere von räumlichen Netzwerken.

Das Repository beinhaltet unsere Projektaufgabe: Erstellen eines Skriptums zur Einführung in die räumliche Netzwerkanalyse mit freier und offener Software. 

Das Skriptum wird gemeinsam von David Steinwender und [Stefan Kasberger](http://twitter.com/stefankasberger) erstellt.

Sprache: Deutsch
- Dokumentation: [CC BY AT 3.0](https://creativecommons.org/licenses/by/3.0/at/)
- Code: [MIT License](http://opensource.org/licenses/MIT)

[VU Einführung in die Netzwerkanalyse](http://openscienceasap.org/education/courses/vu-einfuehrung-geo-netzwerkanalyse/) 

**Verwendete Software**
- [Ubuntu](http://www.ubuntu.com/) Linux 13.10 als Betriebssystem
- [Quantum GIS (QGIS)](http://qgis.org), v2.0.1 ([doc](http://qgis.org/de/docs/index.html)) als Desktop Geoinformationssystem.
- [GRASS GIS](http://grass.osgeo.org/) v6.4.3 ([doc](http://grass.osgeo.org/documentation/)) als Dekstop Geoinformationssystem.
- [R](http://www.r-project.org/) v3.0.2 als statistische Programmiersprache für statistische Berechnungen.
- [Python](http://www.python.org/) v2.7.5+ ([doc](http://www.python.org/doc/)) als Programmiersprache zur Datenmanipulation.
- [PostgreSQL](http://www.postgresql.org/) v9.3.2 ([doc](http://www.postgresql.org/docs/9.3/static/index.html)) als relationale Datenbank.
- [PostGIS](http://postgis.org/) v2.1.1 ([doc](http://postgis.net/docs/manual-2.1/)) als räumliche Erweiterung für PostgreSQL.
- [pgRouting](http://pgrouting.org/) v2.0.0 ([doc](http://pgrouting.org/documentation.html)) als Routing-Erweiterung für PostgreSQL.
- [Graphviz](http://www.graphviz.org/) v2.26.3 ([doc](http://www.graphviz.org/Documentation.php)) zum Zeichnen von Graphen.
- [Git]() und [GitHub]() zur Versionierung der Daten, der Dokumentation und des Quellcodes

**Verwendete Datensets**

Am besten via Shell Script runterladen:
```
sh code/shell/fetch-data.sh
```



## Aufbau Skriptum

**Aufgaben / Tutorials**
* Ziel des Tutorials, der Aufgabe anführen.
* Verwendete Software angeben.
* Schritte auflisten
* Conclusio
* Darauf folgende übliche Schritte -> verweis auf andere Tutorials
* Weitere Quellen

**README**
Titel
Kurze Beschreibung
Verwendete Software und Daten.
Lizenz
Kurze Beschreibung der einzelnen Tutorials / Aufgaben
ToDo

**DEVELOP**
Alle Dokumentations Files und deren Struktur

### 1. Grundlagen
- Graphentheorie: Einführung in die Graphentheorie, dem mathematisch, statistischen Unterbau der Netzwerkanalyse
- Spezielles eingehen auf Verkehr & Transport
- Probleme lösen: Was mache ich, wenn ich nicht mehr weiter komme oder einen Fehler gefunden habe?
- Tools: Software und Dateiformate, die in dieser Einführung verwendet werden.

### 2. Datensets erstellen und aufbereiten
- Erstellen eines eigenen Graphen
- Importieren und aufbereiten von Daten aus OpenStreetMap
- Importieren und aufbereiten von Daten aus dem OGD Portal der Stadt Wien

### 3. Netzwerkanalyse (Verkehr)
- Erklärung von Tools zur Netzwerkanalyse
- Durchführen der Shortest Path, Closest Facility und Service Area Netzwerkanalyse

### 4. Quellen
http://openscienceasap.org/education/courses/se-networks/

