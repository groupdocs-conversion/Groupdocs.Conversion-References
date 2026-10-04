---
title: "HyphenationOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ハイフネーション設定ドキュメントのオプション。"
type: docs
weight: 2570
url: /ja/net/groupdocs.conversion.options.load/hyphenationoptions/
---
## HyphenationOptions class

ハイフネーション設定ドキュメントのオプション。

```csharp
public sealed class HyphenationOptions : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [HyphenationOptions](hyphenationoptions)() | 新しいインスタンスの [`HyphenationOptions`](../hyphenationoptions) クラスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoHyphenation](../../groupdocs.conversion.options.load/hyphenationoptions/autohyphenation) { get; set; } | ドキュメントに対して自動ハイフネーションが有効かどうかを決定する値を取得または設定します。このプロパティのデフォルト値は false です。 |
| [HyphenateCaps](../../groupdocs.conversion.options.load/hyphenationoptions/hyphenatecaps) { get; set; } | 全て大文字で記述された単語がハイフネーションされるかどうかを決定する値を取得または設定します。このプロパティのデフォルト値は true です。 |
| [HyphenationDictionaries](../../groupdocs.conversion.options.load/hyphenationoptions/hyphenationdictionaries) { get; set; } | ISO言語コードと提供されたハイフネーション辞書ストリーム間の関連付けを含む辞書です。 |

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
