---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "フラット化された bypage 変換ハンドラーステージです。IConversionHandlersStage の perpage ミラーです。./iconversionhandlersstage。"
type: docs
weight: 1320
url: /ja/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

フラット化された by-page 変換ハンドラーステージです。[`IConversionHandlersStage`](../iconversionhandlersstage) の per-page ミラーです。

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | ページ変換が正常に完了したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。 |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | ページ変換が失敗したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。 |

### 関連項目

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
