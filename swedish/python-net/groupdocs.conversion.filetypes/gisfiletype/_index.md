---
title: "GisFileType-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "GIS‑dokumenttypdefinitionerna."
type: docs
url: /sv/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

GIS‑dokumenttypdefinitionerna.

Inkluderar följande filtyper: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

GisFileType-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Initierar en GisFileType för serialisering. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Jämför aktuellt objekt med ett annat. (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementerar likhetsjämförelsen som definieras av [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Hämtar FileType för den angivna filändelsen. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Returnerar FileType för angivet file_name. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Returnerar FileType för angivet dokumentström. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Tillhandahåller standardhashfunktionen. (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Strängrepresentation av filtyp. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Filtypens beskrivning. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Filändelsen. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Filfamiljen. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Filformatet. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP är filändelsen för en av de primära filtyperna som används för representation av ESRI Shapefile. Den representerar geospatial information i form av vektordata som ska användas av geografiska informationssystem (GIS)-applikationer. Läs mer om detta filformat här. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON är ett JSON-baserat format utformat för att representera geografiska funktioner med deras icke-spatiala attribut. Detta format definierar olika JSON (JavaScript Object Notation)-objekt och deras sammanslagningsmetod. JSON-formatet representerar en samlad information om de geografiska funktionerna, deras rumsliga utbredning och egenskaper. Läs mer om detta filformat här. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | ESRI-fil Geodatabase (FileGDB) är en samling filer i en mapp på disk som innehåller relaterade geospatiala data såsom feature-dataset, feature-klasser och tillhörande tabeller. Den kräver att vissa andra filer hålls tillsammans med .gdb-filen i samma katalog för att fungera. Läs mer om detta filformat här. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML står för Geography Markup Language som är baserad på XML-specifikationer utvecklade av Open Geospatial Consortium (OGC). Formatet används för att lagra geografiska datafunktioner för utbyte mellan olika filformat. Det fungerar som ett modelleringsspråk för geografiska system samt ett öppet utbytesformat för geografiska transaktioner på internet. Läs mer om detta filformat här. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) innehåller geospatial information i XML-notation. Filer sparade som KML kan öppnas i geografiska informationssystem (GIS)-applikationer förutsatt att de stödjer det. Många applikationer har börjat erbjuda stöd för KML-filformatet efter att det antagits som internationell standard. KML använder en taggbaserad struktur med nästlade element och attribut. Läs mer om detta filformat här. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | Filer med GPX‑ändelse representerar GPS Exchange-format för utbyte av GPS-data mellan applikationer och webbtjänster på internet. Det är ett lättviktigt XML-filformat som innehåller GPS-data, dvs. waypoints, rutter och spår, som kan importeras och läsas av flera program. Läs mer om detta filformat här. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON är en utökning av GeoJSON som kodar topologi. Istället för att representera geometrier separat, sys geometrier i TopoJSON‑filer ihop från delade linjesegment som kallas arcs. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | OSM-filformatet är ett strukturerat dataformat som används för att lagra geografisk data i OpenStreetMap-projektet. OSM-filer är vanligtvis i XML-format och innehåller information såsom placeringen av vägar, byggnader, intressepunkter och andra funktioner på kartan. Läs mer om detta filformat här. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Okänd filtyp (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Se även
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
