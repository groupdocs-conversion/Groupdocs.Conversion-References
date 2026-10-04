---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ソースドキュメントの読み込みまたはレンダリング中に発生した単一のフォント置換を説明します。インスタンスは OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted に渡されます。"
type: docs
weight: 250
url: /ja/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

ソースドキュメントの読み込みまたはレンダリング中に発生した単一のフォント置換を説明します。インスタンスは [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted) に渡されます。

```csharp
public sealed class FontSubstitutionContext
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | 新しい [`FontSubstitutionContext`](../fontsubstitutioncontext) を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | ソースドキュメントで参照されているが、変換パイプラインで利用できないフォントの名前です。 |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | 変換パイプラインが報告した置換メッセージをそのまま、文字通りに、未解析で提供します。フォント名を構造的に公開するドキュメントの場合、これは `null` になることがあります（[`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname) を使用してください）。それ以外の場合は、欠落しているフォントと代替フォントの両方の名前を含む、完全な人間可読の説明が含まれます。 |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | 変換中のソースドキュメントのファイル名です。ソースが FileStream でないストリームとして提供された場合、実際のファイル名の代わりに生成された識別子が含まれます。 |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | 代替として使用されるフォントの名前です。エンジンが置換を説明テキストとしてのみ報告するドキュメントの場合、`null` になることがあります。その場合は [`Reason`](./reason) を参照してください。 |

### 関連項目

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
