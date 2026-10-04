---
title: "WithOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ロードオプションを設定する"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

ロードオプションを設定する

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| loadOptions | LoadOptions | ロードオプション |

### 関連項目

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

現在読み込み中のドキュメントに対するロードオプションを提供します

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | ロードオプションプロバイダー ロードオプションコンテキスト |

### 関連項目

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
