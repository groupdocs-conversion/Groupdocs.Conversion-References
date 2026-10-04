---
title: "ConvertByPageTo"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換されたページをストリームとして保存する"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionto/convertbypageto/
---
## IConversionTo.ConvertByPageTo method

変換されたページをストリームとして保存する

```csharp
public IConversionByPageOptionsOrHandlerSetup ConvertByPageTo(
    Func<SavePageContext, Stream> convertedStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | 変換されたドキュメントページストリームプロバイダー 保存コンテキスト |

### 戻り値

変換構築を続行するためのページオプションまたはハンドラ設定インターフェイス

### 関連項目

* interface [IConversionByPageOptionsOrHandlerSetup](../../iconversionbypageoptionsorhandlersetup)
* class [SavePageContext](../../../groupdocs.conversion/savepagecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
