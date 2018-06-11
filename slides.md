# Einführung & Motivation

## Was ist WikiCite?

* Freie bibliographische Datenbank in Wikidata
    * Bibliographische Metadaten
      * selbstständige + unselbständige Werke
    * Zitationsdaten
    * Kollaborative Katalogisierung (Social Cataloging)
    * offene Daten (CC0)


## Umfang

* **Publikationen**: 19 Millionen Wikidata-Einträgen
* **Zitationen**: 46 Millionen Zitationen in Wikidata

<!--2,3 Mio Medieneinheiten UB Mannheim-->
<!--BASE hat 127 Mio-->

<!--39% von Wikidata-Einträgen insgesamt sind Publikationen, 10% aller Aussagen in Wikidata sind Zitationen -->

[![WikiCite Statistik](img/wikicite-stats-annotated.png){height=70%}](http://wikicite.org/statistics.html)


## Motivation für Wikipedia

* Aussagen mit Belegen versehen, z. B.

![](img/Wikipedia-Belege.png)

\centering

![](img/Wikipedia-Belege-Fussnoten.png){height=40%}

* Bibl. Metadaten zentral für alle Artikel und Sprachversionen


## Motivation für Wikidata

* Fakten in Wikidata mit Fundstellen belegen,\
z.&nbsp;B. höchster Punkt in Berlin

[![](img/fundstelle-wikidata-berlin.jpg)](https://www.wikidata.org/wiki/Q64#P610)


<!--
## Motivation für bibliometrische Auswertungen

* Auswertung und Visualisierung von Zitationsdaten

[![](img/Scholia-Koautorengraph-Zika-Korpus.jpg)](https://tools.wmflabs.org/scholia/topic/Q202864#Co-author%20graph)

-->

## Motivation für bibliometrische Auswertungen

* Auswertung und Visualisierung von Publikationsdaten

[![](img/scholia-organization-example.png){height=70%}](https://tools.wmflabs.org/scholia/organization/Q1269766#Page%20production)

\tiny _Abb. Screenshot von Scholia zur Anzahl produzierter Seiten von Publikationen mit Autoren der DTU_


## Motivation für bibliometrische Auswertungen

* Auswertung und Visualisierung von Zitationsdaten

[![](img/scholia-citation-graph.png)](https://tools.wmflabs.org/scholia/work/Q24314690)


# Umsetzung von WikiCite

---

![](img/wikicite-annotated-item-de.png){width=95%}


## Wikidata-Datenmodell

* Item-Identifier 
    - [Q30000000](http://www.wikidata.org/entity/Q30000000)
* Eigenschaften
    - P31 *ist ein(e) / instance of / est ...*
    - P50 *Autor / author / scriptor ...*
    - ...
* Datenmodell ist dynamisch
    * Neue Eigenschaften vorschlagen + diskutieren
    * Fragen und Diskussion auf spezifischen Projektseiten\
      *[Metadata](https://www.wikidata.org/wiki/Wikidata:WikiProject_Source_MetaData),
      [Books](https://www.wikidata.org/wiki/Wikidata:WikiProject_Books),
      [Periodicals](https://www.wikidata.org/wiki/Wikidata:WikiProject_Periodicals)...*


## Tools zur Bearbeitung

Direkte Bearbeitung auf Wikidata oder...

* **sourceMD/fatameh** Import anhand DOI/PMID
* **zotkat** Import aus Zotero (Literaturverwaltung)
* **Mix'n'Match:** Abgleich mit externen Identifikatoren
* **OpenRefine 3.0** mit erweiterter Wikidata-Anbindung
* ...


## Qualitätssicherung

* Eigene Beobachtungsliste für Wikidata-Einträge\
  mit Benachrichtigung bei Änderungen

* Einschränkungen von Werten von Eigenschaften
    * *ISBN* (P212/P957) folgen bestimmten Mustern
    * *Autoren* (P50) müssen Personen oder Organisation sein

* Regelverletzungen werden protokolliert (constraint reports)\
  und können dann verbessert werden

* bottom-up


## Normdaten-Verlinkung 

* Wikidata ist selbst eine universelle Normdatei

* Verknüpfungen mit externen Einträgen
    * DOI, ISBN, PMID, arXiv-ID, ... (Publikationen)
    * GND, VIAF, ORCID, dblp-ID, ... (Autoren...)
    * ...

* 2824 von 4741 Wikidata-Eigenschaften dienen der\
  Verlinkung mit anderen Datenbanken


## Abfragemöglichkeiten

* <https://query.wikidata.org/> (SPARQL-Editor)

* Beispielabfragen
    * Bücher zusammen von Elter(n) und Kinder(n) geschrieben: <http://tinyurl.com/y7oe8uo8>
    * Autoren, deren Werke 2018 gemeinfrei wurden: <http://tinyurl.com/yc8v6l9c>
    * Meist zitierte Wissenschaftlerinnen: <http://tinyurl.com/y8ell8nw>

* Hilfreich zur Qualitätssicherung


# Perspektiven für Bibliotheken

## Nachnutzung von Daten aus Wikidata

* Kataloganreicherungen bei Normdaten
* mehrsprachige Suche nach Schlagwörtern
* Artikelindex für Discovery aus Wikidata?
* Kataloganreicherungen mit offenen Zitationsdaten?


## Ideen für Katalogisierungstools

* Können Ansätze zum Datenerfassen in Wikidata auch für die Katalogisierung
  in Bibliotheken übernommen werden?
* Sind nicht auch stärker Tools für Batch-Bearbeitungen gefragt?
* Was ist mit Kontroll- und Prüftools?


## Umfang der Katalogisierung

* Aufsatzkatalogisierung
    * Thema für Bibliotheken? FIDs?
    * WikiCite zeigt auf, dass es möglich ist.
* Katalogisierung von Zitationen
    * Können Bibliotheken zu offenen Zitationsdaten beitragen?
    * Zitationsdaten in Verbundkatalog speichern?
    * Linked Open Citation Database (LOC-DB): [Clip](https://www.youtube.com/watch?v=k8ST-bX4BKs)


# Fragen / Diskussion / Antworten ?

