---
title: "CadFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "3D グラフィックファイル形式で使用され、2D または 3D 設計を含む可能性がある CAD ドキュメント（Computer Aided Design）を表します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/cadfiletype/
is_root: false
weight: 20
---


## CadFileType class

3D グラフィックファイル形式で使用され、2D または 3D 設計を含む可能性がある CAD ドキュメント（Computer Aided Design）を表します。

以下のタイプが含まれます:
- [`CadFileType.cf2`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/cf2/)
- [`CadFileType.dgn`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dgn/)
- [`CadFileType.dwf`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwf/)
- [`CadFileType.dwfx`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwfx/)
- [`CadFileType.dwg`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwg/)
- [`CadFileType.dwt`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwt/)
- [`CadFileType.dxf`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dxf/)
- [`CadFileType.ifc`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/ifc/)
- [`CadFileType.igs`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/igs/)
- [`CadFileType.plt`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/plt/)
- [`CadFileType.stl`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/stl/)

CAD フォーマットの詳細は (https://wiki.fileformat.com/cad) をご覧ください。

CadFileType 型は以下のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/__init__/) | シリアライズ用に新しい CadFileType インスタンスを初期化します。 |

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
| [DXF](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dxf/) | DXF（Drawing Interchange Format、または Drawing Exchange Format）は、AutoCAD 図面ファイルのタグ付きデータ表現です。このファイル形式の詳細はここでご覧ください。 |
| [DWG](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwg/) | DWG 拡張子のファイルは、2D および 3D 設計データを格納するために使用される独自のバイナリファイルを表します。ASCII ファイルである DXF と同様に、DWG は CAD（Computer Aided Design）図面のバイナリファイル形式です。このファイル形式の詳細はここでご覧ください。 |
| [DGN](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dgn/) | DGN（Design）ファイルは、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。このファイル形式の詳細はここでご覧ください。 |
| [DWF](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwf/) | Design Web Format（DWF）は、設計ファイルの閲覧、レビュー、印刷のために圧縮形式で 2D/3D 図面を表します。設計データの一部としてグラフィックとテキストを含み、圧縮形式によりファイルサイズを削減します。このファイル形式の詳細はここでご覧ください。 |
| [STL](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/stl/) | STL（stereolithrography の略）は、3 次元表面ジオメトリを表す汎用ファイル形式です。この形式は、ラピッドプロトタイピング、3D プリント、コンピュータ支援製造などのさまざまな分野で使用されています。このファイル形式の詳細はここでご覧ください。 |
| [IFC](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/ifc/) | IFC 拡張子のファイルは、建築オブジェクトとそのプロパティのインポート・エクスポートのための国際標準を確立する Industry Foundation Classes（IFC）ファイル形式を指します。このファイル形式は、異なるソフトウェア間の相互運用性を提供します。このファイル形式の詳細はここでご覧ください。 |
| [PLT](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/plt/) | PLT ファイル形式は Autodesk, Inc. が導入したベクターベースのプロッターファイルで、特定の CAD ファイルに関する情報を含みます。プロットの詳細は生産において正確さと精度が求められ、PLT ファイルはすべての画像をドットではなく線で印刷するため、これを保証します。このファイル形式の詳細はここでご覧ください。 |
| [IGS](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/igs/) | Igs ドキュメント形式 |
| [DWT](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwt/) | DWT ファイルは、DWG ファイルとして保存できる図面を作成するための出発点として使用される AutoCAD 図面テンプレートファイルです。このファイル形式の詳細はここでご覧ください。 |
| [DWFX](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwfx/) | DWFX ファイルは Autodesk の CAD ソフトウェアで作成された 2D または 3D 図面です。これは DWFx 形式で保存され、.DWF ファイルに似ていますが、Microsoft の XML Paper Specification（XPS）を使用してフォーマットされています。 |
| [CF2](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/cf2/) | Common File Format ファイル。3D パッケージ設計やその他のモデルデータを含む CAD ファイルで、ダイカッティング装置などの CAD/CAM 機械で処理・切断できます。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
