---
title: "CadFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义用于 3D 图形文件格式的 CAD（计算机辅助设计）文档，可能包含 2D 或 3D 设计。包括以下类型 Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl。了解更多 CAD 格式，请访问 https://wiki.fileformat.com/cad。"
type: docs
weight: 1070
url: /zh/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

定义 CAD 文档（计算机辅助设计），用于 3D 图形文件格式，可能包含 2D 或 3D 设计。包括以下类型：[`Cf2`](./cf2)[`Dgn`](./dgn)，[`Dwf`](./dwf)，[`Dwfx`](./dwfx)[`Dwg`](./dwg)，[`Dwt`](./dwt)，[`Dxf`](./dxf)，[`Ifc`](./ifc)，[`Igs`](./igs)，[`Plt`](./plt)，[`Stl`](./stl)。了解更多 CAD 格式，请点击[here](https://wiki.fileformat.com/cad)。

```csharp
public sealed class CadFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadFileType](cadfiletype)() | 序列化构造函数 |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | 通用文件格式文件。CAD 文件包含 3D 包装设计或其他模型数据；可由 CAD/CAM 机器（如冲压切割设备）进行处理和切割。 |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN，Design 文件是由 CAD 应用程序（如 MicroStation 和 Intergraph Interactive Graphics Design System）创建并支持的图纸。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/dgn)。 |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format（DWF）以压缩格式表示 2D/3D 图纸，用于查看、审阅或打印设计文件。它包含作为设计数据一部分的图形和文本，并因其压缩格式而减小文件大小。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/dwf)。 |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX 文件是使用 Autodesk CAD 软件创建的 2D 或 3D 图纸。它以 DWFx 格式保存，类似于 .DWF 文件，但使用 Microsoft 的 XML Paper Specification（XPS）进行格式化。 |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | 带有 DWG 扩展名的文件表示用于存储 2D 和 3D 设计数据的专有二进制文件。类似于 ASCII 文件的 DXF，DWG 代表 CAD（计算机辅助设计）图纸的二进制文件格式。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/dwg)。 |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | DWT 文件是 AutoCAD 绘图模板文件，用作创建可保存为 DWG 文件的图纸的起始模板。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/dwt)。 |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF（Drawing Interchange Format，绘图交换格式）是一种标记数据表示的 AutoCAD 绘图文件。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/dxf)。 |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | 带有 IFC 扩展名的文件指的是 Industry Foundation Classes（IFC）文件格式，它建立了用于导入和导出建筑对象及其属性的国际标准。此文件格式提供了不同软件应用之间的互操作性。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/ifc)。 |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs 文档格式 |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT 文件格式是一种由 Autodesk, Inc. 引入的基于矢量的绘图仪文件，包含特定 CAD 文件的信息。绘图细节在生产中需要精确和准确，使用 PLT 文件可保证所有图像以线条而非点的方式打印，从而满足此要求。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/plt)。 |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL，即立体光刻（stereolithography）的缩写，是一种可互换的文件格式，表示三维表面几何。该文件格式在快速原型、3D 打印和计算机辅助制造等多个领域中得到应用。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/cad/stl)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
