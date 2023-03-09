---
title: DiagramFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: ダイアグラム ドキュメントを定義します次のタイプが含まれます Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx.
type: docs
weight: 900
url: /ja/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

ダイアグラム ドキュメントを定義します。次のタイプが含まれます: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | シリアル化コンストラクター |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW は、Web 図面のレンダリングに必要なストリームとストレージを指定する Visio Graphics Service ファイル形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio で作成され、XML 形式で保存された図面またはチャートには、.VDX 拡張子が付きます。 Visio 図面 XML ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD ファイルは、Microsoft Visio アプリケーションで作成された図面で、さまざまなグラフィカル オブジェクトとこれらの間の相互接続を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | VSDM 拡張子を持つファイルは、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。 VSDM ファイルは、VSDX に似た OPC/XML 図面ですが、ファイルを開いたときにマクロを実行する機能も提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | 拡張子が .VSDX のファイルは、Microsoft Office 2013 以降で導入された Microsoft Visio ファイル形式を表します。これは、以前のバージョンの Microsoft Visio でサポートされていたバイナリ ファイル形式 .VSD を置き換えるために開発されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS は、Microsoft Visio 2007 以前で作成されたステンシル ファイルです。ステンシル ファイルは、.VSD Visio 図面に含めることができる図面オブジェクトを提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | 拡張子が .VSSM のファイルは、マクロをサポートする Microsoft Visio Stencil ファイルです。 VSSM ファイルを開くと、マクロを実行して、ダイアグラム内の図形の目的の書式設定と配置を実現できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | 拡張子が .VSSX のファイルは、Microsoft Visio 2013 以降で作成された図面ステンシルです。 VSSX ファイル形式は、Visio 2013 以降で開くことができます。 Visio ファイルは、図形のコレクション、コネクタ、フローチャート、ネットワーク レイアウト、UML ダイアグラム、 など、さまざまな描画要素の表現で知られています。このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | VST 拡張子を持つファイルは、Microsoft Visio で作成されたベクター画像ファイルであり、さらにファイルを作成するためのテンプレートとして機能します。これらのテンプレート ファイルはバイナリ ファイル形式であり、新しい Visio 図面の作成に使用される既定のレイアウトと設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | VSTM 拡張子を持つファイルは、マクロをサポートする Microsoft Visio で作成されたテンプレート ファイルです。 VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | VSTX 拡張子を持つファイルは、Microsoft Visio 2013 以降で作成された図面テンプレート ファイルです。これらの VSTX ファイルは、既定のレイアウトと設定を使用して、.VSDX ファイルとして保存された Visio 図面を作成するための開始点を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | 拡張子が .VSX のファイルは、Microsoft Visio で図を作成するために使用される図面と図形で構成されるステンシルを指します。 VSX ファイルは XML ファイル形式で保存され、Visio 2013 までサポートされていました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | VTX 拡張子を持つファイルは、XML ファイル形式でディスクに保存される Microsoft Visio 図面テンプレートです。このテンプレートは、同じ設定の複数の Visio ファイルを作成するために使用できる基本設定を含むファイルを提供することを目的としています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vtx). |

### 関連項目

* class [FileType](../filetype)
* 名前空間 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
