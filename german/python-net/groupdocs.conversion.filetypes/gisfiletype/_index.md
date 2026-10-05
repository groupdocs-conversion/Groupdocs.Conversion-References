---
title: "GisFileType Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die GIS‑Dokumenttypdefinitionen."
type: docs
url: /de/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

Die GIS‑Dokumenttypdefinitionen.

Enthält die folgenden Dateitypen: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

Der GisFileType-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Initialisiert einen GisFileType für die Serialisierung. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Vergleicht das aktuelle Objekt mit einem anderen. (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementiert den Gleichheitsvergleich, der von [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) definiert wird. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Ermittelt den FileType für die angegebene Dateierweiterung. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Gibt den FileType für den angegebenen file_name zurück. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Gibt den FileType für den bereitgestellten Dokumenten-Stream zurück. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Stellt die Standard‑Hash‑Funktion bereit. (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | String-Darstellung des Dateityps. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Die Dateityp-Beschreibung. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Die Dateierweiterung. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Die Dateifamilie. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Das Dateiformat. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP ist die Dateierweiterung für einen der primären Dateitypen, die zur Darstellung von ESRI Shapefile verwendet werden. Sie stellt geodatenbasierte Informationen in Form von Vektordaten dar, die von Geographic Information Systems (GIS)-Anwendungen genutzt werden. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON ist ein auf JSON basierendes Format, das dazu dient, geografische Merkmale mit ihren nicht‑räumlichen Attributen darzustellen. Dieses Format definiert verschiedene JSON (JavaScript Object Notation)-Objekte und deren Verknüpfungsweise. Das JSON-Format enthält zusammengefasste Informationen über die geografischen Merkmale, deren räumliche Ausdehnungen und Eigenschaften. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | Die ESRI-Dateigeodatenbank (FileGDB) ist eine Sammlung von Dateien in einem Ordner auf der Festplatte, die zusammengehörige Geodaten wie Feature-Datasets, Feature-Klassen und zugehörige Tabellen enthalten. Damit sie funktioniert, müssen bestimmte weitere Dateien zusammen mit der .gdb‑Datei im selben Verzeichnis aufbewahrt werden. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML steht für Geography Markup Language und basiert auf XML‑Spezifikationen, die vom Open Geospatial Consortium (OGC) entwickelt wurden. Das Format wird verwendet, um geografische Datenfeatures zum Austausch zwischen verschiedenen Dateiformaten zu speichern. Es dient sowohl als Modellierungssprache für geografische Systeme als auch als offenes Austauschformat für geografische Transaktionen im Internet. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) enthält geodatenbasierte Informationen in XML‑Notation. Als KML gespeicherte Dateien können in Geographic Information System (GIS)-Anwendungen geöffnet werden, sofern diese sie unterstützen. Viele Anwendungen haben begonnen, das KML‑Dateiformat zu unterstützen, nachdem es zum internationalen Standard erklärt wurde. KML verwendet eine tagbasierte Struktur mit verschachtelten Elementen und Attributen. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | Dateien mit der GPX‑Erweiterung stellen das GPS Exchange Format zum Austausch von GPS‑Daten zwischen Anwendungen und Webdiensten im Internet dar. Es ist ein leichtgewichtiges XML‑Dateiformat, das GPS‑Daten wie Wegpunkte, Routen und Tracks enthält, die von mehreren Programmen importiert und gelesen werden können. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON ist eine Erweiterung von GeoJSON, die Topologie kodiert. Anstatt Geometrien einzeln darzustellen, werden Geometrien in TopoJSON-Dateien aus gemeinsamen Liniensegmenten, sogenannten Bögen, zusammengesetzt. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | Das OSM-Dateiformat ist ein strukturiertes Datenformat, das zur Speicherung geografischer Daten im OpenStreetMap-Projekt verwendet wird. OSM-Dateien liegen typischerweise im XML-Format vor und enthalten Informationen wie die Lage von Straßen, Gebäuden, Interessenspunkten und anderen Merkmalen auf der Karte. Erfahren Sie hier mehr über dieses Dateiformat. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unbekannter Dateityp (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Siehe auch
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
