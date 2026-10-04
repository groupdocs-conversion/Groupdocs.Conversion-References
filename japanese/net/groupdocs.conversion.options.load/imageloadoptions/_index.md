---
title: "ImageLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "画像ドキュメントの読み込みオプション。"
type: docs
weight: 2650
url: /ja/net/groupdocs.conversion.options.load/imageloadoptions/
---
## ImageLoadOptions class

画像ドキュメントの読み込みオプション。

```csharp
public sealed class ImageLoadOptions : BaseImageLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ImageLoadOptions](imageloadoptions)() | 新しいインスタンスの [`ImageLoadOptions`](../imageloadoptions) クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Psd、Emf、Wmf ドキュメントタイプのデフォルトフォントです。フォントが欠落している場合は以下のフォントが使用されます。 |
| [Format](../../groupdocs.conversion.options.load/imageloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | ドキュメントをロードする前にフォントフォルダーをリセットします |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
