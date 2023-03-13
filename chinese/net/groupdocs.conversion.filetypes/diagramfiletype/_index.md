---
title: DiagramFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义图表文档包括以下类型 Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx.
type: docs
weight: 900
url: /zh/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

定义图表文档。包括以下类型： [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | 序列化构造函数 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件 family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 判断两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 判断两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 作为默认哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示形式 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW 是 Visio 图形服务文件格式，它指定呈现 Web 绘图所需的流和存储。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | 在 Microsoft Visio 中创建但以 XML 格式保存的任何绘图或图表都具有 .VDX 扩展名。 Visio 绘图 XML 文件是在 Microsoft 开发的 Visio 软件中创建的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD 文件是使用 Microsoft Visio 应用程序创建的绘图，用于表示各种图形对象以及这些对象之间的互连。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | 带有 VSDM 扩展名的文件是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。 VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但也提供了在文件打开时运行宏的功能。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | 扩展名为 .VSDX 的文件代表从 Microsoft Office 2013 开始引入的 Microsoft Visio 文件格式。开发它是为了替换二进制文件格式 .VSD，它受早期版本的 Microsoft Visio 支持。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | 扩展名为 .VSSM 的文件是支持宏的 Microsoft Visio Stencil 文件。 VSSM 文件打开后允许运行宏以在图表中实现所需的格式设置和形状放置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | 扩展名为 .VSSX 的文件是使用 Microsoft Visio 2013 及更高版本创建的绘图模板。 VSSX 文件格式可以用 Visio 2013 及更高版本打开。 Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接器、流程图、网络布局、UML 图、 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | 具有 VST 扩展名的文件是使用 Microsoft Visio 创建的矢量图像文件，可作为创建更多文件的模板。这些模板文件采用二进制文件格式，包含用于创建新 Visio 绘图的默认布局和设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | 带有 VSTM 扩展名的文件是使用支持宏的 Microsoft Visio 创建的模板文件。与 VSDX 文件不同，从 VSTM 模板创建的文件可以运行在 Visual Basic for Applications (VBA) 代码中开发的宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | 带有 VSTX 扩展名的文件是使用 Microsoft Visio 2013 及更高版本创建的绘图模板文件。这些 VSTX 文件为创建 Visio 绘图提供起点，保存为 .VSDX 文件，具有默认布局和设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | 具有 .VSX 扩展名的文件是指由绘图和形状组成的模板，用于在 Microsoft Visio 中创建图表。 VSX 文件以 XML 文件格式保存并在 Visio 2013 之前一直受支持。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | 带有 VTX 扩展名的文件是以 XML 文件格式保存到光盘的 Microsoft Visio 绘图模板。该模板旨在提供具有基本设置的文件，可用于创建具有相同设置的多个 Visio 文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vtx). |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
