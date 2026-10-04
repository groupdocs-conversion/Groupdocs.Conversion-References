---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Email ファイルタイプへの変換オプションです。"
type: docs
weight: 1800
url: /ja/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Email ファイルタイプへの変換オプションです。

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | 新しいインスタンスの [`EmailConvertOptions`](../emailconvertoptions) クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | メール添付ファイルのカスタム処理を扱うデリゲートです。デリゲートは添付ファイル名、コンテンツタイプ、元の添付ストリームをパラメーターとして受け取り、変更された添付ストリームを返します。 |
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
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
