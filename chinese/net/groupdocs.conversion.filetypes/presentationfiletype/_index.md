---
title: PresentationFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义存储记录集合的演示文稿文件格式以容纳幻灯片形状文本动画视频音频和嵌入对象等演示数据 包括以下文件类型 Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . 了解有关演示文稿格式的更多信息这里https//wiki.fileformat.com/presentation.
type: docs
weight: 1020
url: /zh/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

定义存储记录集合的演示文稿文件格式，以容纳幻灯片、形状、文本、动画、视频、音频和嵌入对象等演示数据。 包括以下文件类型： [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . 了解有关演示文稿格式的更多信息[这里](https://wiki.fileformat.com/presentation).

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | 具有 FODP 扩展名的文件表示 OpenDocument 平面 XML 表示。以 OpenDocument 格式保存的演示文件，但使用平面 XML 格式而不是标准 .ODP 文件使用的 .ZIP 容器保存 |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | 具有 ODP 扩展名的文件表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/odp) |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | 扩展名为 .OTP 的文件表示应用程序以 OASIS OpenDocument 标准格式创建的演示文稿模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/otp) |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | 扩展名为 .POT 的文件代表由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pot) |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | 带有 POTM 扩展名的文件是支持宏的 Microsoft PowerPoint 模板文件。 POTM 文件是使用 PowerPoint 2007 或更高版本创建的，包含可用于创建更多演示文稿文件的默认设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potm) |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | 扩展名为 .POTX 的文件表示使用 Microsoft PowerPoint 2007 及更高版本创建的 Microsoft PowerPoint 模板演示文稿。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potx) |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS，PowerPoint 幻灯片，文件是使用 Microsoft PowerPoint 创建的，用于幻灯片放映。 Microsoft PowerPoint 97-2003 支持 PPS 文件读取和创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pps) |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | 带有 PPSM 扩展名的文件表示使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX、Power Point 幻灯片放映文件是使用 Microsoft PowerPoint 2007 及更高版本创建的，用于放映幻灯片。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | 带有 PPT 扩展名的文件代表 PowerPoint 文件，它由一组幻灯片组成，用于显示为 SlideShow。它指定 Microsoft PowerPoint 97-2003 使用的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | 带有 PPTM 扩展名的文件是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的演示文稿文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | 带有 PPTX 扩展名的文件是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。与以前版本的二进制演示文稿文件格式 PPT 不同，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptx) |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
