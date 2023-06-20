---
title: GisFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines GIS documents. Includes the following file types Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm.
type: docs
weight: 870
url: /net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Defines GIS documents. Includes the following file types: [`Shp`](./shp). [`GeoJson`](./geojson). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [GisFileType](gisfiletype)() | Serialization constructor |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determines whether two object instances are equal. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI file Geodatabase (FileGDB) is a collection of files in a folder on disc that hold related geospatial data such as feature datasets, feature classes and associated tables. It requires certain other files to be kept alongside the .gdb file in the same directory for it to work. Learn more about this file format [here](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON is a JSON based format designed to represent the geographical features with their non-spatial attributes. This format defines different JSON (JavaScript Object Notation) objects and their joining fashion. JSON format represents a collective information about the Geographical features, their spatial extents, and properties. Learn more about this file format [here](https://docs.fileformat.com/gis/geojson/). |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML stands for Geography Markup Language that is based on XML specifications developed by the Open Geospatial Consortium (OGC). The format is used to store geographic data features for interchange among different file formats. It serves as a modeling language for geographic systems as well as an open interchange format for geographic transactions on the internet. Learn more about this file format [here](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Files with GPX extension represent GPS Exchange format for interchange of GPS data between applications and web services on the internet. It is a light-weight XML file format that contains GPS data i.e. waypoints, routes and tracks to be imported and red by multiple programs. Learn more about this file format [here](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) contains geospatial information in XML notation. Files saved as KML can be opened in Geographic Information System (GIS) applications provided they support it. Many applications have started providing support for KML file format after it has been adopted as international standard. KML uses a tag-based structure with nested elements and attributes. Learn more about this file format [here](https://docs.fileformat.com/gis/kml/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | The OSM file format is a structured data format used to store geographical data in the OpenStreetMap project. OSM files are typically in XML format and contain information such as the location of roads, buildings, points of interest, and other features on the map. Learn more about this file format [here](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP is the file extension for one of the primary file types used for representation of ESRI Shapefile. It represents Geospatial information in the form of vector data to be used by Geographic Information Systems (GIS) applications. Learn more about this file format [here](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON is an extension of GeoJSON that encodes topology. Rather than representing geometries discretely, geometries in TopoJSON files are stitched together from shared line segments called arcs. |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
