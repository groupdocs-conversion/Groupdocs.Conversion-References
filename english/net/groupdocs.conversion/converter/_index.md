---
title: Converter
second_title: GroupDocs.Conversion for .NET API Reference
description: Represents main class that controls document conversion process.
type: docs
weight: 820
url: /net/groupdocs.conversion/converter/
---
## Converter class

Represents main class that controls document conversion process.

```csharp
public sealed class Converter : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_3)(string) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_4)(string, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |
| [Converter](converter#constructor_5)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initializes new instance of [`Converter`](../converter) class. |

## Methods

| Name | Description |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Converts source document. Saves the whole converted document. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Converts source document. Saves the converted document page by page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Converts source document. Saves the whole converted document. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Releases resources. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Gets source document info - pages count and other document properties specific to the file type. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Gets source document info - pages count and other document properties specific to the file type. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Gets possible conversions for the source document. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Checks is source document is password protected |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Gets all supported conversions |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Gets supported conversions for provided document extension |

### Examples

**Basic conversion from file path:**

```csharp
// Convert DOCX to PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Convert DOCX to PDF with watermark and specific page range
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions
    {
        PageNumber = 1,
        PagesCount = 3,
        Watermark = new WatermarkTextOptions("CONFIDENTIAL")
        {
            Color = System.Drawing.Color.Red,
            Width = 300,
            Height = 100
        }
    };
    converter.Convert("output.pdf", options);
}
```

**Conversion from stream:**

```csharp
// Convert document from stream to stream
using (var sourceStream = File.OpenRead("sample.docx"))
using (var converter = new Converter(() => sourceStream))
using (var outputStream = File.Create("output.pdf"))
{
    var options = new PdfConvertOptions();
    converter.Convert((SaveContext context) => outputStream, options);
}
```

**Conversion with load options (password-protected document):**

```csharp
// Load password-protected document and convert to PDF
var loadOptions = new WordProcessingLoadOptions
{
    Password = "secret_password"
};
using (var converter = new Converter("protected.docx", (LoadContext context) => loadOptions))
{
    var convertOptions = new PdfConvertOptions();
    converter.Convert("output.pdf", convertOptions);
}
```

**Page-by-page conversion:**

```csharp
// Convert document pages to separate image files
using (var converter = new Converter("sample.pdf"))
{
    var options = new ImageConvertOptions
    {
        Format = ImageFileType.Png
    };

    converter.Convert(
        (SavePageContext context) => File.Create($"page-{context.Page}.png"),
        options
    );
}
```

**Get document information:**

```csharp
// Retrieve document metadata before conversion
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### See Also

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
