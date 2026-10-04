---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "markdown ファイルタイプへの変換オプションです。"
type: docs
weight: 2010
url: /ja/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

markdown ファイルタイプへの変換オプションです。

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | `[`MarkdownOptions`](../markdownoptions)` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | 画像を base64 としてエクスポートします。デフォルトは true です。[`ImageSavingCallback`](./imagesavingcallback) が設定されている場合は無視されます。 |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Markdown を保存する際、画像ごとに一度呼び出されるコールバックです。呼び出し元が画像を外部に永続化し、ドキュメントに埋め込まれた URI を置き換えることができます。`null` でない場合、[`ExportImagesAsBase64`](./exportimagesasbase64) より優先されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
