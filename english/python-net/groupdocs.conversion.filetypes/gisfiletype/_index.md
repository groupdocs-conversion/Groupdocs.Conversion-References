---
title: GisFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
---

## GisFileType class

Defines GIS documents. Includes the following file types:
[`GisFileType.Shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.GeoJson`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.Gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.Gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.Kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.Gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.TopoJson`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).
[`GisFileType.Osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype).



**Inheritance:** [`GisFileType`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The GisFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/unknown) | Unknown file type |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp) | SHP is the file extension for one of the primary file types used for representation of ESRI Shapefile. It represents Geospatial information in the form of vector data to be used by Geographic Information Systems (GIS) applications. <br/>Learn more about this file format [here](https://docs.fileformat.com/gis/shp/). |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json) | GeoJSON is a JSON based format designed to represent the geographical features with their non-spatial attributes. This format defines different JSON (JavaScript Object Notation) objects and their joining fashion. JSON format represents a collective information about the Geographical features, their spatial extents, and properties. <br/>Learn more about this file format [here](https://docs.fileformat.com/gis/geojson/). |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI file Geodatabase (FileGDB) is a collection of files in a folder on disc that hold related geospatial data such as feature datasets, feature classes and associated tables. It requires certain other files to be kept alongside the .gdb file in the same directory for it to work. <br/>Learn more about this file format [here](https://docs.fileformat.com/database/gdb/). |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml) | GML stands for Geography Markup Language that is based on XML specifications developed by the Open Geospatial Consortium (OGC). The format is used to store geographic data features for interchange among different file formats. It serves as a modeling language for geographic systems as well as an open interchange format for geographic transactions on the internet.<br/>Learn more about this file format [here](https://docs.fileformat.com/gis/gml/). |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) contains geospatial information in XML notation. Files saved as KML can be opened in Geographic Information System (GIS) applications provided they support it. Many applications have started providing support for KML file format after it has been adopted as international standard. KML uses a tag-based structure with nested elements and attributes.<br/>Learn more about this file format [here](https://docs.fileformat.com/gis/kml/). |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx) | Files with GPX extension represent GPS Exchange format for interchange of GPS data between applications and web services on the internet. It is a light-weight XML file format that contains GPS data i.e. waypoints, routes and tracks to be imported and red by multiple programs. <br/>Learn more about this file format [here](https://docs.fileformat.com/gis/gpx/). |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json) | TopoJSON is an extension of GeoJSON that encodes topology. Rather than representing geometries discretely, geometries in TopoJSON files are stitched together from shared line segments called arcs. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm) | The OSM file format is a structured data format used to store geographical data in the OpenStreetMap project. OSM files are typically in XML format and contain information such as the location of roads, buildings, points of interest, and other features on the map.<br/>Learn more about this file format [here](https://docs.fileformat.com/gis/osm/). |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/compare_to/#any) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/from_filename/#str) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/from_extension/#str) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
* class [`GisFileType`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype)
