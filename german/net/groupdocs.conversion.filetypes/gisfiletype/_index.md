---
title: "GisFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert GIS‑Dokumente. Enthält die folgenden Dateitypen Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /de/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Definiert GIS‑Dokumente. Enthält die folgenden Dateitypen: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GisFileType](gisfiletype)() | Serialisierungskonstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dateitypbeschreibung |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Die Dateierweiterung |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Die Dateifamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Das Dateiformat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergleicht das aktuelle Objekt mit einem anderen. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementiert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hashfunktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String-Darstellung |

## Fields

| Name | Beschreibung |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | Die ESRI-Dateigeodatenbank (FileGDB) ist eine Sammlung von Dateien in einem Ordner auf der Festplatte, die zusammengehörige geodatenbezogene Daten wie Feature-Datensätze, Feature-Klassen und zugehörige Tabellen enthalten. Sie erfordert, dass bestimmte weitere Dateien neben der .gdb-Datei im selben Verzeichnis aufbewahrt werden, damit sie funktioniert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON ist ein auf JSON basierendes Format, das entwickelt wurde, um geografische Merkmale mit ihren nicht‑räumlichen Attributen darzustellen. Dieses Format definiert verschiedene JSON (JavaScript Object Notation)-Objekte und deren Verknüpfungsweise. Das JSON‑Format liefert zusammengefasste Informationen über die geografischen Merkmale, ihre räumlichen Ausdehnungen und Eigenschaften. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence ist ein Strom unabhängiger GeoJSON‑Datensätze statt eines einzigen umschließenden Dokuments, wobei jeder Datensatz durch einen Zeilenumbruch oder das RS‑Steuerzeichen abgegrenzt wird. Es wird für Feeds verwendet, die im Laufe der Zeit erweitert werden, wobei das Ende der Sammlung beim Beginn des Schreibens nicht bekannt ist. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML steht für Geography Markup Language und basiert auf XML‑Spezifikationen, die vom Open Geospatial Consortium (OGC) entwickelt wurden. Das Format wird verwendet, um geografische Datenmerkmale zum Austausch zwischen verschiedenen Dateiformaten zu speichern. Es dient sowohl als Modellierungssprache für geografische Systeme als auch als offenes Austauschformat für geografische Transaktionen im Internet. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Dateien mit der GPX‑Erweiterung stellen das GPS‑Exchange‑Format für den Austausch von GPS‑Daten zwischen Anwendungen und Webdiensten im Internet dar. Es ist ein leichtgewichtiges XML‑Dateiformat, das GPS‑Daten wie Wegpunkte, Routen und Tracks enthält, die von mehreren Programmen importiert und gelesen werden können. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) enthält geodatenbezogene Informationen in XML‑Notation. Als KML gespeicherte Dateien können in Geographic Information System (GIS)-Anwendungen geöffnet werden, sofern diese das Format unterstützen. Viele Anwendungen haben begonnen, das KML‑Dateiformat zu unterstützen, nachdem es als internationaler Standard anerkannt wurde. KML verwendet eine tagbasierte Struktur mit verschachtelten Elementen und Attributen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ ist ein ZIP‑Archiv, das ein KML‑Dokument enthält, das per Konvention im Archivstamm als doc.kml benannt ist, zusammen mit allen Ressourcen, auf die das Dokument verweist. Der Sinn liegt im Komprimieren des Markups: ein KML‑Feed beliebiger Größe schrumpft erheblich, weshalb Verlage KMZ statt KML verbreiten. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Das OSM-Dateiformat ist ein strukturiertes Datenformat, das zur Speicherung geografischer Daten im OpenStreetMap-Projekt verwendet wird. OSM-Dateien liegen typischerweise im XML-Format vor und enthalten Informationen wie die Lage von Straßen, Gebäuden, Sehenswürdigkeiten und anderen Merkmalen auf der Karte. Erfahren Sie mehr über dieses Dateiformat [here](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP ist die Dateierweiterung für einen der primären Dateitypen, die zur Darstellung von ESRI Shapefile verwendet werden. Es repräsentiert geospatiale Informationen in Form von Vektordaten, die von Geographic Information Systems (GIS)-Anwendungen genutzt werden. Erfahren Sie mehr über dieses Dateiformat [here](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON ist eine Erweiterung von GeoJSON, die Topologie kodiert. Anstatt Geometrien einzeln darzustellen, werden Geometrien in TopoJSON-Dateien aus gemeinsamen Liniensegmenten, den sogenannten Bögen, zusammengefügt. |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
