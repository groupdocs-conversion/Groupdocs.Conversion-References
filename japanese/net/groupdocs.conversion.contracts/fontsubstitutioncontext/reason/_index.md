---
title: "理由"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換パイプラインがそのまま報告した置換メッセージ（文字通りで未解析）。フォント名が構造的に公開されているドキュメントの場合、これは null になることがあり、OriginalFontNamegroupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname / SubstituteFontNamegroupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname を使用してください。その他の場合は、欠落しているフォントと置換フォントの両方の名前を含む、完全な人間が読める説明が格納されます。"
type: docs
weight: 30
url: /ja/net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
---
## FontSubstitutionContext.Reason property

変換パイプラインがそのまま報告した置換メッセージ（文字通りで未解析）。フォント名が構造的に公開されているドキュメントの場合、これは `null` になることがあり（[`OriginalFontName`](../originalfontname) / [`SubstituteFontName`](../substitutefontname) を使用）、その他の場合は欠落しているフォントと置換フォントの両方の名前を含む、完全な人間が読める説明が格納されます。

```csharp
public string Reason { get; }
```

### 関連項目

* class [FontSubstitutionContext](../../fontsubstitutioncontext)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
