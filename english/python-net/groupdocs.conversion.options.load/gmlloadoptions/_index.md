---
title: GmlLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/gmlloadoptions/
is_root: false
weight: 170
---

## GmlLoadOptions class

Options for loading Gml documents.



**Inheritance:** [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions) → 
[`GisLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gisloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The GmlLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/__init__/#) | Initializes new instance of [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/format) | Input document file type. |
| [width](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/width) | Sets desired page width for converting GIS document. Default is 1000. |
| [height](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/height) | Sets desired page height for converting GIS document. Default is 1000. |
| [schema_location](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location) | Space separated list of URI pairs. First URI in every pair is a URI of the namespace, second URI is a Path to XML schema of the namespace. If set to null, Conversion will try read schemaLocation from the root element of the document. Default is null |
| [restore_schema](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/restore_schema) | Determines whether Conversion is allowed to parse attributes in a Gml file in which an XML schema is missing or cannot be loaded. If set to true, Conversion reader does not require the presence of an XML Schema. Default is false. |
| [load_schemas_from_internet](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/load_schemas_from_internet) | Determines whether Conversion is allowed to load XML schema from Internet. If set to false, schemas with absolute URIs that does not start with ‘file://’ would not be loaded. Default is false. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`GisLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gisloadoptions)
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
