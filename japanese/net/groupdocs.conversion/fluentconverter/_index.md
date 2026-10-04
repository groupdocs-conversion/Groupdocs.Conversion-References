---
title: "FluentConverter"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "フルエントな変換設定用のクラスです。"
type: docs
weight: 1580
url: /ja/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

フルエントな変換設定用のクラスです。

```csharp
public static class FluentConverter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | ソースドキュメントのストリームを構成する |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | ソースドキュメントストリームのセットを構成する |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | 変換用のソースドキュメントを構成する |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | ソースドキュメントのセットを構成する |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | 変換ライフサイクルイベントハンドラで開始するフルエントチェーンのエントリーステージバリアントです。[`WithSettings`](./withsettings) と同じエントリーステージに位置し、生成された [`ConversionEvents`](../conversionevents) バッグはコンバータによるすべての変換実行時に発火します。 |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | 変換設定を構成する |

### 備考

フルエント変換の使用例:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// 推奨: 早期段階（Load 前）で WithEvents を使用してハンドラを集約します。
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
// ページごとのミラー: 早期段階で WithEvents を使用したページごとのハンドラ。
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
// レガシーチェーンは依然として変更なしでコンパイルされます（現在は廃止されたステージドインターフェイスに裏付けられています）：
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

### 関連項目

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
