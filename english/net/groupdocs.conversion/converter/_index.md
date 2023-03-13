---
title: Converter
second_title: GroupDocs.Conversion for .NET API Reference
description: Represents main class that controls document conversion process.
type: docs
weight: 730
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
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converts source document. Saves the whole converted document. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Releases resources. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Gets source document info - pages count and other document properties specific to the file type. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Gets possible conversions for the source document. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Checks is source document is password protected |
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
