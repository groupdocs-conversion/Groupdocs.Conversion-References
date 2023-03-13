---
title: ThreeDFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: 3D ドキュメントを定義します 次のタイプが含まれます Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/x 3D 形式の詳細ここhttps//wiki.fileformat.com/3d.
type: docs
weight: 1060
url: /ja/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3D ドキュメントを定義します 次のタイプが含まれます: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x) 3D 形式の詳細[ここ](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | シリアル化コンストラクター |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイル family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他のオブジェクトと比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | AMF ファイルは、アディティブ マニュファクチャリング プロセスで使用するためのオブジェクト記述のガイドラインで構成されています。 XML の開始タグが含まれ、要素で終了します。これの前に、ファイルの XML バージョンとエンコードを指定する XML 宣言行があります。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/amf) |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | 拡張子が .ase のファイルは、シーンの ASCII 表現である Autodesk ASCII シーン エクスポート ファイル形式で、Autodesk を使用してシーン データをエクスポートする際に 2D または 3D 情報を含みます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/ase) |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE ファイルは、インタラクティブな 3D アプリケーション間でデータを交換するために使用される Digital Asset Exchange ファイル形式です。このファイル形式は、グラフィック ソフトウェア アプリケーション間でデジタル アセットを交換するためのオープン スタンダード XML スキーマである COLLADA (COLLAborative Design Activity) XML スキーマに基づいています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/dae) |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | 拡張子が .drc のファイルは、Google Draco ライブラリで作成された圧縮 3D ファイル形式です。 Google は、3D 幾何学的メッシュと点群を圧縮および解凍するためのオープン ソース ライブラリとして Draco を提供し、3D グラフィックスの保存と転送を改善します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/drc) |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX (FilmBox) は、Kaydara が MotionBuilder 用に最初に開発した一般的な 3D ファイル形式です。 2006 年に Autodesk Inc に買収され、現在では多くの 3D ツールで使用されている主要な 3D 交換フォーマットの 1 つです。 FBX は、バイナリ ファイル形式と ASCII ファイル形式の両方で利用できます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/fbx) |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) は、3D モデル情報を JSON 形式で格納する 3D ファイル形式です。 JSON を使用すると、3D アセットのサイズと、それらのアセットを解凍して使用するために必要なランタイム処理の両方が最小限に抑えられます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/gltf) |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) は、Siemens PLM Software によって開発された、効率的で業界に焦点を当てた柔軟な ISO 標準化された 3D データ形式です。航空宇宙、自動車産業、重機の機械 CAD ドメインでは、JT が最も主要な 3D ビジュアライゼーション フォーマットとして使用されています。 このファイル フォーマットの詳細[ここ](https://docs.fileformat.com/3d/jt) |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ ファイルは、Wavefront の Advanced Visualizer アプリケーションで使用され、ジオメトリ オブジェクトを定義および保存します。ジオメトリ データの前後の転送は、OBJ ファイルを介して可能になります。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/obj) |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY (ポリゴン ファイル形式) は、ポリゴンのコレクションとして記述されたグラフィック オブジェクトを格納する 3D ファイル形式を表します。このファイル形式の目的は、幅広いモデルで役立つように十分一般的でシンプルで使いやすいファイル タイプを確立することでした。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/ply) |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM データ ファイルは AVEVA PDMS に関連しています。 RVM ファイルは、AVEVA Plant Design Management System Model プロジェクト ファイルです。 AVEVA の Plant Design Management System (PDMS) は、データ中心のテクノロジを使用してプロジェクトを管理する最も一般的な 3D 設計システムです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/rvm) |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | 拡張子が .3ds のファイルは、Autodesk 3D Studio で使用される 3D Sudio (DOS) メッシュ ファイル形式を表します。 Autodesk 3D Studio は 1990 年代から 3D ファイル形式の市場にあり、現在は 3D モデリング、アニメーション、およびレンダリングを扱う 3D Studio MAX に進化しています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/3ds) |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF (3D Manufacturing Format) は、3D オブジェクト モデルをさまざまな他のアプリケーション、プラットフォーム、サービス、およびプリンターにレンダリングするためにアプリケーションで使用されます。これは、最新バージョンの 3D プリンターで作業するために、STL などの他の 3D ファイル形式の制限と問題を回避するために作成されました。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/3mf) |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) は、3D コンピュータ グラフィックス用の圧縮ファイル形式およびデータ構造です。三角形のメッシュ、ライティング、シェーディング、モーション データ、色と構造を持つ線と点などの 3D モデル情報が含まれています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/u3d) |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | 拡張子が .usd のファイルは、デジタル コンテンツ作成アプリケーション間でデータを交換および拡張する目的でデータをエンコードするユニバーサル シーン記述ファイル形式です。 Pixar によって開発された USD は、要素アセット (モデルなど) またはアニメーションを交換する機能を提供します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/usd) |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz を含むファイルは、USD (Universal Scene Description) ファイル形式の非圧縮および暗号化されていない ZIP アーカイブであり、アーカイブ内に埋め込まれた他の形式 (テクスチャやアニメーションなど) のファイルを含み、それらをプロキシします。解凍する必要のない USD ランタイム. このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/usdz) |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language (VRML) は、World Wide Web (www) 上でインタラクティブな 3D ワールド オブジェクトを表現するためのファイル形式です。イラスト、定義、仮想現実のプレゼンテーションなど、複雑なシーンの 3 次元表現の作成に使用されます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/vrml) |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | 拡張子が .x のファイルは、Microsoft DirectX 2.0 で導入された DirectX 3D グラフィックスのレガシー ファイル形式を指します。ゲームでの 3D グラフィックス レンダリングに使用され、メッシュ、テクスチャ、アニメーション、およびユーザー定義オブジェクトの構造を指定します。 Autodesk FBX ファイル形式は、より最新の形式としてより適切に機能するため、2014 年以降は廃止されています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/3d/x) |

### 関連項目

* class [FileType](../filetype)
* 名前空間 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
