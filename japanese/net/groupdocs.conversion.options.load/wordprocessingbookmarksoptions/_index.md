---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "WordProcessing のブックマーク処理オプション"
type: docs
weight: 2930
url: /ja/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

WordProcessing のブックマーク処理オプション

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | ドキュメントアウトラインで Word ブックマークを表示するデフォルトのレベルを指定します。デフォルトは 0 です。有効範囲は 0 から 9 です。 |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | ファイルを表示したときにドキュメントアウトラインで展開して表示するレベル数を指定します。デフォルトは 0 です。有効範囲は 0 から 9 です。このオプションは XPS へ保存する場合は機能しませんので注意してください。 |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | ドキュメントアウトラインに含める見出し（Heading スタイルで書式設定された段落）のレベル数を指定します。デフォルトは 0 です。有効範囲は 0 から 9 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
