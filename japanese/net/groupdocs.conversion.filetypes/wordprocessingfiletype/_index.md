---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "プレーンテキストまたはリッチテキスト形式でユーザー情報を含むワードプロセッシングファイルを定義します。プレーンテキストのファイル形式は書式設定されていないテキストで、フォントやページ設定などは適用できません。対照的に、リッチテキストのファイル形式はフォントタイプ、スタイル（太字、斜体、下線など）、ページ余白、見出し、箇条書きや番号付けなど、さまざまな書式設定オプションを可能にします。以下のファイルタイプが含まれます Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt Md./wordprocessingfiletype/md. Word Processing フォーマットの詳細は herehttps//wiki.fileformat.com/wordprocessing でご確認ください。"
type: docs
weight: 1280
url: /ja/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

プレーンテキストまたはリッチテキスト形式でユーザー情報を含むワードプロセッシングファイルを定義します。プレーンテキストのファイル形式は書式設定されていないテキストで、フォントやページ設定などは適用できません。対照的に、リッチテキストのファイル形式はフォントタイプ、スタイル（太字、斜体、下線など）、ページ余白、見出し、箇条書きや番号付けなど、さまざまな書式設定オプションを可能にします。以下のファイルタイプが含まれます: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Word Processing フォーマットの詳細は [こちら](https://wiki.fileformat.com/word-processing) でご確認ください。

```csharp
public sealed class WordProcessingFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | .doc 拡張子のファイルは、Microsoft Word または他のワードプロセッシングソフトで生成されたバイナリ形式のドキュメントを表します。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/doc) でご確認ください。 |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM ファイルは、Microsoft Word 2007 以降で作成されたマクロ実行機能を持つドキュメントです。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/docm) でご確認ください。 |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX は Microsoft Word ドキュメントの代表的な形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、この新しいドキュメント形式の構造は従来のバイナリから XML とバイナリファイルの組み合わせに変更されました。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/docx) でご確認ください。 |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT 拡張子のファイルは、Microsoft Word が作成したテンプレートファイルで、今後生成される DOC や DOCX ファイルのために事前に書式設定が施されています。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/dot) でご確認ください。 |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM 拡張子のファイルは、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/dotm) でご確認ください。 |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | .DOTX 拡張子のファイルは、Microsoft Word が作成したテンプレートファイルで、今後生成される DOCX ファイルのために事前に書式設定が施されています。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/dotx) でご確認ください。 |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word は、ZIP パッケージではなくフラットな XML ファイルに格納された Office Open XML WordprocessingML です。 |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown 言語の方言で作成されたテキストファイルは、.MD または .MARKDOWN 拡張子で保存されます。MD ファイルはプレーンテキスト形式で保存され、Markdown 言語を使用し、インラインテキスト記号を含み、インデント、表の書式設定、フォント、ヘッダーなどのテキストの書式方法を定義します。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/word-processing/md) でご確認ください。 |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT ファイルは、OpenDocument テキストファイル形式に基づくワードプロセッシングアプリケーションで作成される文書の種類です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/odt)をご覧ください。 |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT 拡張子のファイルは、OASIS の OpenDocument 標準形式に準拠したアプリケーションで生成されるテンプレート文書を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/ott)をご覧ください。 |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft によって導入・文書化されたリッチテキスト形式 (RTF) は、アプリケーション内で使用するための書式設定されたテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/rtf)をご覧ください。 |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT 拡張子のファイルは、行単位のプレーンテキストを含むテキスト文書を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/txt)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
