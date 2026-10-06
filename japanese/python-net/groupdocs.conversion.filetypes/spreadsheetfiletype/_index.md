---
title: "SpreadsheetFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "スプレッドシートドキュメントを定義します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/
is_root: false
weight: 190
---


## SpreadsheetFileType class

スプレッドシートドキュメントを定義します。

以下のファイルタイプが含まれます:
- [`SpreadsheetFileType.csv`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/csv/)
- [`SpreadsheetFileType.fods`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/fods/)
- [`SpreadsheetFileType.ods`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ods/)
- [`SpreadsheetFileType.ots`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ots/)
- [`SpreadsheetFileType.tsv`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/tsv/)
- [`SpreadsheetFileType.xlam`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlam/)
- [`SpreadsheetFileType.xls`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xls/)
- [`SpreadsheetFileType.xlsb`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb/)
- [`SpreadsheetFileType.xlsm`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm/)
- [`SpreadsheetFileType.xlsx`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx/)
- [`SpreadsheetFileType.xlt`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlt/)
- [`SpreadsheetFileType.xltm`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltm/)
- [`SpreadsheetFileType.xltx`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltx/)

スプレッドシート形式の詳細は https://wiki.fileformat.com/spreadsheet. でご確認ください。

SpreadsheetFileType 型は以下のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/__init__/) | シリアライズ用に SpreadsheetFileType を初期化します。 |

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
| [XLS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xls/) | XLS は Excel バイナリファイル形式を表します。この形式のファイルは Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシートプログラムでも作成できます。こちらでこのファイル形式の詳細を確認してください。 |
| [XLSX](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx/) | XLSX は Microsoft Office 2007 のリリースとともに Microsoft が導入した、Microsoft Excel ドキュメントの代表的な形式です。こちらでこのファイル形式の詳細を確認してください。 |
| [XLSM](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm/) | XLSM はマクロをサポートするスプレッドシートファイルの一種です。こちらでこのファイル形式の詳細を確認してください。 |
| [XLSB](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb/) | XLSB ファイル形式は Excel バイナリファイル形式を指定し、Excel ワークブックの内容を定義するレコードと構造の集合です。こちらでこのファイル形式の詳細を確認してください。 |
| [ODS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ods/) | ODS 拡張子のファイルは、ユーザーが編集可能な OpenDocument スプレッドシートドキュメント形式を表します。データは ODF ファイル内に行と列として保存されます。こちらでこのファイル形式の詳細を確認してください。 |
| [OTS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ots/) | .ots 拡張子のファイルは、Apache OpenOffice に含まれる Calc アプリケーションで作成された OpenDocument スプレッドシートテンプレートファイルです。Calc は Microsoft Office の Excel に相当するソフトウェアです。こちらでこのファイル形式の詳細を確認してください。 |
| [XLTX](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltx/) | XLTX ファイルは Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートを表します。これを使用して標準テンプレートファイルを作成し、XLTX ファイルで指定された設定と同じ設定を持つ XLSX ファイルを生成できます。こちらでこのファイル形式の詳細を確認してください。 |
| [XLT](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlt/) | .XLT 拡張子のファイルは、Microsoft Office スイートの一部であるスプレッドシートアプリケーション Microsoft Excel で作成されたテンプレートファイルです。Microsoft Office 97-2003 は新規 XLT ファイルの作成および開くことをサポートしていました。こちらでこのファイル形式の詳細を確認してください。 |
| [XLTM](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltm/) | XLTM 拡張子は、Microsoft Excel が生成するマクロ対応テンプレートファイルを表します。XLTM ファイルは構造上 XLTX と似ていますが、XLTX はマクロ付きテンプレートの作成をサポートしていません。こちらでこのファイル形式の詳細を確認してください。 |
| [TSV](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/tsv/) | タブ区切り値（TSV）ファイル形式は、タブで区切られたプレーンテキスト形式のデータを表します。こちらでこのファイル形式の詳細を確認してください。 |
| [XLAM](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlam/) | XLAM はスプレッドシートに新しい機能を追加するためのマクロ対応アドインファイルです。アドインは追加のコードを実行し、スプレッドシートに追加機能を提供する補助プログラムです。こちらでこのファイル形式の詳細を確認してください。 |
| [CSV](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/csv/) | CSV（カンマ区切り値）拡張子のファイルは、カンマで区切られたデータレコードを含むプレーンテキストファイルを表します。こちらでこのファイル形式の詳細を確認してください。 |
| [FODS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/fods/) | .fods 拡張子のファイルは、行と列にデータを格納する OpenDocument スプレッドシートドキュメント形式の一種です。この形式は OASIS が公開・管理する ODF 1.2 仕様の一部として定義されています。こちらでこのファイル形式の詳細を確認してください。 |
| [DIF](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/dif/) | DIF は Data Interchange Format の略で、異なるアプリケーション間でスプレッドシートデータのインポート/エクスポートに使用されます。対象には Microsoft Excel、OpenOffice Calc、StarCalc など多数があります。こちらでこのファイル形式の詳細を確認してください。 |
| [SXC](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/sxc/) | SXC（Sun XML Calc）ファイル形式は OpenOffice.org というオフィススイートに属します。この形式は XML ベースのスプレッドシートファイル形式で、ユーザーのスプレッドシートニーズに対応します。SXC 形式は数式、関数、マクロ、チャート、DataPilot をサポートしています。こちらでこのファイル形式の詳細を確認してください。 |
| [NUMBERS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/numbers/) | .numbers 拡張子のファイルはスプレッドシートファイルタイプに分類され、.xlsx ファイルと似ていますが、Numbers ファイルは Apple の iWork Numbers スプレッドシートソフトウェアで作成されます。こちらでこのファイル形式の詳細を確認してください。 |
| [FLAT_OPC](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/flat_opc/) | Flat OPC Excel は、ZIP パッケージではなくフラットな XML ファイルに保存された Office Open XML SpreadsheetML です。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
