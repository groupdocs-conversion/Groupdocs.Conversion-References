---
title: "CompressionConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Compression ファイルタイプへの変換オプションです。"
type: docs
weight: 1750
url: /ja/net/groupdocs.conversion.options.convert/compressionconvertoptions/
---
## CompressionConvertOptions class

Compression ファイルタイプへの変換オプションです。

```csharp
public class CompressionConvertOptions : ConvertOptions<CompressionFileType>
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [CompressionConvertOptions](compressionconvertoptions)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [Password](../../groupdocs.conversion.options.convert/compressionconvertoptions/password) { get; set; } | 変換されたドキュメントをパスワードで保護したい場合は、このプロパティを設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CompressionFileType](../../groupdocs.conversion.filetypes/compressionfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
