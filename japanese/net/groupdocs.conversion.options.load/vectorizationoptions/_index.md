---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "画像のベクトル化オプション。"
type: docs
weight: 2900
url: /ja/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

画像のベクトル化オプション。

```csharp
public class VectorizationOptions : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | VectorizationOptions のデフォルト コンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | 背景色を取得または設定します。デフォルト値は透明な白です。 |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | 画像を量子化する際に使用される最大色数を取得または設定します。デフォルト値は 25 です。 |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | ベクトル化画像を有効にします。デフォルトは false です。 |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | 画像の幅と高さの乗算で決定される最大次元を取得または設定します。このプロパティに基づいて画像のサイズがスケーリングされます。デフォルト値は 1800000 です。 |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | 線幅を取得または設定します。このパラメータの値はグラフィック スケールの影響を受けます。デフォルト値は 1 です。 |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | 画像トレーススムーザーの重症度を設定します |

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
