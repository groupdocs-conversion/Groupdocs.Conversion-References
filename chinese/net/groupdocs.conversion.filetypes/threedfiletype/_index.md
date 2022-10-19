---
title: ThreeDFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义 3D 文档 包括以下类型 Fbx./threedfiletype/fbx 了解有关 3D 格式的更多信息这里https//wiki.fileformat.com/3d.
type: docs
weight: 940
url: /zh/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

定义 3D 文档 包括以下类型： [`Fbx`](./fbx) 了解有关 3D 格式的更多信息[这里](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | 序列化构造函数 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 档案族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 确定两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 用作默认哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | AMF 文件包含对象描述指南，以供增材制造流程使用。它包含一个开始的 XML 标记并以一个元素结束。这前面是一个 XML 声明行，指定文件的 XML 版本和编码。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/amf) |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | 带有 .ase 扩展名的文件是 Autodesk ASCII 场景导出文件格式，它是场景的 ASCII 表示，在使用 Autodesk 导出场景数据时包含 2D 或 3D 信息。 了解有关此文件格式的详细信息[这里](https://docs.fileformat.com/3d/ase) |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE 文件是一种数字资产交换文件格式，用于在交互式 3D 应用程序之间交换数据。此文件格式基于 COLLADA（COLLAborative Design Activity）XML 模式，它是一种开放标准 XML 模式，用于在图形软件应用程序之间交换数字资产。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/dae) |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | 扩展名为 .drc 的文件是使用 Google Draco 库创建的压缩 3D 文件格式。 Google 提供 Draco 作为开源库，用于压缩和解压缩 3D 几何网格和点云，并改进 3D 图形的存储和传输。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/drc) |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX，FilmBox，是一种流行的 3D 文件格式，最初由 Kaydara 为 MotionBuilder 开发。它于 2006 年被 Autodesk Inc 收购，现在是许多 3D 工具使用的主要 3D 交换格式之一。 FBX 提供二进制和 ASCII 文件格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/fbx) |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF（GL 传输格式）是一种 3D 文件格式，它以 JSON 格式存储 3D 模型信息。 JSON 的使用最大限度地减少了 3D 资产的大小以及解压和使用这些资产所需的运行时处理。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/gltf) |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT（Jupiter Tessellation）是一种高效、专注于行业且灵活的 ISO 标准化 3D 数据格式，由 Siemens PLM Software 开发。航空航天、汽车工业和重型设备的机械 CAD 领域使用 JT 作为其最领先的 3D 可视化格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/jt) |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Wavefront 的 Advanced Visualizer 应用程序使用 OBJ 文件来定义和存储几何对象。通过 OBJ 文件可以实现几何数据的前后传输。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/obj) |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY，多边形文件格式，表示存储描述为多边形集合的图形对象的 3D 文件格式。此文件格式的目的是建立一种简单易用的文件类型，该文件类型足够通用，可用于各种模型。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/ply) |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM 数据文件与 AVEVA PDMS 相关。 RVM 文件是 AVEVA 工厂设计管理系统模型项目文件。 AVEVA 的工厂设计管理系统 (PDMS) 是最流行的 3D 设计系统，它使用以数据为中心的技术来管理项目。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/rvm) |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | 扩展名为 .3ds 的文件表示 Autodesk 3D Studio 使用的 3D Sudio (DOS) 网格文件格式。自 1990 年代以来，Autodesk 3D Studio 一直在 3D 文件格式市场，现在已经发展到 3D Studio MAX，用于处理 3D 建模、动画和渲染。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/3ds) |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF，3D 制造格式，应用程序使用它来将 3D 对象模型渲染到各种其他应用程序、平台、服务和打印机。它旨在避免其他 3D 文件格式（如 STL）中的限制和问题，用于使用最新版本的 3D 打印机。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/3mf) |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D（Universal 3D）是一种用于 3D 计算机图形的压缩文件格式和数据结构。它包含 3D 模型信息，例如三角形网格、照明、阴影、运动数据、具有颜色和结构的线和点。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/u3d) |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | 扩展名为 .usd 的文件是一种通用场景描述文件格式，用于对数据进行编码，以便在数字内容创建应用程序之间进行数据交换和扩充。由 Pixar 开发，USD 提供了交换元素资产（例如模型）或动画的能力。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/usd) |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz 文件是 USD（通用场景描述）文件格式的未压缩和未加密 ZIP 存档，其中包含嵌入存档中的其他格式（例如纹理和动画）的文件和代理，并使用USD 运行时无需任何解包。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/usdz) |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | 虚拟现实建模语言 (VRML) 是一种文件格式，用于在万维网 (www) 上表示交互式 3D 世界对象。它可用于创建复杂场景的三维表示，例如插图、定义和虚拟现实演示。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/vrml) |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | 带有 .x 扩展名的文件是指 Microsoft DirectX 2.0 引入的 DirectX 3D 图形旧文件格式。它用于游戏中的 3D 图形渲染，并指定网格、纹理、动画和用户定义对象的结构。自 2014 年以来，它已被弃用，因为 Autodesk FBX 文件格式更适合作为更现代的格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/3d/x) |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
