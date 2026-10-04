---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "財務ドキュメントを定義します。以下のタイプが含まれます：Xbrl./financefiletype/xbrl、IXbrl./financefiletype/ixbrl、Ofx./financefiletype/ofx。この財務形式の詳細は[こちら](https://docs.fileformat.com/finance/)をご覧ください。"
type: docs
weight: 1140
url: /ja/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

財務ドキュメントを定義します。次のタイプが含まれます：[`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) 財務フォーマットの詳細は[こちら](https://docs.fileformat.com/finance/)をご覧ください。

```csharp
public sealed class FinanceFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [FinanceFileType](financefiletype)() | シリアライズ コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイルファミリー |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) を実装します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | iXBRL の内部では、XBRL の内容が XML タグを使用した xHTML ファイル形式でラップされています。XBRL と同様に、iXBRL ファイルのルート要素です。XHTML 形式は、その内容をさまざまなドキュメントタイプやモジュールのコレクションとして表現します。XHTML のすべてのファイルは XML ファイル形式に基づいており、XML 文書標準に準拠しています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/finance/ixbrl/)をご覧ください。 |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) は、Microsoft の Open Financial Connectivity (OFC) と Intuit の Open Exchange ファイル形式から派生した、金融情報の交換用データストリーム形式です。このファイル形式の詳細は[こちら](https://en.wikipedia.org/wiki/Open_Financial_Exchange)をご覧ください。 |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL は、世界中で広く使用されているデジタルビジネスレポーティングのためのオープンな国際標準です。XML ベースの言語で、タグとして知られる XBRL 要素を使用してビジネスデータの各項目を記述し、レポートのソートや分析のためのデータを構成します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/finance/xbrl/)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
