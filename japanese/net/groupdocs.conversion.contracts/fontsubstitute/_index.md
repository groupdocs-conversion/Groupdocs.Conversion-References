---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "欠落したフォントの置換について説明します。"
type: docs
weight: 240
url: /ja/net/groupdocs.conversion.contracts/fontsubstitute/
---
## FontSubstitute class

欠落したフォントの置換について説明します。

```csharp
public class FontSubstitute : ValueObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitute/originalfontname) { get; } | 元のフォント名。 |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitute/substitutefontname) { get; } | 代替フォント名。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fontsubstitute/create)(string, string) | 新しいフォント置換ペアをインスタンス化します。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
