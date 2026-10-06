---
title: "Classe GisFileType"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Le definizioni dei tipi di documento GIS."
type: docs
url: /it/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

Le definizioni dei tipi di documento GIS.

Include i seguenti tipi di file: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

Il tipo GisFileType espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Inizializza un GisFileType per la serializzazione. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Confronta l'oggetto corrente con un altro. (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementa il confronto di uguaglianza definito da [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (ereditato da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Ottiene il FileType per l'estensione di file fornita. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Restituisce il FileType per il file_name specificato. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Restituisce il FileType per lo stream di documento fornito. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Fornisce la funzione hash predefinita. (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Rappresentazione stringa del tipo di file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La descrizione del tipo di file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | L'estensione del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La famiglia del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Il formato del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP è l'estensione file per uno dei principali tipi di file usati per la rappresentazione di ESRI Shapefile. Rappresenta informazioni geospaziali sotto forma di dati vettoriali da utilizzare nelle applicazioni Geographic Information Systems (GIS). Scopri di più su questo formato di file qui. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON è un formato basato su JSON progettato per rappresentare le caratteristiche geografiche con i loro attributi non spaziali. Questo formato definisce diversi oggetti JSON (JavaScript Object Notation) e il loro modo di collegamento. Il formato JSON rappresenta informazioni collettive sulle caratteristiche geografiche, le loro estensioni spaziali e le proprietà. Scopri di più su questo formato di file qui. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | Il Geodatabase di file ESRI (FileGDB) è una raccolta di file in una cartella su disco che contiene dati geospaziali correlati, come dataset di feature, classi di feature e tabelle associate. Richiede che alcuni altri file siano mantenuti accanto al file .gdb nella stessa directory affinché funzioni. Scopri di più su questo formato di file qui. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML sta per Geography Markup Language, basato su specifiche XML sviluppate dall'Open Geospatial Consortium (OGC). Il formato è usato per memorizzare caratteristiche di dati geografici per lo scambio tra diversi formati di file. Serve sia come linguaggio di modellazione per sistemi geografici sia come formato di scambio aperto per transazioni geografiche su Internet. Scopri di più su questo formato di file qui. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) contiene informazioni geospaziali in notazione XML. I file salvati come KML possono essere aperti in applicazioni Geographic Information System (GIS) a condizione che le supportino. Molte applicazioni hanno iniziato a fornire supporto per il formato file KML dopo che è stato adottato come standard internazionale. KML utilizza una struttura basata su tag con elementi e attributi nidificati. Scopri di più su questo formato di file qui. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | I file con estensione GPX rappresentano il formato GPS Exchange per lo scambio di dati GPS tra applicazioni e servizi web su Internet. È un formato file XML leggero che contiene dati GPS, cioè waypoint, percorsi e tracce, da importare e leggere da più programmi. Scopri di più su questo formato di file qui. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON è un'estensione di GeoJSON che codifica la topologia. Invece di rappresentare le geometrie in modo discreto, le geometrie nei file TopoJSON sono unite da segmenti di linea condivisi chiamati archi. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | Il formato file OSM è un formato dati strutturato usato per memorizzare dati geografici nel progetto OpenStreetMap. I file OSM sono tipicamente in formato XML e contengono informazioni come la posizione di strade, edifici, punti di interesse e altre caratteristiche sulla mappa. Scopri di più su questo formato di file qui. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo di file sconosciuto (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Vedi anche
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
