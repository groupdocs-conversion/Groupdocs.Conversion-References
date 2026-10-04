---
title: "BitmapInfo"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ピクセルの配列とビットマップ情報を含むオブジェクトです。"
type: docs
weight: 70
url: /ja/net/groupdocs.conversion.contracts/bitmapinfo/
---
## BitmapInfo class

ピクセルの配列とビットマップ情報を含むオブジェクトです。

```csharp
public class BitmapInfo : ValueObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.contracts/bitmapinfo/format) { get; } | ビットマップのピクセル形式を取得します。 |
| [Height](../../groupdocs.conversion.contracts/bitmapinfo/height) { get; } | ビットマップの高さを取得します。 |
| [PixelBytes](../../groupdocs.conversion.contracts/bitmapinfo/pixelbytes) { get; } | ピクセルの配列を取得します。 |
| [Width](../../groupdocs.conversion.contracts/bitmapinfo/width) { get; } | ビットマップの幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/bitmapinfo/create)(byte[], int, int, PixelFormat) | 新しい BitmapInfo インスタンスを作成します |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [PixelFormat](bitmapinfo.pixelformat) | ピクセル形式列挙について説明します |

### 関連項目

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
