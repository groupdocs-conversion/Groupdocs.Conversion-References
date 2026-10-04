---
title: "BaseImageLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "画像ドキュメントの読み込みオプション。"
type: docs
weight: 2400
url: /ja/net/groupdocs.conversion.options.load/baseimageloadoptions/
---
## BaseImageLoadOptions class

画像ドキュメントの読み込みオプション。

```csharp
public abstract class BaseImageLoadOptions : LoadOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Psd、Emf、Wmf ドキュメントタイプのデフォルトフォントです。フォントが欠落している場合は以下のフォントが使用されます。 |
| [Format](../../groupdocs.conversion.options.load/baseimageloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | ドキュメントをロードする前にフォントフォルダーをリセットします |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
