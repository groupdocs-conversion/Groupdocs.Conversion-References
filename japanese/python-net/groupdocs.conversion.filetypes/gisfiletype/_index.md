---
title: "GisFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "GIS ドキュメントタイプの定義です。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

GIS ドキュメントタイプの定義です。

次のファイルタイプが含まれます：[`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

GisFileType 型は次のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | シリアライズ用に GisFileType を初期化します。 |

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
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP は ESRI Shapefile の表現に使用される主要なファイルタイプの一つの拡張子です。ベクトルデータの形で地理空間情報を表し、地理情報システム（GIS）アプリケーションで使用されます。このファイル形式の詳細はここをご覧ください。 |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON は、地理的特徴とその非空間属性を表すために設計された JSON ベースのフォーマットです。このフォーマットは、さまざまな JSON（JavaScript Object Notation）オブジェクトとそれらの結合方法を定義します。JSON フォーマットは、地理的特徴、その空間範囲、およびプロパティに関する総合的な情報を表します。このファイル形式の詳細はここをご覧ください。 |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | ESRI ファイルジオデータベース（FileGDB）は、ディスク上のフォルダー内にあるファイルの集合で、フィーチャ データセット、フィーチャ クラス、関連テーブルなどの関連する地理空間データを保持します。動作させるには、.gdb ファイルと同じディレクトリに特定の他のファイルを併せて配置する必要があります。このファイル形式の詳細はここをご覧ください。 |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML は、Open Geospatial Consortium (OGC) が策定した XML 仕様に基づく Geography Markup Language の略称です。この形式は、異なるファイル形式間での地理データ機能の交換のために地理データを保存するために使用されます。また、地理システムのモデリング言語として、インターネット上の地理取引のオープンな交換フォーマットとしても機能します。このファイル形式の詳細はここをご覧ください。 |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML（Keyhole Markup Language）は、XML 表記で地理空間情報を含んでいます。KML 形式で保存されたファイルは、対応していれば地理情報システム（GIS）アプリケーションで開くことができます。国際標準として採用された後、多くのアプリケーションが KML ファイル形式のサポートを開始しました。KML は、入れ子になった要素と属性を持つタグベースの構造を使用します。このファイル形式の詳細はここをご覧ください。 |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | GPX 拡張子のファイルは、インターネット上のアプリケーションやウェブサービス間で GPS データを交換するための GPS Exchange フォーマットを表します。これは、ウェイポイント、ルート、トラックなどの GPS データを含む軽量な XML ファイル形式で、複数のプログラムでインポートおよび読み取りが可能です。このファイル形式の詳細はここをご覧ください。 |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON は GeoJSON の拡張で、トポロジーをエンコードします。個別にジオメトリを表すのではなく、TopoJSON ファイル内のジオメトリは「アーク」と呼ばれる共有線分から組み合わされています。 |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | OSM ファイル形式は、OpenStreetMap プロジェクトで地理データを保存するために使用される構造化データ形式です。OSM ファイルは通常 XML 形式で、道路、建物、興味ポイント、その他の地図上の特徴の位置情報などを含みます。このファイル形式の詳細はここをご覧ください。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
