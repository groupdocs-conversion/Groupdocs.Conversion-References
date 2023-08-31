---
title: GmlLoadOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for loading Gml documents.
type: docs
weight: 2090
url: /net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Options for loading Gml documents.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Initializes new instance of [`GmlLoadOptions`](../gmlloadoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Input document file type. (2 properties) |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Sets desired page height for converting GIS document. Default is 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Determines whether Conversion is allowed to load XML schema from Internet. If set to false, schemas with absolute URIs that does not start with ‘file://’ would not be loaded. Default is false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Determines whether Conversion is allowed to parse attributes in a Gml file in which an XML schema is missing or cannot be loaded. If set to true, Conversion reader does not require the presence of an XML Schema. Default is false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Space separated list of URI pairs. First URI in every pair is a URI of the namespace, second URI is a Path to XML schema of the namespace. If set to null, Conversion will try read schemaLocation from the root element of the document. Default is null |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Sets desired page width for converting GIS document. Default is 1000. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->