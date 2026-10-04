---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Web ドキュメントを読み込む際のページレイアウトモードを説明します。"
type: docs
weight: 2720
url: /ja/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Web ドキュメントを読み込む際のページレイアウトモードを説明します。

```csharp
public class PageLayoutOptions : FlagsEnumeration
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | 現在のフラグが指定されたフラグを持っているかチェックします。 |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | 現在のフラグが指定された値を持っているかチェックします。 |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | 現在のオブジェクトを文字列に変換します。 |
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | ビット単位のORを使用して、2つの[`PageLayoutOptions`](../pagelayoutoptions)フラグを結合します。 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | デフォルト値 |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | このフラグは、ドキュメントの内容が最初のページの高さに合わせてスケーリングされることを示します。すべてのドキュメント内容は単一ページのみに配置されます。 |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | ドキュメントの内容がページに合わせて拡大縮小され、利用可能なページ幅と重なり合うコンテンツとの差が最も大きい場所に合わせられることを示します。 |

### 関連項目

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
