---
title: Converter
second_title: GroupDocs.Conversion for .NET API Reference
description: Represents main class that controls document conversion process.
type: docs
weight: 610
url: /net/groupdocs.conversion/converter/
---
## Converter class

Represents main class that controls document conversion process.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Converter](converter#constructor)() | Initializes new instance of [`Converter`](../converter) class for fluent conversion setup. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_7)(string) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |

## Methods

| Name | Description |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(SaveDocumentStream, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(SaveDocumentStream, ConvertOptionsProvider) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(SaveDocumentStreamForFileType, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(SaveDocumentStreamForFileType, ConvertOptionsProvider) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(SavePageStream, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(SavePageStream, ConvertOptionsProvider) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(SavePageStreamForFileType, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(SavePageStreamForFileType, ConvertOptionsProvider) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(SavePageStream, ConvertedPageStream, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) | Converts source document. Saves the converted document page by page. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Releases resources. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Gets source document info - pages count and other document properties specific to the file type. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Gets possible conversions for the source document. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Configure source document stream |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Configure set of source documents streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Configure source document for conversion |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Configure set of source documents |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Configure conversion settings |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Gets all supported conversions |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Gets supported conversions for provided document extension |

### See Also

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
