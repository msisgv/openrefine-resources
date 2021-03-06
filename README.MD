# OpenRefine Ressourcen

OpenRefine ist eine Open-Source-Applikation für Datenbereinigung bzw. -transformation. Es erlaubt das Einlesen  von Daten im CSV/TSV, XML, RDF, JSON und Google Spreadsheets Format. 

Datentransformationsschritte werden mittels Skripte durchgeführt, welche in [GREL (General Refine Expression Language)](https://github.com/OpenRefine/OpenRefine/wiki/General-Refine-Expression-Language), [Python](https://www.python.org/)/[Jython](https://www.jython.org/) oder [Clojure](https://clojure.org/) verfasst werden können.  

[OpenRefine Website und Dokumentation](https://openrefine.org/)

OpenRefine ist auch ein nützliches Tool zum Abgleich bzw. Matching von Daten. Über Reconciliation-Schnittstellen können Werte in Datenfeldern mit Einträgen in externen Datenbanken/Wissensbasen verknüpft werden (sofern eine entsprechende API implementiert wurde). Standardmäßig ist in OpenRefine der Reconciliation-Dienst für [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) inkludiert, es existieren aber auch Schnittstellen für weitere wichtige Normdatensätze wie [VIAF](http://viaf.org/) oder [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html), welche ohne großen Aufwand hinzugefügt werden können. 

[Reconciliation API Spezifikation](https://reconciliation-api.github.io/specs/0.1/)



## Tutorials

### Carpentry Kurse
* [OpenRefine for Social Science](https://datacarpentry.org/openrefine-socialsci/)
* [Library Carpentry: OpenRefine](https://librarycarpentry.org/lc-open-refine/)

### Datenanreicherung
 * [Enriching reconciled data with OpenRefine](https://medium.com/the-bytegeist-blog/enriching-reconciled-data-with-openrefine-89b885dcadbb)
 

### Reconciliation Service 
* [Reconciling](https://histhub.ch/reconciling/)
* [Reconciling von Geodaten](https://histhub.ch/usecase-reconciling-von-geodaten/)
* [Using OpenRefine to reconcile named entities](https://mnylc.org/fellows/2017/03/17/using-openrefine-to-reconcile-name-entities/)
* [Reconciling mit GND Daten](http://blog.lobid.org/2018/08/27/openrefine.html)


## Reconsiliation Endpoints

* List of Reconciliation endpoints - http://okfnlabs.org/reconcile-csv/
* Wikidata - https://tools.wmflabs.org/openrefine-wikidata/
* GND - http://blog.lobid.org/2019/08/19/openrefine.html
* VIAF - http://refine.codefork.com/reconcile/viaf - http://refine.codefork.com/



## License

CC-0

## Verfasser

[kompetenzwerkd@saw-leipzig.de](kompetenzwerkd@saw-leipzig.de)
