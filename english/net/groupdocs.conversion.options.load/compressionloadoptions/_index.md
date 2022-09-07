---
title: CompressionLoadOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for loading compression documents.
type: docs
weight: 1790
url: /net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Options for loading compression documents.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Initializes new instance of [`CompressionLoadOptions`](../compressionloadoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Option to control whether the owned documents in the documents container must be converted |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Option to control whether the documents container itself must be converted If this property is true the documents container will be the first converted document |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Option to control how many levels in depth to perform conversion |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Input document file type. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Set password to load protected document. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->