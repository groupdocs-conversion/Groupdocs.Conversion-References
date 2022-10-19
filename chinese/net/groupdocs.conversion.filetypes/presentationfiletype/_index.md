---
title: PresentationFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义存储记录集合的演示文件格式以容纳演示数据例如幻灯片形状文本动画视频音频和嵌入对象 包括以下文件类型 Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . 了解有关演示格式的更多信息这里https//wiki.fileformat.com/presentation.
type: docs
weight: 910
url: /zh/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

定义存储记录集合的演示文件格式，以容纳演示数据，例如幻灯片、形状、文本、动画、视频、音频和嵌入对象。 包括以下文件类型： [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . 了解有关演示格式的更多信息[这里](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | 序列化构造函数 |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | 带有 FODP 扩展名的文件代表 OpenDocument 平面 XML 演示文稿。以 OpenDocument 格式保存的演示文件，但使用平面 XML 格式而不是标准 .ODP 文件使用的 .ZIP 容器保存 |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | 带有 ODP 扩展名的文件表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/odp) |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | 带有 .OTP 扩展名的文件表示由应用程序以 OASIS OpenDocument 标准格式创建的演示模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/otp) |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | 带有 .POT 扩展名的文件代表由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pot) |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | 带有 POTM 扩展名的文件是支持宏的 Microsoft PowerPoint 模板文件。 POTM 文件是使用 PowerPoint 2007 或更高版本创建的，包含可用于创建更多演示文件的默认设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potm) |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | 带有 .POTX 扩展名的文件代表使用 Microsoft PowerPoint 2007 及更高版本创建的 Microsoft PowerPoint 模板演示文稿。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potx) |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS，PowerPoint 幻灯片放映，文件是使用 Microsoft PowerPoint 为幻灯片放映目的创建的。 Microsoft PowerPoint 97-2003 支持 PPS 文件读取和创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pps) |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | 带有 PPSM 扩展名的文件表示使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX、Power Point 幻灯片放映文件是使用 Microsoft PowerPoint 2007 及更高版本创建的，用于幻灯片放映目的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | 带有 PPT 扩展名的文件表示 PowerPoint 文件，该文件由一组幻灯片组成，用于显示为 SlideShow。它指定 Microsoft PowerPoint 97-2003 使用的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | 带有 PPTM 扩展名的文件是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的演示文稿文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | 带有 PPTX 扩展名的文件是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。与以前版本的二进制演示文件格式 PPT 不同，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptx) |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
