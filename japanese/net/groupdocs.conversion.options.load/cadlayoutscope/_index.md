---
title: "CadLayoutScope"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "CAD 変換が選択する描画空間（モデル空間、ペーパースペースレイアウト、またはその両方）を表します。"
type: docs
weight: 2420
url: /ja/net/groupdocs.conversion.options.load/cadlayoutscope/
---
## CadLayoutScope class

CAD 変換が選択する描画空間（モデル空間、ペーパー空間レイアウト、またはその両方）を表します。

```csharp
public class CadLayoutScope : Enumeration
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | 現在のオブジェクトを表す文字列を返します。 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [Both](../../groupdocs.conversion.options.load/cadlayoutscope/both) | モデル空間とすべてのペーパースペースレイアウトを選択します。これはデフォルト値で、変換を制限しません。スコープが指定されていない場合と同様に、図面はそのまま正確にレンダリングされます。 |
| static readonly [Layouts](../../groupdocs.conversion.options.load/cadlayoutscope/layouts) | ペーパースペースレイアウトのみを選択します。モデル空間は除外されます。 |
| static readonly [Model](../../groupdocs.conversion.options.load/cadlayoutscope/model) | モデル空間のみを選択します。 |

### 関連項目

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
