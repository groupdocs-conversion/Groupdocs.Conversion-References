---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "PDFドキュメントがワードプロセッシングドキュメントに変換される方法を制御できるようにします。"
type: docs
weight: 2160
url: /ja/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

PDFドキュメントがワードプロセッシングドキュメントに変換される方法を制御できるようにします。

```csharp
public sealed class PdfRecognitionMode : Enumeration
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
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | フル認識モードでは、エンジンがグルーピングと多層解析を実行し、元の文書作成者の意図を復元して最大限に編集可能な文書を生成します。デメリットとして、出力文書が元の PDF ファイルと見た目が異なる場合があります。 |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | このモードは高速で、PDF ファイルの元の外観を最大限に保持するのに適していますが、生成されたドキュメントの編集可能性は制限される可能性があります。元の PDF ファイルで視覚的にグループ化されたテキストブロックはすべて、生成されたドキュメント内のテキストボックスに変換されます。これにより、出力ドキュメントは元の PDF ファイルにできるだけ似せることができます。出力ドキュメントは見た目は良いですが、完全にテキストボックスで構成されるため、Microsoft Word でのさらなる編集がかなり困難になる可能性があります。これはデフォルトモードです。 |

### 関連項目

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
