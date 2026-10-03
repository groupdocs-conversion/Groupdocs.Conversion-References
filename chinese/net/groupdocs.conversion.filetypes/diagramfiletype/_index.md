---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义 Diagram 文档。包括以下类型 Drawio。/diagramfiletype/drawio Mmd。/diagramfiletype/mmd Vdw。/diagramfiletype/vdw Vdx。/diagramfiletype/vdx Vsd。/diagramfiletype/vsd Vsdm。/diagramfiletype/vsdm Vsdx。/diagramfiletype/vsdx Vss。/diagramfiletype/vss Vssm。/diagramfiletype/vssm Vssx。/diagramfiletype/vssx Vst。/diagramfiletype/vst Vstm。/diagramfiletype/vstm Vstx。/diagramfiletype/vstx Vsx。/diagramfiletype/vsx Vtx。/diagramfiletype/vtx。"
type: docs
weight: 1100
url: /zh/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

定义 Diagram 文档。包括以下类型：[`Drawio`](./drawio)、[`Mmd`](./mmd)、[`Vdw`](./vdw)、[`Vdx`](./vdx)、[`Vsd`](./vsd)、[`Vsdm`](./vsdm)、[`Vsdx`](./vsdx)、[`Vss`](./vss)、[`Vssm`](./vssm)、[`Vssx`](./vssx)、[`Vst`](./vst)、[`Vstm`](./vstm)、[`Vstx`](./vstx)、[`Vsx`](./vsx)、[`Vtx`](./vtx)。

```csharp
public sealed class DiagramFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | 序列化构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 实现 [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | 带有 DRAWIO 扩展名的文件是使用 diagrams.net（前身为 draw.io）创建的图表。它以 XML 文件格式存储，根元素为 mxfile，并保存图表元素的内容和格式，如文本、图像、布局、形状和位置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/web/drawio)。 |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | 带有 MMD 扩展名的文件是使用 Mermaid 标记语言编写的图表。它以纯文本文档存储，首先是图表声明，例如 flowchart 或 sequenceDiagram，随后是节点及其连接的定义。了解更多关于此文件格式的信息，请点击[此处](https://mermaid.js.org/intro/)。 |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW 是 Visio Graphics Service 文件格式，指定渲染 Web 绘图所需的流和存储。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/web/vdw)。 |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | 任何在 Microsoft Visio 中创建的绘图或图表，如果以 XML 格式保存，则使用 .VDX 扩展名。Visio 绘图 XML 文件由 Microsoft 开发的 Visio 软件创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vdx)。 |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD 文件是使用 Microsoft Visio 应用程序创建的绘图，用于表示各种图形对象及其相互连接。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsd)。 |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | 带有 VSDM 扩展名的文件是使用 Microsoft Visio 应用程序创建的支持宏的绘图文件。VSDM 文件是 OPC/XML 绘图，类似于 VSDX，但在打开文件时还能运行宏。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsdm)。 |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | 带有 .VSDX 扩展名的文件代表自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它用于取代早期版本 Visio 支持的二进制文件格式 .VSD。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsdx)。 |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS 是在 Microsoft Visio 2007 及更早版本中创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vss)。 |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | 带有 .VSSM 扩展名的文件是支持宏的 Microsoft Visio 模板文件。打开 VSSM 文件时，可运行宏以实现所需的形状格式和位置布局。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vssm)。 |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | 带有 .VSSX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。VSSX 文件格式可以在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接线、流程图、网络布局、UML 图。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vssx)。 |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | 带有 VST 扩展名的文件是使用 Microsoft Visio 创建的矢量图像文件，充当创建后续文件的模板。这些模板文件采用二进制文件格式，包含用于创建新 Visio 绘图的默认布局和设置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vst)。 |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | 带有 VSTM 扩展名的文件是使用 Microsoft Visio 创建的支持宏的模板文件。与 VSDX 文件不同，基于 VSTM 模板创建的文件可以运行在 Visual Basic for Applications (VBA) 代码中开发的宏。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vstm)。 |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | 带有 VSTX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件提供了创建 Visio 绘图（保存为 .VSDX 文件）的起始点，包含默认布局和设置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vstx)。 |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | 带有 .VSX 扩展名的文件指的是用于在 Microsoft Visio 中创建图表的绘图和形状模板。VSX 文件以 XML 文件格式保存，并在 Visio 2013 之前受支持。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsx)。 |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | 带有 VTX 扩展名的文件是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。该模板旨在提供具有基本设置的文件，可用于创建多个具有相同设置的 Visio 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vtx)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
