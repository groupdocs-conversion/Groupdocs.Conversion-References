---
title: "PresentationFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "スライド、図形、テキスト、アニメーション、ビデオ、オーディオ、埋め込みオブジェクトなどのプレゼンテーションデータを収容するレコードのコレクションを保存するプレゼンテーションファイル形式を表します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/presentationfiletype/
is_root: false
weight: 160
---


## PresentationFileType class

スライド、図形、テキスト、アニメーション、ビデオ、オーディオ、埋め込みオブジェクトなどのプレゼンテーションデータを収容するレコードのコレクションを保存するプレゼンテーションファイル形式を表します。

以下のファイルタイプが含まれます:
- [`PresentationFileType.odp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/)
- [`PresentationFileType.otp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/)
- [`PresentationFileType.pot`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/)
- [`PresentationFileType.potm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/)
- [`PresentationFileType.potx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/)
- [`PresentationFileType.pps`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/)
- [`PresentationFileType.ppsm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/)
- [`PresentationFileType.ppsx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/)
- [`PresentationFileType.ppt`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/)
- [`PresentationFileType.pptm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/)
- [`PresentationFileType.pptx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/).

プレゼンテーション形式の詳細は https://wiki.fileformat.com/presentation をご覧ください。

PresentationFileType 型は以下のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/__init__/) | シリアル化用に PresentationFileType を初期化します。 |

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
| [PPT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/) | .PPT 拡張子のファイルは、スライドのコレクションで構成され、スライドショーとして表示される PowerPoint ファイルです。Microsoft PowerPoint 97-2003 が使用するバイナリファイル形式を指定しています。このファイル形式の詳細はここをご覧ください。 |
| [PPS](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/) | PPS（PowerPoint Slide Show）ファイルは、Microsoft PowerPoint を使用してスライドショー目的で作成されます。PPS ファイルの読み取りおよび作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細はここをご覧ください。 |
| [PPTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/) | PPTX 拡張子のファイルは、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。従来のバイナリ形式 PPT と異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーションファイル形式に基づいています。このファイル形式の詳細はここをご覧ください。 |
| [PPSX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/) | PPSX、Power Point Slide Show ファイルは、Microsoft PowerPoint 2007 以降でスライドショー目的に作成されます。このファイル形式の詳細については、こちらをご覧ください。 |
| [ODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/) | ODP 拡張子のファイルは、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーションファイル形式を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [OTP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/) | .OTP 拡張子のファイルは、OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーションテンプレートファイルを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [POTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/) | .POTX 拡張子のファイルは、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレートプレゼンテーションを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [POT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/) | .POT 拡張子のファイルは、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレートファイルを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [POTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/) | POTM 拡張子のファイルは、マクロに対応した Microsoft PowerPoint テンプレートファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーションファイルを作成する際に使用できるデフォルト設定が含まれています。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/) | PPTM 拡張子のファイルは、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーションファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPSM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/) | PPSM 拡張子のファイルは、Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショーファイル形式を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [FODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/fodp/) | FODP 拡張子のファイルは、OpenDocument フラット XML プレゼンテーションを表します。プレゼンテーションファイルは OpenDocument 形式で保存されますが、標準の .ODP ファイルが使用する .ZIP コンテナの代わりにフラット XML 形式で保存されます。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
