---
title: "FluentConverter クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "流暢な変換設定を表します。"
type: docs
url: /ja/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

流暢な変換設定を表します。

サンプルの流暢な変換使用例:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// 推奨: 初期段階（Load 前）で WithEvents を使用してハンドラを集約する。
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
// ページ単位のミラー: 初期段階で WithEvents を使用したページ単位のハンドラ。
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
// レガシーチェーンは依然として変更なしでコンパイルされます（現在は廃止された段階的インターフェイスに裏付けられています）:
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

FluentConverter 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | 変換用のソースドキュメントを構成します。 |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | ソースドキュメントのセットを構成します。 |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | ソースドキュメントストリームを構成します。 |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | ソースドキュメントストリームのセットを構成します。 |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | エントリ段階で変換ライフサイクルイベントハンドラを使用してフルエントチェーンを開始します。 |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | 変換設定を構成します。 |

### 関連項目
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
