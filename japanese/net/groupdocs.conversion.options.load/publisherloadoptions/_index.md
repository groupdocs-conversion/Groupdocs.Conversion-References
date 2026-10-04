---
title: "PublisherLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Publisher ドキュメントの読み込みオプション。"
type: docs
weight: 2790
url: /ja/net/groupdocs.conversion.options.load/publisherloadoptions/
---
## PublisherLoadOptions class

Publisher ドキュメントの読み込みオプション。

```csharp
public class PublisherLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PublisherLoadOptions](publisherloadoptions)() | 新しいインスタンスの[`PublisherLoadOptions`](../publisherloadoptions)クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/publisherloadoptions/defaultfont) { get; set; } | Publisherドキュメントのデフォルトフォントです。フォントが見つからない場合は、次のフォントが使用されます。 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/publisherloadoptions/fontsubstitutes) { get; set; } | Publisherドキュメントを変換する際に特定のフォントを置き換えます。 |
| [Format](../../groupdocs.conversion.options.load/publisherloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
