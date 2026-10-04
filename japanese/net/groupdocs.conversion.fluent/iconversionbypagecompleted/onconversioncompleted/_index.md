---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換されたページストリームを受け取ります。ConvertToconvertedStreamProvider が設定されている場合にのみ発火します。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

変換されたページストリームを受け取ります。"ConvertTo(convertedStreamProvider)" が設定されている場合にのみ発火します。

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertedPageStream | Action`1 | 変換されたページストリームプロバイダー [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### 戻り値

変換構築を続行するためのインターフェイス

### 関連項目

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
