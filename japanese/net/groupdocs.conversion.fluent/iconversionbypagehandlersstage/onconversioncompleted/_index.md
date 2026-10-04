---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ページ変換が正常に完了したときに呼び出されるコールバックを登録します。再度呼び出すと以前に設定されたハンドラが置き換えられます。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

ページ変換が正常に完了したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| onCompleted | Action`1 | 完了を処理するアクションで、変換されたページコンテキストを受け取ります。 |

### 戻り値

この段階で、追加のハンドラや `Convert` / `Compress` をチェーンできます。

### 関連項目

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
