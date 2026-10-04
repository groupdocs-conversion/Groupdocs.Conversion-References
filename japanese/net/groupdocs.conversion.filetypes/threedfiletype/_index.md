---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "3D ドキュメントを定義し、次のタイプを含みます Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb 3D フォーマットの詳細はこちらhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /ja/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3D ドキュメントを定義し、次のタイプを含みます: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) 3D フォーマットの詳細は [こちら](https://wiki.fileformat.com/3d)です。

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | AMF ファイルは、オブジェクト記述のためのガイドラインで構成され、付加製造プロセスで使用されます。XML の開始タグで始まり、要素で終了します。この前には XML バージョンとエンコーディングを指定する XML 宣言行があります。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/amf)をご覧ください。 |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase 拡張子のファイルは Autodesk ASCII Scene Export ファイル形式で、シーンの ASCII 表現であり、2D または 3D 情報を含み、Autodesk を使用してシーン データをエクスポートします。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/ase)をご覧ください。 |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE ファイルは Digital Asset Exchange（デジタル資産交換）ファイル形式で、インタラクティブな 3D アプリケーション間でデータを交換するために使用されます。このファイル形式は、COLLADA（COLLAborative Design Activity）XML スキーマに基づいており、グラフィックス ソフトウェア アプリケーション間でデジタル資産を交換するためのオープン標準 XML スキーマです。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/dae)をご覧ください。 |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc 拡張子のファイルは、Google Draco ライブラリで作成された圧縮 3D ファイル形式です。Google は 3D 幾何メッシュと点群を圧縮・伸長するためのオープンソース ライブラリとして Draco を提供しており、3D グラフィックスの保存と転送を改善します。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/drc)をご覧ください。 |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX（FilmBox）は、もともと Kaydara が MotionBuilder 用に開発した人気の 3D ファイル形式です。2006 年に Autodesk Inc に買収され、現在は多くの 3D ツールで使用される主要な 3D 交換フォーマットの一つとなっています。FBX はバイナリ形式と ASCII 形式の両方で利用可能です。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/fbx)をご覧ください。 |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB は、GL Transmission Format（glTF）で保存された 3D モデルのバイナリ ファイル形式表現です。このバイナリ形式は、glTF アセット（JSON、.bin、画像）をバイナリ ブロブに格納します。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/glb)をご覧ください。 |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF（GL Transmission Format）は、3D モデル情報を JSON 形式で保存する 3D ファイル形式です。JSON を使用することで、3D アセットのサイズと、それらを展開・使用するために必要な実行時処理の両方を最小化できます。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/gltf)をご覧ください。 |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT（Jupiter Tessellation）は、Siemens PLM Software が開発した、効率的で業界志向かつ柔軟な ISO 標準化 3D データ形式です。航空宇宙、自動車産業、重機などの機械 CAD 分野では、JT が最も主要な 3D 可視化フォーマットとして使用されています。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/jt)をご覧ください。 |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | .ma 拡張子のファイルは Autodesk Maya アプリケーションで作成された 3D プロジェクト ファイルです。ファイルに関する情報を指定する多数のテキスト コマンドが含まれています。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/ma)をご覧ください。 |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | .mb 拡張子のファイルは Autodesk Maya アプリケーションで作成されたバイナリ プロジェクト ファイルです。ASCII 形式の MA ファイル形式とは異なり、MB ファイルはバイナリ形式で保存されます。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/mb)をご覧ください。 |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ ファイルは Wavefront の Advanced Visualizer アプリケーションで使用され、幾何オブジェクトを定義および保存します。OBJ ファイルにより、幾何データの前方・後方の転送が可能になります。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/obj)をご覧ください。 |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY（Polygon File Format）は、ポリゴンの集合として記述されたグラフィックオブジェクトを保存する 3D ファイル形式です。このファイル形式の目的は、幅広いモデルで利用できるほど汎用的でシンプルかつ扱いやすいファイルタイプを確立することでした。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/ply)をご覧ください。 |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM データファイルは AVEVA PDMS に関連しています。RVM ファイルは AVEVA Plant Design Management System（プラント設計管理システム）のモデル プロジェクト ファイルです。AVEVA の Plant Design Management System（PDMS）は、プロジェクト管理にデータ中心技術を使用する最も人気のある 3D 設計システムです。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/rvm)をご覧ください。 |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds 拡張子のファイルは、Autodesk 3D Studio で使用される 3D Studio（DOS）メッシュ ファイル形式を表します。Autodesk 3D Studio は 1990 年代から 3D ファイル形式市場に参入しており、現在は 3D モデリング、アニメーション、レンダリングに対応する 3D Studio MAX に進化しています。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/3ds)をご覧ください。 |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF（3D Manufacturing Format）は、アプリケーションが 3D オブジェクトモデルをさまざまな他のアプリケーション、プラットフォーム、サービス、プリンターに出力するために使用されます。最新の 3D プリンターでの利用を考慮し、STL など他の 3D ファイル形式の制限や問題を回避するように設計されました。このファイル形式の詳細は [こちら](https://docs.fileformat.com/3d/3mf)をご覧ください。 |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) は、3D コンピュータグラフィックス用の圧縮ファイル形式およびデータ構造です。三角形メッシュ、ライティング、シェーディング、モーションデータ、色と構造を持つ線や点などの 3D モデル情報を含みます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/3d/u3d)で確認できます。 |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | 拡張子 .usd のファイルは、Universal Scene Description（USD）形式で、デジタルコンテンツ作成アプリケーション間でデータを交換・拡張するためのデータをエンコードします。Pixar が開発した USD は、モデルなどの要素資産やアニメーションのやり取りを可能にします。このファイル形式の詳細は[こちら](https://docs.fileformat.com/3d/usd)で確認できます。 |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | 拡張子 .usdz のファイルは、圧縮も暗号化もされていない ZIP アーカイブで、USD（Universal Scene Description）形式のファイルであり、テクスチャやアニメーションなど他形式のファイルをアーカイブ内に埋め込み、解凍せずに USD ランタイムで直接実行できます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/3d/usdz)で確認できます。 |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language（VRML）は、World Wide Web 上でインタラクティブな 3D オブジェクトを表現するためのファイル形式です。イラストや定義、バーチャルリアリティプレゼンテーションなど、複雑なシーンの三次元表現を作成する際に使用されます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/3d/vrml)で確認できます。 |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | 拡張子 .x のファイルは、Microsoft DirectX 2.0 で導入された DirectX 3D Graphics のレガシーファイル形式を指します。ゲームにおける 3D グラフィックスのレンダリングに使用され、メッシュ、テクスチャ、アニメーション、ユーザー定義オブジェクトの構造を指定します。2014 年以降は Autodesk の FBX 形式がよりモダンな形式として推奨され、廃止されています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/3d/x)で確認できます。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
