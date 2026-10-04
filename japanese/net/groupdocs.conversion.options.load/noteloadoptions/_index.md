---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "One ドキュメントの読み込みオプション。"
type: docs
weight: 2680
url: /ja/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

One ドキュメントの読み込みオプション。

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | 新しい [`NoteLoadOptions`](../noteloadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Note ドキュメントのデフォルトフォントです。フォントが見つからない場合は以下のフォントが使用されます。 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Note ドキュメントを変換する際に特定のフォントを置き換えます。 |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | 保護されたドキュメントの保護を解除するためのパスワードを設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
