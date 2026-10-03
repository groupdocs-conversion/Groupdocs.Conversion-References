---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "डॉक्यूमेंट कन्वर्ज़न प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।"
type: docs
weight: 890
url: /hi/net/groupdocs.conversion/converter/
---
## Converter class

डॉक्यूमेंट कन्वर्ज़न प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।

```csharp
public sealed class Converter : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का। |
| [Converter](converter#constructor_5)(string) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का। |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का। |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का। |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का स्पष्ट रूपांतरण घटनाओं के साथ। |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का। |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का स्पष्ट रूपांतरण घटनाओं के साथ। |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का। |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का स्पष्ट रूपांतरण घटनाओं के साथ। |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | नया उदाहरण प्रारंभ करता है [`Converter`](../converter) क्लास का स्पष्ट रूपांतरण घटनाओं के साथ। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | संसाधनों को मुक्त करता है। |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | स्रोत दस्तावेज़ की जानकारी प्राप्त करता है - पृष्ठों की संख्या और फ़ाइल प्रकार के विशिष्ट अन्य दस्तावेज़ गुण। |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | स्रोत दस्तावेज़ की जानकारी प्राप्त करता है - पृष्ठों की संख्या और फ़ाइल प्रकार के विशिष्ट अन्य दस्तावेज़ गुण। |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | स्रोत दस्तावेज़ के संभावित रूपांतरण प्राप्त करता है। |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | जाँचता है कि स्रोत दस्तावेज़ पासवर्ड-संरक्षित है या नहीं |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | सभी समर्थित रूपांतरण प्राप्त करता है |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | प्रदान किए गए दस्तावेज़ एक्सटेंशन के लिए समर्थित रूपांतरण प्राप्त करता है |

### उदाहरण

**Basic conversion from file path:**

```csharp
// DOCX को PDF में रूपांतरित करें
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// वॉटरमार्क और विशिष्ट पृष्ठ सीमा के साथ DOCX को PDF में रूपांतरित करें
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
// दस्तावेज़ को स्ट्रीम से स्ट्रीम में रूपांतरित करें
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
// पासवर्ड-संरक्षित दस्तावेज़ लोड करें और PDF में रूपांतरित करें
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
// दस्तावेज़ पृष्ठों को अलग-अलग छवि फ़ाइलों में रूपांतरित करें
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

**Registering conversion event handlers (recommended path):**

```csharp
// सभी इवेंट हैंडलरों को एक ConversionEvents बैग में एकत्रित करें और इसे Converter को पास करें।
var events = new ConversionEvents
{
    OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}"),
    OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine($"Conversion of {ctx.SourceFileName} failed: {ex.Message}"),
    OnPageFailed        = (ctx, ex) => Console.Error.WriteLine($"Page {ctx.Page} of {ctx.SourceFileName} failed: {ex.Message}"),
};
using (var converter = new Converter("sample.docx", () => new ConverterSettings(), () => events))
{
    converter.Convert("output.pdf", new PdfConvertOptions());
}
```

फ़्लैट `OnConversionFailed`, `OnConversionByPageFailed`, और `OnCompressionCompleted` प्रॉपर्टीज़ [`ConverterSettings`](../convertersettings) पर अभी भी काम करती हैं लेकिन अप्रचलित हैं; नया कोड एक [`ConversionEvents`](../conversionevents) इंस्टेंस को `events` कंस्ट्रक्टर पैरामीटर के माध्यम से पास करना चाहिए।

**Get document information:**

```csharp
// रूपांतरण से पहले दस्तावेज़ मेटाडेटा प्राप्त करें
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### देखें भी

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
