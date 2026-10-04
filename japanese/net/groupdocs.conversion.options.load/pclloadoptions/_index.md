---
title: "PclLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Pcl ドキュメントの読み込みオプション。"
type: docs
weight: 2730
url: /ja/net/groupdocs.conversion.options.load/pclloadoptions/
---
## PclLoadOptions class

Pcl ドキュメントの読み込みオプション。

```csharp
public sealed class PclLoadOptions : LoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PclLoadOptions](pclloadoptions)() | 新しいインスタンスの [`PclLoadOptions`](../pclloadoptions) クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/pclloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pclloadoptions/resetfontfolders) { get; set; } | ドキュメントをロードする前にフォントフォルダーをリセットします |

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
