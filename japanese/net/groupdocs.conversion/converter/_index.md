---
title: "Converter"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ドキュメント変換プロセスを制御するメインクラスを表します。"
type: docs
weight: 890
url: /ja/net/groupdocs.conversion/converter/
---
## Converter class

ドキュメント変換プロセスを制御するメインクラスを表します。

```csharp
public sealed class Converter : IDisposable
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | 新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_5)(string) | 新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | 新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | 新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 明示的な変換イベントを使用して新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 明示的な変換イベントを使用して新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 明示的な変換イベントを使用して新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | 明示的な変換イベントを使用して新しい [`Converter`](../converter) クラスのインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメント全体を保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメント全体を保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメント全体を保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメント全体を保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | ソースドキュメントを変換します。変換されたドキュメント全体を保存します。 |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | リソースを解放します。 |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | ソースドキュメント情報を取得します - ページ数やファイルタイプ固有のその他のドキュメントプロパティ。 |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | ソースドキュメント情報を取得します - ページ数やファイルタイプ固有のその他のドキュメントプロパティ。 |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | ソースドキュメントの可能な変換を取得します。 |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | ソースドキュメントがパスワードで保護されているか確認します。 |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | サポートされているすべての変換を取得します |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | 指定されたドキュメント拡張子に対するサポートされている変換を取得します |

### 例

**Basic conversion from file path:**

```csharp
// DOCX を PDF に変換
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// DOCX を PDF に変換し、透かしと特定のページ範囲を適用します
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
// ストリームからストリームへドキュメントを変換する
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
// パスワードで保護されたドキュメントを読み込み、PDFに変換する
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
// ドキュメントページを個別の画像ファイルに変換する
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
// すべてのイベントハンドラを ConversionEvents バッグに集約し、Converter に渡す。
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

平坦な `OnConversionFailed`、`OnConversionByPageFailed`、および `OnCompressionCompleted` プロパティは [`ConverterSettings`](../convertersettings) 上で依然として機能しますが、廃止予定です；新しいコードでは `events` コンストラクタ パラメータを介して [`ConversionEvents`](../conversionevents) インスタンスを渡すべきです。

**Get document information:**

```csharp
// 変換前にドキュメントのメタデータを取得する
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### 関連項目

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
