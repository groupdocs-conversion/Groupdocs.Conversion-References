---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Mbox ドキュメントの読み込みオプション。"
type: docs
weight: 2670
url: /ja/net/groupdocs.conversion.options.load/mboxloadoptions/
---
## MboxLoadOptions class

Mbox ドキュメントの読み込みオプション。

```csharp
public sealed class MboxLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [MboxLoadOptions](mboxloadoptions)() | 新しいインスタンスの[`MboxLoadOptions`](../mboxloadoptions)クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/mboxloadoptions/convertowned) { get; } | [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) を実装します（読み取り専用）。trueに設定します。所有するドキュメントが変換されます。 |
| [ConvertOwner](../../groupdocs.conversion.options.load/mboxloadoptions/convertowner) { get; } | [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) を実装します（読み取り専用）。falseに設定します。所有者は変換されません。 |
| [Depth](../../groupdocs.conversion.options.load/mboxloadoptions/depth) { get; set; } | [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) を実装します。デフォルト: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/mboxloadoptions/clone)() | 現在のインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
