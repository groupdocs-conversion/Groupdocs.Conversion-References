---
title: "ConvertTo"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換されたドキュメントをファイルとして保存する"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

変換されたドキュメントをファイルとして保存する

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | String | 変換されたドキュメント |

### 戻り値

変換構築を続行するためのオプションまたはハンドラ設定インターフェイス

### 関連項目

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

変換されたドキュメントをストリームとして保存する

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | 変換されたドキュメントストリームプロバイダー 保存コンテキスト |

### 戻り値

変換構築を続行するためのオプションまたはハンドラ設定インターフェイス

### 関連項目

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
