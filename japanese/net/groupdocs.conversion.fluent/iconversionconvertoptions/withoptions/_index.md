---
title: "WithOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換オプションを設定する"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

変換オプションを設定する

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 変換オプション |

### 戻り値

変換構築を続行するためのインターフェイス

### 関連項目

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

変換オプションを設定する

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| パラメータ | 説明 |
| --- | --- |
| convertOptionsProvider | 変換オプションプロバイダー |
| convertOptionsProvider arg1arg1 | この [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### 戻り値

変換構築を続行するためのインターフェイス

### 関連項目

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
