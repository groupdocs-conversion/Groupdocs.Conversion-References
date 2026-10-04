---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ページ変換が失敗したときに呼び出されるコールバックを登録します。再度呼び出すと以前に設定されたハンドラが置き換えられます。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

ページ変換が失敗したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| onFailed | Action`2 | 変換されたページコンテキストと失敗の原因となった例外を受け取り、失敗を処理するアクションです。 |

### 戻り値

この段階で、追加のハンドラや `Convert` / `Compress` をチェーンできます。

### 関連項目

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
