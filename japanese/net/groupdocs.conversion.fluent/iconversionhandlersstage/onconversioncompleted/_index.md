---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録します。再度呼び出すと以前に設定されたハンドラが置き換えられます。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| onCompleted | Action`1 | 変換コンテキストを受け取り、完了を処理するアクションです。 |

### 戻り値

この段階で、追加のハンドラや `Convert` / `Compress` をチェーンできます。

### 関連項目

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
