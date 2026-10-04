---
title: "PageResizeMode"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ページサイズが変更されたときにコンテンツをどのようにスケーリングするかを指定します"
type: docs
weight: 2050
url: /ja/net/groupdocs.conversion.options.convert/pageresizemode/
---
## PageResizeMode class

ページサイズが変更されたときにコンテンツをどのようにスケーリングするかを指定します

```csharp
public sealed class PageResizeMode : Enumeration
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
| static [AlignTopLeft](../../groupdocs.conversion.options.convert/pageresizemode/aligntopleft) | スケーリングは適用されません。コンテンツは左上隅に揃えられます。 |
| static [ScaleToFill](../../groupdocs.conversion.options.convert/pageresizemode/scaletofill) | コンテンツを伸ばしてページ全体を埋めます。アスペクト比が歪む可能性があります。 |
| static [ScaleToFit](../../groupdocs.conversion.options.convert/pageresizemode/scaletofit) | コンテンツを比例的に拡大してページ全体に収め、オーバーフローを防ぎます。余白が生じる可能性があります。 |
| static [ScaleToHeight](../../groupdocs.conversion.options.convert/pageresizemode/scaletoheight) | コンテンツを比例的に拡大してページの高さに合わせます。幅がオーバーフローし、切り取られる可能性があります。 |
| static [ScaleToWidth](../../groupdocs.conversion.options.convert/pageresizemode/scaletowidth) | ページ幅に合わせてコンテンツを比例的に拡大縮小します。高さがはみ出す場合は切り取られます。 |

### 関連項目

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
