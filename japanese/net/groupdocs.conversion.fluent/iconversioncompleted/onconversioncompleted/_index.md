---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換されたドキュメントストリームを受信します。ConvertTostring の fileName または ConvertToconvertedStreamProvider が設定されている場合にのみ発生します。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

変換されたドキュメントのストリームを受け取ります。"ConvertTo(string fileName)" または ConvertTo(convertedStreamProvider)" が設定されている場合にのみ発火します。

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertedFileStream | Action`1 | 変換されたドキュメントストリームプロバイダー [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### 戻り値

変換構築を続行するためのインターフェイス

### 関連項目

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
