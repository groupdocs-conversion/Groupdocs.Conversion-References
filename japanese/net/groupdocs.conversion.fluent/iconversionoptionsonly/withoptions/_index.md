---
title: "WithOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換プロセスのための変換オプションを設定します。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

変換プロセスのための変換オプションを設定します。

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 変換オプション。 |

### 戻り値

ハンドラステージは変換構築を続行します。

### 関連項目

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

プロバイダー関数を使用して変換オプションを設定します。

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| optionsProvider | Func`2 | 変換コンテキストに基づいて変換オプションを提供する関数。 |

### 戻り値

ハンドラステージは変換構築を続行します。

### 関連項目

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
