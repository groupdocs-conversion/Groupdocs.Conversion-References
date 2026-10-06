---
title: "FinanceFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "金融ドキュメントタイプを定義します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

金融ドキュメントタイプを定義します。

次のタイプが含まれます: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/)。金融フォーマットの詳細は以下をご覧ください: https://docs.fileformat.com/finance/.

FinanceFileType 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | シリアル化用に FinanceFileType を初期化します。 |

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
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL は、世界中で広く使用されているデジタルビジネスレポーティングのためのオープンな国際標準です。XML ベースの言語で、XBRL 要素（タグと呼ばれる）を使用してビジネスデータの各項目を記述し、レポートの分類や分析のためのデータを構成します。こちらでこのファイル形式の詳細をご覧ください。 |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | iXBRL の内部では、XBRL の内容が XML タグを使用する xHTML ファイル形式でラップされています。XBRL と同様に、iXBRL ファイルのルート要素です。XHTML 形式は、その内容をさまざまな文書タイプやモジュールのコレクションとして表現します。XHTML のすべてのファイルは XML ファイル形式に基づき、XML 文書標準に準拠しています。こちらでこのファイル形式の詳細をご覧ください。 |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange（OFX）は、Microsoft の Open Financial Connectivity（OFC）および Intuit の Open Exchange ファイル形式から発展した、金融情報を交換するためのデータストリーム形式です。こちらでこのファイル形式の詳細をご覧ください。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
