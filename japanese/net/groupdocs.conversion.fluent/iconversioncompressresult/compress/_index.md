---
title: "Compress"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "このメソッドを呼び出して変換結果を圧縮します。エントリ段階で compressedstream ハンドラを WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents 経由で登録し、設定は OnCompressionCompleted です。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

このメソッドを呼び出して変換結果を圧縮します。エントリ段階で compressed-stream ハンドラを [`WithEvents`](../../iconversionsettings/withevents) 経由で登録し、設定は `OnCompressionCompleted` です。

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| オプション | CompressionConvertOptions | 圧縮変換オプション |

### 戻り値

`Convert` に進む継続処理です。

### 関連項目

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
