---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "문서 변환 프로세스를 제어하는 ​​주요 클래스를 나타냅니다."
type: docs
weight: 890
url: /ko/net/groupdocs.conversion/converter/
---
## Converter class

문서 변환 프로세스를 제어하는 ​​주요 클래스를 나타냅니다.

```csharp
public sealed class Converter : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_5)(string) | 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 명시적 변환 이벤트와 함께 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 명시적 변환 이벤트와 함께 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 명시적 변환 이벤트와 함께 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 명시적 변환 이벤트와 함께 새 인스턴스인 [`Converter`](../converter) 클래스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | 소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | 소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | 소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | 소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | 소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | 소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | 리소스를 해제합니다. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | 소스 문서 정보를 가져옵니다 - 페이지 수 및 파일 유형에 특정한 기타 문서 속성. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | 소스 문서 정보를 가져옵니다 - 페이지 수 및 파일 유형에 특정한 기타 문서 속성. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | 소스 문서에 대한 가능한 변환을 가져옵니다. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | 소스 문서가 암호로 보호되어 있는지 확인합니다 |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | 지원되는 모든 변환을 가져옵니다 |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | 제공된 문서 확장자에 대한 지원 변환을 가져옵니다 |

### 예제

**Basic conversion from file path:**

```csharp
// DOCX를 PDF로 변환
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// 워터마크와 특정 페이지 범위를 지정하여 DOCX를 PDF로 변환
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
// 스트림에서 스트림으로 문서를 변환합니다
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
// 비밀번호로 보호된 문서를 로드하고 PDF로 변환합니다
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
// 문서 페이지를 개별 이미지 파일로 변환합니다
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
// 모든 이벤트 핸들러를 ConversionEvents 가방에 모아 Converter에 전달합니다.
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

[`ConverterSettings`](../convertersettings)에 있는 평면 `OnConversionFailed`, `OnConversionByPageFailed`, 및 `OnCompressionCompleted` 속성은 여전히 작동하지만 더 이상 사용되지 않습니다; 새로운 코드는 `events` 생성자 매개변수를 통해 [`ConversionEvents`](../conversionevents) 인스턴스를 전달해야 합니다.

**Get document information:**

```csharp
// 변환 전에 문서 메타데이터를 검색합니다
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### 또 보기

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
