---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換されたドキュメントへの透かし設定オプション"
type: docs
weight: 2300
url: /ja/net/groupdocs.conversion.options.convert/watermarkoptions/
---
## WatermarkOptions class

変換されたドキュメントへの透かし設定オプション

```csharp
public abstract class WatermarkOptions : ValueObject, ICloneable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | 透かしを自動スケールします。値が true の場合、位置とサイズはページサイズに合わせて自動的に計算されます。 |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | 透かしが背景としてスタンプされることを示します。値が true の場合、透かしは下部に配置されます。デフォルトは false で、透かしは上部に配置されます。 |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | 透かしの高さ |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | 透かしの左位置 |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | 透かしの回転角度 |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | 透かしの上位置 |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | 透かしの透明度。値は 0 から 1 の間です。値が 0 の場合は完全に表示され、値が 1 の場合は見えなくなります。 |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | 透かしの幅 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | 現在のインスタンスをクローンします |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
