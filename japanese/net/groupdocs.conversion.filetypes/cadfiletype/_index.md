---
title: "CadFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "CAD（Computer Aided Design）ドキュメントを定義し、3Dグラフィックファイル形式で使用され、2Dまたは3Dの設計を含む可能性があります。以下のタイプが含まれます Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. CAD形式の詳細はここをご覧くださいhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /ja/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

CAD（Computer Aided Design）ドキュメントを定義し、3Dグラフィックファイル形式で使用され、2Dまたは3Dの設計を含む可能性があります。以下のタイプが含まれます: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). CAD形式の詳細は[こちら](https://wiki.fileformat.com/cad)をご覧ください。

```csharp
public sealed class CadFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [CadFileType](cadfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format ファイル。3Dパッケージ設計やその他のモデルデータを含む CAD ファイルで、ダイカッティング装置などの CAD/CAM 機械で処理・切断できます。 |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN（Design）ファイルは、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/dgn)をご覧ください。 |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format（DWF）は、閲覧、レビュー、印刷用に圧縮された形式で 2D/3D 図面を表現します。設計データの一部としてグラフィックとテキストを含み、圧縮形式によりファイルサイズを削減します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/dwf)をご覧ください。 |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX ファイルは、Autodesk の CAD ソフトウェアで作成された 2D または 3D 図面です。DWFx 形式で保存され、.DWF ファイルに似ていますが、Microsoft の XML Paper Specification（XPS）を使用してフォーマットされています。 |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | DWG 拡張子のファイルは、2D および 3D 設計データを格納するための独自のバイナリファイルです。ASCII ファイルである DXF と同様に、DWG は CAD（Computer Aided Design）図面のバイナリファイル形式を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/dwg)をご覧ください。 |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | DWT ファイルは、AutoCAD の図面テンプレートで、DWG ファイルとして保存できる図面を作成する際の出発点として使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/dwt)をご覧ください。 |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF（Drawing Interchange Format、または Drawing Exchange Format）は、AutoCAD 図面ファイルのタグ付きデータ表現です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/dxf)をご覧ください。 |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | IFC 拡張子のファイルは、建築オブジェクトとそのプロパティのインポート・エクスポートの国際標準を確立する Industry Foundation Classes（IFC）ファイル形式を指します。このファイル形式は、異なるソフトウェア間の相互運用性を提供します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/ifc)をご覧ください。 |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs ドキュメント形式 |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT ファイル形式は、Autodesk 社が導入したベクターベースのプロッターファイルで、特定の CAD ファイルに関する情報を含みます。プロットの詳細は生産において高い精度と正確さが求められ、PLT ファイルはすべての画像を点ではなく線で印刷するため、これを保証します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/plt)をご覧ください。 |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL（stereolithography の略）は、3 次元表面ジオメトリを表す汎用的なファイル形式です。この形式は、ラピッドプロトタイピング、3D プリント、コンピュータ支援製造などのさまざまな分野で使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/stl)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
