---
title: "GisFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "GIS ドキュメントを定義します。以下のファイルタイプが含まれます Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /ja/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

GIS ドキュメントを定義します。以下のファイルタイプが含まれます: [`Shp`](./shp)。[`GeoJson`](./geojson)。[`GeoJsonSeq`](./geojsonseq)。[`Gdb`](./gdb)。[`Gml`](./gml)。[`Kml`](./kml)。[`Kmz`](./kmz)。[`Gpx`](./gpx)。[`TopoJson`](./topojson)。[`Osm`](./osm)。

```csharp
public sealed class GisFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [GisFileType](gisfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI のファイルジオデータベース（FileGDB）は、フォルダー内のファイル群で、フィーチャ データセット、フィーチャ クラス、関連テーブルなどの地理空間データを保持します。.gdb ファイルと同じディレクトリに特定の他のファイルを配置しておく必要があります。このファイル形式の詳細は[こちら](https://docs.fileformat.com/database/gdb/)をご覧ください。 |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON は、地理的特徴とそれらの非空間属性を表すために設計された JSON ベースのフォーマットです。このフォーマットは、さまざまな JSON（JavaScript Object Notation）オブジェクトとそれらの結合方法を定義します。JSON フォーマットは、地理的特徴、その空間範囲、およびプロパティに関する総合的な情報を表します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/gis/geojson/)をご覧ください。 |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence は、1つの包括的なドキュメントではなく、独立した GeoJSON レコードのストリームで、各レコードは改行または RS 制御文字で区切られます。これは、時間とともに追記されるフィードで使用され、書き込み開始時にコレクションの終了が分からない場合に適しています。 |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML は Geography Markup Language の略で、Open Geospatial Consortium（OGC）が開発した XML 仕様に基づいています。このフォーマットは、さまざまなファイル形式間での地理データ機能の交換のために使用されます。また、地理システムのモデリング言語およびインターネット上の地理取引のオープン交換フォーマットとしても機能します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/gis/gml/)をご覧ください。 |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | .GPX 拡張子のファイルは、インターネット上のアプリケーションやウェブサービス間で GPS データを交換するための GPS Exchange フォーマットを表します。軽量な XML ファイル形式で、ウェイポイント、ルート、トラックなどの GPS データを含み、複数のプログラムでインポートおよび読み取りが可能です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/gis/gpx/)をご覧ください。 |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML（Keyhole Markup Language）は、XML 表記で地理空間情報を含みます。KML として保存されたファイルは、対応する GIS アプリケーションで開くことができます。国際標準として採用されて以来、多くのアプリケーションが KML ファイル形式のサポートを開始しました。KML はタグベースの構造で、入れ子要素と属性を持ちます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/gis/kml/)をご覧ください。 |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ は KML ドキュメントを格納した ZIP アーカイブで、慣例としてアーカイブのルートに doc.kml という名前で配置され、ドキュメントが参照するリソースも含まれます。マークアップを圧縮することが目的で、任意のサイズの KML フィードが大幅に縮小されるため、出版者は KML よりも KMZ を配布します。このファイル形式の詳細は [こちら](https://docs.fileformat.com/gis/kmz/) でご確認ください。 |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | OSM ファイル形式は、OpenStreetMap プロジェクトで地理データを保存するために使用される構造化データ形式です。OSM ファイルは通常 XML 形式で、道路、建物、興味ポイント、その他の地図上の特徴の位置情報などを含みます。このファイル形式の詳細は [こちら](https://docs.fileformat.com/gis/osm/) でご確認ください。 |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP は ESRI Shapefile の表現に使用される主要なファイルタイプの一つの拡張子です。ベクトルデータの形で地理空間情報を表し、地理情報システム (GIS) アプリケーションで使用されます。このファイル形式の詳細は [こちら](https://docs.fileformat.com/gis/shp/) でご確認ください。 |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON はトポロジーをエンコードする GeoJSON の拡張です。ジオメトリを個別に表すのではなく、TopoJSON ファイル内のジオメトリはアークと呼ばれる共有線分から組み合わされています。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
