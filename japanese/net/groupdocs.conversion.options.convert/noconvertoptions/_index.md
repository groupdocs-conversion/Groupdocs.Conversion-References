---
title: "NoConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換処理を行わずにソースドキュメントをコピーするようコンバータに指示する特別な変換オプションクラス"
type: docs
weight: 2020
url: /ja/net/groupdocs.conversion.options.convert/noconvertoptions/
---
## NoConvertOptions class

変換プロセッサに対し、ソースドキュメントを処理せずにコピーするよう指示する特別な変換オプションクラスです。

```csharp
public sealed class NoConvertOptions : ConvertOptions<FileType>
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [NoConvertOptions](noconvertoptions)() | デフォルト形式で [`NoConvertOptions`](../noconvertoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
