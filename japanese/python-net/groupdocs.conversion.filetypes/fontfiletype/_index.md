---
title: "FontFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "フォントドキュメントタイプを表します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/fontfiletype/
is_root: false
weight: 100
---


## FontFileType class

フォントドキュメントタイプを表します。

以下のタイプが含まれます:
- [`FontFileType.ttf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf/)
- [`FontFileType.eot`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot/)
- [`FontFileType.otf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf/)
- [`FontFileType.cff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff/)
- [`FontFileType.type1`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1/)
- [`FontFileType.woff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff/)
- [`FontFileType.woff2`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2/)

フォント形式の詳細は https://docs.fileformat.com/font/ をご覧ください。

FontFileType 型は以下のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/__init__/) | シリアル化用に FontFileType を初期化します。 |

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
| [TTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf/) | .ttf 拡張子のファイルは、TrueType 仕様のフォント技術に基づくフォントファイルです。もともと Apple Computer, Inc が Mac OS 用に設計・発売し、後に Microsoft が Windows OS 用に採用しました。このファイル形式の詳細はここをご覧ください。 |
| [EOT](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot/) | .eot 拡張子のファイルは、ドキュメントに埋め込まれる OpenType フォントです。主にウェブページなどのウェブファイルで使用されます。Microsoft が作成し、PowerPoint の .pps プレゼンテーションファイルを含む Microsoft 製品でサポートされています。このファイル形式の詳細はここをご覧ください。 |
| [OTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf/) | .otf 拡張子のファイルは OpenType フォント形式を指します。OTF フォント形式はスケーラビリティが高く、デジタルタイポグラフィ向けに TTF 形式の既存機能を拡張しています。Microsoft と Adobe によって開発され、OTF は PostScript と TrueType フォント形式の機能を組み合わせています。このファイル形式の詳細はここをご覧ください。 |
| [CFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff/) | .cff 拡張子のファイルは Compact Font Format（CFF）で、PostScript Type 1 または CIDFont とも呼ばれます。CFF は複数のフォントを単一のユニット（FontSet）として格納するコンテナとして機能します。このファイル形式の詳細はここをご覧ください。 |
| [TYPE1](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1/) | Type 1 フォントは、Adobe の旧技術で、デスクトップ出版ソフトウェアや PostScript 対応プリンターで広く使用されていました。多くの最新プラットフォームやウェブブラウザ、モバイル OS ではサポートされていませんが、一部の OS では依然としてサポートされています。このファイル形式の詳細はここをご覧ください。 |
| [WOFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff/) | .woff 拡張子のファイルは、Web Open Font Format（WOFF）に基づくウェブフォントファイルです。TrueType（.TTF）または OpenType（.OTT）フォントタイプのいずれかに基づく、フォーマット固有の圧縮コンテナを持ちます。このファイル形式の詳細はここをご覧ください。 |
| [WOFF2](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2/) | .woff 拡張子のファイルは、Web Open Font Format（WOFF）に基づくウェブフォントファイルです。TrueType（.TTF）または OpenType（.OTT）フォントタイプのいずれかに基づく、フォーマット固有の圧縮コンテナを持ちます。このファイル形式の詳細はここをご覧ください。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
