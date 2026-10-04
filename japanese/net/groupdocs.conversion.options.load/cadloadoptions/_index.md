---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "CAD ドキュメントの読み込みオプション。"
type: docs
weight: 2430
url: /ja/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

CAD ドキュメントの読み込みオプション。

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | [`CadLoadOptions`](../cadloadoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | 背景色を取得または設定します。 |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | CTB ソースを取得または設定します。 |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | 前景色を取得または設定します。 |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | 描画のタイプを取得または設定します。 |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | 変換対象となる CAD レイアウトを指定します |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | 変換される描画スペースを取得または設定します。デフォルトは[`Both`](../cadlayoutscope/both)で、変換を制限しません。[`LayoutNames`](./layoutnames) が指定されている場合は無視されます。これは明示的なレイアウト名が常に優先されるためです。`null` 値は[`Both`](../cadlayoutscope/both)として扱われます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
