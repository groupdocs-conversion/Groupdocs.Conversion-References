---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "フラット化された変換ハンドラーステージです。OnConversionCompleted または OnConversionFailed を任意の順序で、任意の回数設定でき、Convert / Compress に進む前に使用できます。イベントはこのステージではなく、WithEvents./iconversionsettings/withevents を介して早期ステージで登録すべきです。"
type: docs
weight: 1480
url: /ja/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

フラット化された変換ハンドラーステージです。`OnConversionCompleted` または `OnConversionFailed` を任意の順序で、任意の回数設定し、`Convert` / `Compress` に進む前に使用できます。イベントはこのステージではなく、[`WithEvents`](../iconversionsettings/withevents) を介して早期ステージで登録すべきです。

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。 |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | ドキュメント変換が失敗したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。 |

### 関連項目

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
