---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义用于存储记录集合以容纳演示数据（如幻灯片、形状、文本、动画、视频、音频和嵌入对象）的演示文件格式。包括以下文件类型 Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx。了解更多关于演示格式的信息 此处https//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /zh/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

定义用于存储记录集合以容纳演示数据（如幻灯片、形状、文本、动画、视频、音频和嵌入对象）的演示文件格式。包括以下文件类型：[`Odp`](./odp)、[`Otp`](./otp)、[`Pot`](./pot)、[`Potm`](./potm)、[`Potx`](./potx)、[`Pps`](./pps)、[`Ppsm`](./ppsm)、[`Ppsx`](./ppsx)、[`Ppt`](./ppt)、[`Pptm`](./pptm)、[`Pptx`](./pptx)。了解更多关于演示格式的信息 [此处](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | 序列化构造函数 |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | 带有 FODP 扩展名的文件表示 OpenDocument 扁平 XML 演示文稿。演示文件以 OpenDocument 格式保存，但使用扁平 XML 格式，而不是标准 .ODP 文件使用的 .ZIP 容器。 |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | 带有 ODP 扩展名的文件表示 OpenOffice.org 在 OASIS Open 标准中使用的演示文件格式。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | 带有 .OTP 扩展名的文件表示使用 OASIS OpenDocument 标准格式的应用程序创建的演示模板文件。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | 带有 .POT 扩展名的文件表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | 带有 POTM 扩展名的文件是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或更高版本创建，包含可用于创建进一步演示文件的默认设置。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | 带有 .POTX 扩展名的文件表示由 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS，PowerPoint 幻灯片放映文件，是使用 Microsoft PowerPoint 为幻灯片放映目的创建的。PPS 文件的读取和创建受 Microsoft PowerPoint 97-2003 支持。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | 带有 PPSM 扩展名的文件表示由 Microsoft PowerPoint 2007 或更高版本创建的支持宏的幻灯片放映文件格式。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX，Power Point 幻灯片放映文件，是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | 带有 PPT 扩展名的文件表示 PowerPoint 文件，它由一系列幻灯片组成，用于以幻灯片放映方式显示。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | 带有 PPTM 扩展名的文件是由 Microsoft PowerPoint 2007 或更高版本创建的支持宏的演示文件。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | 带有 PPTX 扩展名的文件是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。不同于之前的二进制 PPT 演示文件格式，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文件格式。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/presentation/pptx). |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
