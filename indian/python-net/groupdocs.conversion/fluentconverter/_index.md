---
title: "FluentConverter वर्ग"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक सहज परिवर्तन सेटअप का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

एक सहज परिवर्तन सेटअप का प्रतिनिधित्व करता है।

नमूना फ़्लुएंट रूपांतरण उपयोग:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// सिफ़ारिश: प्रारंभिक चरण (Load से पहले) में WithEvents के माध्यम से हैंडलर्स को एकत्रित करें।
FluentConverter
    .WithEvents(e =>
    {
        e.OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}");
        e.OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine(ex.Message);
    })
    .Load("input.docx")
    .ConvertTo("output.pdf").WithOptions(new PdfConvertOptions())
    .Convert();
```

```csharp
// प्रति-पृष्ठ मिरर: प्रारंभिक चरण में WithEvents के माध्यम से प्रति-पृष्ठ हैंडलर्स।
FluentConverter
    .WithEvents(e =>
    {
        e.OnPageConverted = ctx       => Console.WriteLine($"page {ctx.Page} done");
        e.OnPageFailed    = (ctx, ex) => Console.Error.WriteLine($"page {ctx.Page}: {ex.Message}");
    })
    .Load("input.pdf")
    .ConvertByPageTo(ctx => new FileStream($"page-{ctx.Page}.png", FileMode.Create))
    .WithOptions(new ImageConvertOptions { Format = ImageFileType.Png })
    .Convert();
```

```csharp
// पुरानी श्रृंखला अभी भी बिना बदलाव के संकलित होती है (अब अप्रचलित चरणबद्ध इंटरफ़ेस द्वारा समर्थित):
FluentConverter.WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
FluentConverter.Load("").GetPossibleConversions();
FluentConverter.Load("").GetDocumentInfo();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

FluentConverter प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | रूपांतरण के लिए स्रोत दस्तावेज़ को कॉन्फ़िगर करें। |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | स्रोत दस्तावेज़ों का सेट कॉन्फ़िगर करें। |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | स्रोत दस्तावेज़ स्ट्रीम को कॉन्फ़िगर करें। |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | स्रोत दस्तावेज़ स्ट्रीमों का सेट कॉन्फ़िगर करें। |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | प्रवेश चरण में रूपांतरण जीवनचक्र इवेंट हैंडलर्स के साथ फ़्लुएंट श्रृंखला शुरू करता है। |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | रूपांतरण सेटिंग्स को कॉन्फ़िगर करें। |

### साथ ही देखें
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
