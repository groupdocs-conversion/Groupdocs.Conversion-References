---
title: "Converter"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية تحويل المستند."
type: docs
weight: 890
url: /ar/net/groupdocs.conversion/converter/
---
## Converter class

يمثل الفئة الرئيسية التي تتحكم في عملية تحويل المستند.

```csharp
public sealed class Converter : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter) مع أحداث تحويل صريحة. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter) مع أحداث تحويل صريحة. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter) مع أحداث تحويل صريحة. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | ينشئ مثلاً جديدًا من الفئة [`Converter`](../converter) مع أحداث تحويل صريحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل صفحةً بصفحة. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | يحوِّل مستند المصدر. يحفظ المستند المُحوَّل بالكامل. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | يطلق الموارد. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | يحصل على معلومات المستند المصدر - عدد الصفحات وغيرها من خصائص المستند الخاصة بنوع الملف. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | يحصل على معلومات المستند المصدر - عدد الصفحات وغيرها من خصائص المستند الخاصة بنوع الملف. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | يحصل على التحويلات الممكنة للمستند المصدر. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | يتحقق مما إذا كان مستند المصدر محميًا بكلمة مرور |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | يحصل على جميع التحويلات المدعومة |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | يحصل على التحويلات المدعومة لامتداد المستند المقدم |

### أمثلة

**Basic conversion from file path:**

```csharp
// تحويل DOCX إلى PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// تحويل DOCX إلى PDF مع علامة مائية ونطاق صفحات محدد
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
// تحويل المستند من تدفق إلى تدفق
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
// تحميل مستند محمي بكلمة مرور وتحويله إلى PDF
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
// تحويل صفحات المستند إلى ملفات صورة منفصلة
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
// تجميع جميع معالجات الأحداث في حزمة ConversionEvents وتمريرها إلى الـ Converter.
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

الخصائص المسطحة `OnConversionFailed` و `OnConversionByPageFailed` و `OnCompressionCompleted` على [`ConverterSettings`](../convertersettings) لا تزال تعمل ولكنها قديمة؛ يجب على الشيفرة الجديدة تمرير كائن [`ConversionEvents`](../conversionevents) عبر معامل المُنشئ `events`.

**Get document information:**

```csharp
// استرجاع بيانات تعريف المستند قبل التحويل
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### انظر أيضًا

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
