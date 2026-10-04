---
title: "FontTransformation"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "フォント属性を含むフォント変換設定について説明します。フォント変換はドキュメントの読み込みとフォント置換の後に適用されます。"
type: docs
weight: 260
url: /ja/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

フォント属性を含むフォント変換設定について説明します。フォント変換はドキュメントの読み込みとフォント置換の後に適用されます。

```csharp
public class FontTransformation : ValueObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | true の場合、元のフォント名に対して任意のフォントサイズに一致します。false の場合、OriginalFont に指定された正確なフォントサイズに一致します。 |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | true の場合、元のフォントに対して任意のフォントスタイル（太字、斜体、下線）に一致します。false の場合、OriginalFont に指定された正確なフォントスタイルに一致します。 |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | 一致させて置換する元のフォント仕様。 |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | 置換フォントの仕様。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | サイズとスタイルが一致する正確なフォントマッチングでフォント変換を作成します。 |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | 名前のみでフォント変換を作成し、任意のサイズとスタイルに一致させます。置換フォントは元のフォントのサイズとスタイルを保持します。 |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | 柔軟なマッチングオプションでフォント変換を作成します。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
