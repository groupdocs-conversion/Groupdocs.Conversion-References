---
title: "Clase GisFileType"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Las definiciones de tipos de documentos GIS."
type: docs
url: /es/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

Las definiciones de tipos de documentos GIS.

Incluye los siguientes tipos de archivo: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

El tipo GisFileType expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Inicializa un GisFileType para serialización. |

### Métodos
| Método | Descripción |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Compara el objeto actual con otro. (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementa la comparación de igualdad definida por [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Obtiene el FileType para la extensión de archivo proporcionada. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Devuelve el FileType para el file_name especificado. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Devuelve el FileType para el flujo de documento proporcionado. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Proporciona la función hash predeterminada. (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Representación en cadena del tipo de archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La descripción del tipo de archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | La extensión del archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La familia del archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | El formato del archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP es la extensión de archivo para uno de los tipos de archivo principales utilizados para la representación de ESRI Shapefile. Representa información geoespacial en forma de datos vectoriales para ser utilizada por aplicaciones de Sistemas de Información Geográfica (GIS). Aprende más sobre este formato de archivo aquí. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON es un formato basado en JSON diseñado para representar las características geográficas con sus atributos no espaciales. Este formato define diferentes objetos JSON (JavaScript Object Notation) y su forma de unión. El formato JSON representa información colectiva sobre las características geográficas, sus extensiones espaciales y propiedades. Aprende más sobre este formato de archivo aquí. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | Geodatabase de archivo ESRI (FileGDB) es una colección de archivos en una carpeta en disco que contiene datos geoespaciales relacionados, como conjuntos de datos de entidades, clases de entidades y tablas asociadas. Requiere que ciertos otros archivos se mantengan junto al archivo .gdb en el mismo directorio para que funcione. Aprende más sobre este formato de archivo aquí. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML significa Geography Markup Language y se basa en especificaciones XML desarrolladas por el Open Geospatial Consortium (OGC). El formato se utiliza para almacenar características de datos geográficos para el intercambio entre diferentes formatos de archivo. Sirve como lenguaje de modelado para sistemas geográficos, así como un formato de intercambio abierto para transacciones geográficas en internet. Aprende más sobre este formato de archivo aquí. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) contiene información geoespacial en notación XML. Los archivos guardados como KML pueden abrirse en aplicaciones de Sistemas de Información Geográfica (GIS) siempre que las soporten. Muchas aplicaciones han comenzado a ofrecer soporte para el formato de archivo KML después de que se adoptara como estándar internacional. KML utiliza una estructura basada en etiquetas con elementos y atributos anidados. Obtenga más información sobre este formato de archivo aquí. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | Los archivos con extensión GPX representan el formato GPS Exchange para el intercambio de datos GPS entre aplicaciones y servicios web en internet. Es un formato de archivo XML liviano que contiene datos GPS, es decir, puntos de referencia, rutas y rastros que pueden ser importados y leídos por múltiples programas. Obtenga más información sobre este formato de archivo aquí. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON es una extensión de GeoJSON que codifica topología. En lugar de representar geometrías de forma discreta, las geometrías en archivos TopoJSON se ensamblan a partir de segmentos de línea compartidos llamados arcos. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | El formato de archivo OSM es un formato de datos estructurado utilizado para almacenar datos geográficos en el proyecto OpenStreetMap. Los archivos OSM suelen estar en formato XML y contienen información como la ubicación de carreteras, edificios, puntos de interés y otras características del mapa. Obtenga más información sobre este formato de archivo aquí. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo de archivo desconocido (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ver también
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
