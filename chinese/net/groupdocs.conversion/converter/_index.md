---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "表示控制文档转换过程的主类。"
type: docs
weight: 890
url: /zh/net/groupdocs.conversion/converter/
---
## Converter class

表示控制文档转换过程的主类。

```csharp
public sealed class Converter : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | 初始化 [`Converter`](../converter) 类的新实例。 |
| [Converter](converter#constructor_5)(string) | 初始化 [`Converter`](../converter) 类的新实例。 |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | 初始化 [`Converter`](../converter) 类的新实例。 |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | 初始化 [`Converter`](../converter) 类的新实例。 |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 初始化 [`Converter`](../converter) 类的新实例，并带有显式转换事件。 |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 初始化 [`Converter`](../converter) 类的新实例。 |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 初始化 [`Converter`](../converter) 类的新实例，并带有显式转换事件。 |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 初始化 [`Converter`](../converter) 类的新实例。 |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 初始化 [`Converter`](../converter) 类的新实例，并带有显式转换事件。 |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 初始化 [`Converter`](../converter) 类的新实例，并带有显式转换事件。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | 转换源文档。保存完整的已转换文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | 转换源文档。逐页保存已转换的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | 转换源文档。保存完整的已转换文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | 转换源文档。逐页保存已转换的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | 转换源文档。保存完整的已转换文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | 转换源文档。保存完整的已转换文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | 转换源文档。逐页保存已转换的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | 转换源文档。逐页保存已转换的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | 转换源文档。保存完整的已转换文档。 |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | 释放资源。 |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | 获取源文档信息——页面计数以及特定文件类型的其他文档属性。 |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | 获取源文档信息——页面计数以及特定文件类型的其他文档属性。 |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | 获取源文档的可能转换。 |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | 检查源文档是否受密码保护 |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | 获取所有支持的转换 |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | 获取提供的文档扩展名支持的转换 |

### 示例

**Basic conversion from file path:**

```csharp
// 将 DOCX 转换为 PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// 将 DOCX 转换为 PDF，带水印和特定页范围
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
// 将文档从流转换为流
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
// 加载受密码保护的文档并转换为 PDF
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
// 将文档页面转换为单独的图像文件
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
// 将所有事件处理程序聚合到 ConversionEvents 包中并将其传递给 Converter。
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

平面 `OnConversionFailed`、`OnConversionByPageFailed` 和 `OnCompressionCompleted` 属性位于 [`ConverterSettings`](../convertersettings) 上仍然可用，但已过时；新代码应通过 `events` 构造函数参数传递一个 [`ConversionEvents`](../conversionevents) 实例。

**Get document information:**

```csharp
// 在转换之前检索文档元数据
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### 另见

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
