---
title: "WithOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換オプションを設定する"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

変換オプションを設定する

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 変換オプション |

### 戻り値

変換構築を続行するためのインターフェイス

### 関連項目

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

変換オプションを設定する

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 変換オプション [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### 戻り値

変換構築を続行するためのインターフェイス

### 関連項目

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
