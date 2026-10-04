---
title: "GisFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos GIS. Incluye los siguientes tipos de archivo Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /es/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Define documentos GIS. Incluye los siguientes tipos de archivo: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GisFileType](gisfiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | La Geodatabase de archivos ESRI (FileGDB) es una colección de archivos en una carpeta del disco que contiene datos geoespaciales relacionados, como conjuntos de datos de entidades, clases de entidades y tablas asociadas. Requiere que ciertos otros archivos se mantengan junto al archivo .gdb en el mismo directorio para que funcione. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON es un formato basado en JSON diseñado para representar las características geográficas con sus atributos no espaciales. Este formato define diferentes objetos JSON (JavaScript Object Notation) y su forma de unión. El formato JSON representa información colectiva sobre las características geográficas, sus extensiones espaciales y propiedades. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence es un flujo de registros GeoJSON independientes en lugar de un documento único que los englobe, cada registro delimitado por una nueva línea o por el carácter de control RS. Se utiliza para fuentes que se van añadiendo con el tiempo, donde el final de la colección no se conoce cuando comienza la escritura. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML significa Geography Markup Language y se basa en especificaciones XML desarrolladas por el Open Geospatial Consortium (OGC). El formato se utiliza para almacenar características de datos geográficos para el intercambio entre diferentes formatos de archivo. Sirve como lenguaje de modelado para sistemas geográficos, así como como un formato de intercambio abierto para transacciones geográficas en internet. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Los archivos con extensión GPX representan el formato GPS Exchange para el intercambio de datos GPS entre aplicaciones y servicios web en internet. Es un formato de archivo XML ligero que contiene datos GPS, es decir, puntos de referencia, rutas y rastros, que pueden ser importados y leídos por múltiples programas. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) contiene información geoespacial en notación XML. Los archivos guardados como KML pueden abrirse en aplicaciones de Sistema de Información Geográfica (GIS) siempre que las soporten. Muchas aplicaciones han comenzado a ofrecer soporte para el formato de archivo KML después de que se adoptara como estándar internacional. KML utiliza una estructura basada en etiquetas con elementos y atributos anidados. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ es un archivo ZIP que lleva un documento KML, por convención llamado doc.kml en la raíz del archivo, junto con cualquier recurso al que el documento haga referencia. Comprimir el marcado es el objetivo: una fuente KML de cualquier tamaño se reduce drásticamente, por lo que los editores distribuyen KMZ en lugar de KML. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | El formato de archivo OSM es un formato de datos estructurado utilizado para almacenar datos geográficos en el proyecto OpenStreetMap. Los archivos OSM suelen estar en formato XML y contienen información como la ubicación de carreteras, edificios, puntos de interés y otras características del mapa. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP es la extensión de archivo para uno de los tipos principales de archivos utilizados para la representación de ESRI Shapefile. Representa información geoespacial en forma de datos vectoriales para ser utilizada por aplicaciones de Sistemas de Información Geográfica (GIS). Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON es una extensión de GeoJSON que codifica topología. En lugar de representar geometrías de forma discreta, las geometrías en los archivos TopoJSON se ensamblan a partir de segmentos de línea compartidos llamados arcos. |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
