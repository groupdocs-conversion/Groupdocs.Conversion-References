---
title: WordProcessingFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: プレーン テキストまたはリッチ テキスト形式のユーザー情報を含むワープロ ファイルを定義しますプレーン テキスト ファイル形式には書式設定されていないテキストが含まれておりフォントやページ設定などは適用できません対照的にリッチ テキスト ファイル形式ではフォントの種類スタイル 太字斜体下線などページの余白見出し箇条書きと数字およびその他のいくつかの書式設定機能の設定などの書式設定オプションを使用できます 次のファイル タイプが含まれます Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Log . ワード プロセッシング形式の詳細ここhttps//wiki.fileformat.com/wordprocessing.
type: docs
weight: 1090
url: /ja/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

プレーン テキストまたはリッチ テキスト形式のユーザー情報を含むワープロ ファイルを定義します。プレーン テキスト ファイル形式には書式設定されていないテキストが含まれており、フォントやページ設定などは適用できません。対照的に、リッチ テキスト ファイル形式では、フォントの種類、スタイル (太字、斜体、下線など)、ページの余白、見出し、箇条書きと数字、およびその他のいくつかの書式設定機能の設定などの書式設定オプションを使用できます。 次のファイル タイプが含まれます: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt). [`Md`](./md). Log . ワード プロセッシング形式の詳細[ここ](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | シリアル化コンストラクター |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイル family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他のオブジェクトと比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | 拡張子が .doc のファイルは、Microsoft Word またはその他のワード プロセッシング ドキュメントによって生成されたドキュメントをバイナリ ファイル形式で表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/doc) |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docm) |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年の Microsoft Office 2007 のリリースで導入されたこの新しいドキュメント形式の構造は、プレーン バイナリから XML とバイナリ ファイルの組み合わせに変更されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docx) |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | 拡張子が .DOT のファイルは、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOC または DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dot) |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM 拡張子を持つファイルは、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotm) |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | DOTX 拡張子を持つファイルは、Microsoft Word によって作成されたテンプレート ファイルであり、さらに DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotx) |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown 言語の方言で作成されたテキスト ファイルは、.MD または .MARKDOWN ファイル拡張子で保存されます。 MD ファイルは、インライン テキスト シンボルを含む Markdown 言語を使用するプレーン テキスト形式で保存され、インデント、表の書式設定、フォント、ヘッダーなどのテキストの書式設定方法を定義します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/md) |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT ファイルは、OpenDocument テキスト ファイル形式に基づくワード プロセッシング アプリケーションで作成されたドキュメントのタイプです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/odt) |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT 拡張子を持つファイルは、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されたテンプレート ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/ott) |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft によって導入および文書化されたリッチ テキスト形式 (RTF) は、アプリケーション内で使用するために書式設定されたテキストとグラフィックスをエンコードする方法を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/rtf) |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | 拡張子が .TXT のファイルは、行形式のプレーン テキストを含むテキスト ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/txt) |

### 関連項目

* class [FileType](../filetype)
* 名前空間 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
