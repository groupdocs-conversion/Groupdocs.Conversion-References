---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义 3D 文档 包含以下类型 Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb 了解更多 3D 格式，请访问 https//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /zh/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

定义 3D 文档 包含以下类型: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) 了解更多 3D 格式，请访问 [这里](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | 序列化构造函数 |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | AMF 文件包含用于对象描述的指南，以便用于增材制造工艺。它包含一个打开的 XML 标记并以一个元素结束。此之前是指定 XML 版本和文件编码的 XML 声明行。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/amf)。 |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase 扩展名的文件是 Autodesk ASCII 场景导出文件格式，它是场景的 ASCII 表示，包含 2D 或 3D 信息，在使用 Autodesk 导出场景数据时使用。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/ase)。 |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE 文件是一种数字资产交换（Digital Asset Exchange）文件格式，用于在交互式 3D 应用之间交换数据。此文件格式基于 COLLADA（协作设计活动）XML 架构，是用于在图形软件应用之间交换数字资产的开放标准 XML 架构。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/dae)。 |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc 扩展名的文件是一种使用 Google Draco 库创建的压缩 3D 文件格式。Google 提供 Draco 作为开源库，用于压缩和解压缩 3D 几何网格和点云，并提升 3D 图形的存储和传输。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/drc)。 |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX（FilmBox）是一种流行的 3D 文件格式，最初由 Kaydara 为 MotionBuilder 开发。2006 年被 Autodesk Inc 收购，现在已成为许多 3D 工具使用的主要 3D 交换格式之一。FBX 提供二进制和 ASCII 两种文件格式。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/fbx)。 |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB 是以 GL Transmission Format（glTF）保存的 3D 模型的二进制文件格式表示。此二进制格式将 glTF 资产（JSON、.bin 和图像）存储在二进制块中。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/glb)。 |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF（GL Transmission Format）是一种 3D 文件格式，将 3D 模型信息存储为 JSON 格式。使用 JSON 可同时减小 3D 资产的体积并降低运行时解包和使用这些资产所需的处理。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/gltf)。 |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT（Jupiter Tessellation）是一种高效、面向行业且灵活的 ISO 标准化 3D 数据格式，由 Siemens PLM Software 开发。航空航天、汽车行业和重型设备等机械 CAD 领域将 JT 作为其领先的 3D 可视化格式。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/jt)。 |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | .ma 扩展名的文件是使用 Autodesk Maya 应用创建的 3D 项目文件。它包含大量文本命令，用于指定文件信息。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/ma)。 |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | .mb 扩展名的文件是使用 Autodesk Maya 应用创建的二进制项目文件。不同于以 ASCII 形式存储的 MA 文件格式，MB 文件以二进制形式存储。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/mb)。 |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ 文件被 Wavefront 的 Advanced Visualizer 应用用于定义和存储几何对象。通过 OBJ 文件实现几何数据的前向和后向传输。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/obj)。 |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY（Polygon File Format）是一种 3D 文件格式，用于存储以多边形集合描述的图形对象。该文件格式的目的是建立一种简单易用且足够通用的文件类型，以适用于广泛的模型。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/ply)。 |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM 数据文件与 AVEVA PDMS 相关。RVM 文件是 AVEVA Plant Design Management System（工厂设计管理系统）的模型项目文件。AVEVA 的 Plant Design Management System（PDMS）是使用数据中心技术管理项目的最流行的 3D 设计系统。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/rvm)。 |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds 扩展名的文件代表 Autodesk 3D Studio 使用的 3D Sudio（DOS）网格文件格式。Autodesk 3D Studio 自 1990 年代起进入 3D 文件格式市场，如今已发展为用于 3D 建模、动画和渲染的 3D Studio MAX。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/3ds)。 |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF（3D Manufacturing Format）被应用程序用于将 3D 对象模型渲染到各种其他应用、平台、服务和打印机。它的构建旨在避免其他 3D 文件格式（如 STL）在使用最新 3D 打印机时的限制和问题。了解更多关于此文件格式的信息，请访问 [这里](https://docs.fileformat.com/3d/3mf)。 |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D（Universal 3D）是一种用于3D计算机图形的压缩文件格式和数据结构。它包含三维模型信息，如三角网格、光照、着色、运动数据、带颜色和结构的线条和点。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/3d/u3d)。 |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | 带有 .usd 扩展名的文件是 Universal Scene Description 文件格式，用于编码数据以实现数字内容创作应用之间的数据交换和增强。由 Pixar 开发，USD 提供了交换元素资产（如模型）或动画的能力。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/3d/usd)。 |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | 带有 .usdz 扩展名的文件是未压缩且未加密的 ZIP 存档，用于 USD（Universal Scene Description）文件格式，包含其他格式（如纹理和动画）的文件代理，嵌入存档中，并可直接在 USD 运行时运行，无需解压。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/3d/usdz)。 |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | 虚拟现实建模语言（VRML）是一种用于在万维网（WWW）上表示交互式 3D 世界对象的文件格式。它用于创建复杂场景的三维表示，如插图、定义和虚拟现实演示。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/3d/vrml)。 |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | 带有 .x 扩展名的文件指的是 DirectX 3D 图形的旧版文件格式，最初随 Microsoft DirectX 2.0 引入。它用于游戏中的 3D 图形渲染，定义了网格、纹理、动画和用户自定义对象的结构。自 2014 年起已被弃用，因为 Autodesk FBX 文件格式作为更现代的格式表现更佳。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/3d/x)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
