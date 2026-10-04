---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換ライフサイクルのイベントハンドラを集約します。インスタンスは Converter./converter のコンストラクタの events パラメータまたは fluent の WithEvents メソッドに渡します。個別の ConverterSettings./convertersettings ハンドラプロパティ（廃止予定）よりもこちらを優先してください。"
type: docs
weight: 850
url: /ja/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

変換ライフサイクルのイベントハンドラを集約します。インスタンスは [`Converter`](../converter) のコンストラクタの `events` パラメータまたは fluent の `WithEvents` メソッドに渡します。個別の [`ConverterSettings`](../convertersettings) ハンドラプロパティ（廃止予定）よりもこちらを優先してください。

```csharp
public sealed class ConversionEvents
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ConversionEvents](conversionevents)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | 変換出力の圧縮が完了したときに発生します。圧縮パイプライン (LIB_ZIP) を含むビルドでのみ呼び出されます。 |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | 変換実行が完了したときに一度だけ発生します。成功か失敗かに関係なく。 |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | 変換進捗がパーセンテージ (0–100) で定期的に発生します。 |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | 変換実行の開始時に一度だけ発生します。ドキュメントが処理される前です。 |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | 全体ドキュメントの変換が正常に完了したときに1回発生します。 |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | 全体ドキュメントの変換が失敗したときに1回発生します。 |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | ソースドキュメントで参照されているフォントが利用できず、置き換えられたときに発生します（顧客提供の[`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute) ルール、設定されたデフォルトフォント、または変換パイプラインの内部フォールバックのいずれかによる）。 |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | ページごとの変換が正常に完了したときに、ページごとに1回発生します。 |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | ページごとの変換が失敗したときに、ページごとに1回発生します。 |

### 関連項目

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
