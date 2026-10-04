---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Diagram ドキュメントを定義します。次のタイプが含まれます Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /ja/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Diagram ドキュメントを定義します。次のタイプが含まれます：[`Drawio`](./drawio)、[`Mmd`](./mmd)、[`Vdw`](./vdw)、[`Vdx`](./vdx)、[`Vsd`](./vsd)、[`Vsdm`](./vsdm)、[`Vsdx`](./vsdx)、[`Vss`](./vss)、[`Vssm`](./vssm)、[`Vssx`](./vssx)、[`Vst`](./vst)、[`Vstm`](./vstm)、[`Vstx`](./vstx)、[`Vsx`](./vsx)、[`Vtx`](./vtx)。

```csharp
public sealed class DiagramFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | DRAWIO 拡張子のファイルは、diagrams.net（旧 draw.io）で作成された図です。XML ファイル形式で保存され、mxfile ルート要素を持ち、テキスト、画像、レイアウト、シェイプ、位置情報などの図要素の内容と書式設定を保持します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/web/drawio)をご覧ください。 |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | MMD 拡張子のファイルは、Mermaid マークアップ言語で記述された図です。プレーンテキストドキュメントとして保存され、フローチャートや sequenceDiagram などの図宣言で始まり、ノードとそれらの接続の定義が続きます。このファイル形式の詳細は[こちら](https://mermaid.js.org/intro/)をご覧ください。 |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW は Visio Graphics Service のファイル形式で、Web 図面のレンダリングに必要なストリームとストレージを指定します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/web/vdw)をご覧ください。 |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio で作成された図やチャートを XML 形式で保存したものは .VDX 拡張子を持ちます。Visio ソフトウェア（Microsoft が開発）で作成された Visio 図面 XML ファイルです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vdx)をご覧ください。 |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD ファイルは、Microsoft Visio アプリケーションで作成された図面で、さまざまなグラフィックオブジェクトやそれらの相互接続を表現します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vsd)をご覧ください。 |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | VSDM 拡張子のファイルは、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。VSDM ファイルは OPC/XML 図面で、VSDX と類似していますが、ファイルを開く際にマクロを実行できる機能も提供します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vsdm)をご覧ください。 |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | .VSDX 拡張子のファイルは、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。以前のバージョンでサポートされていたバイナリ形式の .VSD を置き換えるために開発されました。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vsdx)をご覧ください。 |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS は Microsoft Visio 2007 以前で作成されたステンシルファイルです。ステンシルファイルは、.VSD Visio 図面に含めることができる描画オブジェクトを提供します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vss)をご覧ください。 |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | .VSSM 拡張子のファイルは、マクロをサポートする Microsoft Visio ステンシルファイルです。VSSM ファイルを開くと、マクロが実行され、図面内のシェイプの書式設定や配置を目的通りに行うことができます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vssm)をご覧ください。 |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Files with .VSSX extension are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representation of a variety of drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, Learn more about this file format [here](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Files with VST extension are vector image files created with Microsoft Visio and act as template for creating further files. These template files are in binary file format and contain the default layout and settings that are utilized for creation of new Visio drawings. Learn more about this file format [here](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Files with VSTM extension are template files created with Microsoft Visio that support macros. Unlike VSDX files, files created from VSTM templates can run macros that are developed in Visual Basic for Applications (VBA) code. Learn more about this file format [here](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Files with VSTX extensions are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide starting point for creating Visio drawings, saved as .VSDX files, with default layout and settings. Learn more about this file format [here](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Files with .VSX extension refer to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013. Learn more about this file format [here](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | A file with VTX extension is a Microsoft Visio drawing template that is saved to disc in XML file format. The template is aimed to provide a file with basic settings that can be used to create multiple Visio files of the same settings. Learn more about this file format [here](https://wiki.fileformat.com/image/vtx). |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
