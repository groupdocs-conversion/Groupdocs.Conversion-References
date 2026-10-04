---
title: "GisFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i documenti GIS. Include i seguenti tipi di file Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /it/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Definisce i documenti GIS. Include i seguenti tipi di file: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [GisFileType](gisfiletype)() | Costruttore di serializzazione |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia del file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione stringa |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | Il Geodatabase di file ESRI (FileGDB) è una raccolta di file in una cartella su disco che contiene dati geospaziali correlati, come dataset di feature, classi di feature e tabelle associate. Richiede che alcuni altri file siano mantenuti accanto al file .gdb nella stessa directory affinché funzioni. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON è un formato basato su JSON progettato per rappresentare le caratteristiche geografiche con i loro attributi non spaziali. Questo formato definisce diversi oggetti JSON (JavaScript Object Notation) e il loro modo di collegamento. Il formato JSON rappresenta informazioni collettive sulle caratteristiche geografiche, le loro estensioni spaziali e le proprietà. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence è un flusso di record GeoJSON indipendenti anziché un unico documento racchiuso, ogni record delimitato da una nuova riga o dal carattere di controllo RS. Viene utilizzato per feed a cui si aggiungono dati nel tempo, dove la fine della collezione non è nota all'inizio della scrittura. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML sta per Geography Markup Language ed è basato su specifiche XML sviluppate dall'Open Geospatial Consortium (OGC). Il formato è usato per memorizzare le caratteristiche dei dati geografici per lo scambio tra diversi formati di file. Funziona sia come linguaggio di modellazione per sistemi geografici sia come formato di scambio aperto per transazioni geografiche su Internet. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | I file con estensione GPX rappresentano il formato GPS Exchange per lo scambio di dati GPS tra applicazioni e servizi web su Internet. È un formato di file XML leggero che contiene dati GPS, ovvero waypoint, percorsi e tracce, da importare e leggere da più programmi. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) contiene informazioni geospaziali in notazione XML. I file salvati come KML possono essere aperti in applicazioni Geographic Information System (GIS) a condizione che le supportino. Molte applicazioni hanno iniziato a fornire supporto per il formato di file KML dopo che è stato adottato come standard internazionale. KML utilizza una struttura basata su tag con elementi e attributi annidati. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ è un archivio ZIP che contiene un documento KML, per convenzione denominato doc.kml nella radice dell'archivio, insieme a tutte le risorse a cui il documento fa riferimento. Comprimere il markup è lo scopo: un feed KML di qualsiasi dimensione si riduce drasticamente, motivo per cui gli editori distribuiscono KMZ anziché KML. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Il formato di file OSM è un formato di dati strutturato utilizzato per memorizzare dati geografici nel progetto OpenStreetMap. I file OSM sono tipicamente in formato XML e contengono informazioni come la posizione di strade, edifici, punti di interesse e altre caratteristiche sulla mappa. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP è l'estensione di file per uno dei principali tipi di file utilizzati per la rappresentazione di ESRI Shapefile. Rappresenta informazioni geospaziali sotto forma di dati vettoriali da utilizzare nelle applicazioni Geographic Information Systems (GIS). Scopri di più su questo formato di file [qui](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON è un'estensione di GeoJSON che codifica la topologia. Invece di rappresentare le geometrie in modo discreto, le geometrie nei file TopoJSON sono unite da segmenti di linea condivisi chiamati archi. |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
