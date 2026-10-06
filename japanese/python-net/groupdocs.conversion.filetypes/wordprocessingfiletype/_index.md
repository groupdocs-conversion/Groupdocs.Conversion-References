---
title: "WordProcessingFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "WordProcessingFileType クラスは、プレーンテキストとリッチテキストのバリエーションを含むワードプロセッシングファイル形式を定義します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/
is_root: false
weight: 230
---


## WordProcessingFileType class

WordProcessingFileType クラスは、プレーンテキストとリッチテキストのバリエーションを含むワードプロセッシングファイル形式を定義します。

プレーンテキストファイルは、フォントやページ設定が適用されていない未フォーマットのテキストを含みます。リッチテキストファイルは、フォントタイプ、スタイル（太字、斜体、下線）、ページ余白、見出し、箇条書き、番号付けなどの書式設定オプションをサポートします。

- [`WordProcessingFileType.Doc`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/doc/)
- [`WordProcessingFileType.Docm`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docm/)
- [`WordProcessingFileType.Docx`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/)
- [`WordProcessingFileType.Dot`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dot/)
- [`WordProcessingFileType.Dotm`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotm/)
- [`WordProcessingFileType.Dotx`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotx/)
- [`WordProcessingFileType.Odt`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/odt/)
- [`WordProcessingFileType.Ott`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/ott/)
- [`WordProcessingFileType.Rtf`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/rtf/)
- [`WordProcessingFileType.Txt`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/txt/)
- [`WordProcessingFileType.Md`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/md/)

Word Processing フォーマットの詳細はここをご覧ください: https://wiki.fileformat.com/word-processing

WordProcessingFileType 型は以下のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/__init__/) | シリアライズ用に WordProcessingFileType を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 現在のオブジェクトを他と比較します。（[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) によって定義された等価比較を実装します。（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | （[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 提供されたファイル拡張子の FileType を取得します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 指定された file_name の FileType を返します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 提供されたドキュメントストリームの FileType を返します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | （[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | デフォルトのハッシュ関数を提供します。（[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | ファイルタイプの文字列表現です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | ファイルタイプの説明です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | ファイル拡張子です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | ファイルファミリーです。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | ファイル形式です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DOC](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/doc/) | .doc 拡張子のファイルは、Microsoft Word やその他のワードプロセッサで生成されたバイナリ形式のドキュメントを表します。このファイル形式の詳細はここをご覧ください。 |
| [DOCM](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docm/) | DOCM ファイルは、Microsoft Word 2007 以降で作成されたマクロ実行可能なドキュメントです。このファイル形式の詳細はここをご覧ください。 |
| [DOCX](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/) | DOCX は、Microsoft Word ドキュメントのよく知られた形式です。Microsoft Office 2007 のリリースとともに 2007 年に導入され、この新しいドキュメント形式の構造は、従来のバイナリ形式から XML とバイナリファイルの組み合わせに変更されました。このファイル形式の詳細はここをご覧ください。 |
| [DOT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dot/) | .DOT 拡張子のファイルは、Microsoft Word が作成したテンプレートファイルで、今後の DOC または DOCX ファイル生成のために事前に書式設定された設定を持ちます。このファイル形式の詳細はここをご覧ください。 |
| [DOTM](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotm/) | DOTM 拡張子のファイルは、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細はここをご覧ください。 |
| [DOTX](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotx/) | .DOTX 拡張子のファイルは、Microsoft Word が作成したテンプレートファイルで、今後の DOCX ファイル生成のために事前に書式設定された設定を持ちます。このファイル形式の詳細はここをご覧ください。 |
| [RTF](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/rtf/) | Microsoft によって導入・文書化されたリッチテキスト形式（RTF）は、アプリケーション内で使用するための書式付きテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細はここをご覧ください。 |
| [ODT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/odt/) | ODT ファイルは、OpenDocument Text ファイル形式に基づくワードプロセッシングアプリケーションで作成された文書タイプです。このファイル形式の詳細はここをご覧ください。 |
| [OTT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/ott/) | OTT 拡張子のファイルは、OASIS の OpenDocument 標準フォーマットに準拠してアプリケーションによって生成されたテンプレート文書を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [TXT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/txt/) | .TXT 拡張子のファイルは、行形式のプレーンテキストを含むテキスト文書を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [MD](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/md/) | Markdown 言語の方言で作成されたテキストファイルは、.MD または .MARKDOWN 拡張子で保存されます。MD ファイルは、インラインテキスト記号を含む Markdown 言語を使用したプレーンテキスト形式で保存され、インデントや表の書式、フォント、ヘッダーなど、テキストの書式設定方法を定義します。このファイル形式の詳細については、こちらをご覧ください。 |
| [FLAT_OPC](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/flat_opc/) | Flat OPC Word は、ZIP パッケージではなくフラットな XML ファイルに格納された Office Open XML WordprocessingML です。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # 入力ドキュメントで Converter をインスタンス化します
    with Converter("./business-plan.docx") as converter:
        # 変換オプションを定義します；デフォルトの出力形式は DOCX です
        word_convert_options = WordProcessingConvertOptions()
        # フォーマットファミリ内の出力形式を DOCX から TXT に変更します
        word_convert_options.format = WordProcessingFileType.Txt

        # 入力ドキュメントを TXT に変換します
        converter.convert("./business-plan.txt", word_convert_options)

if __name__ == "__main__":
    specify_output_format()
```

### Guides
`WordProcessingFileType` を使用するタスク ガイド：

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
