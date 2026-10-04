---
title: "Rectangle"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "切り抜き目的でエッジで定義された矩形を表します。"
type: docs
weight: 580
url: /ja/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

切り抜き目的でエッジで定義された矩形を表します。

```csharp
public sealed class Rectangle : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | 指定されたエッジで[`Rectangle`](../rectangle)構造体の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | 矩形の下端を取得します。 |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | 上端と下端に基づいて矩形の高さを取得します。 |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | 矩形の左端を取得します。 |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | 矩形の右端を取得します。 |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | 矩形の上端を取得します。 |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | 左端と右端に基づいて矩形の幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | 指定された余白を除去して、現在の矩形の切り抜きバージョンを作成します。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | 矩形の文字列表現を返します。 |

### 関連項目

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
