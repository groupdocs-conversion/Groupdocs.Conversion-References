---
title: "FontFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义字体文档 包含以下类型 Ttf./fontfiletype/ttf Eot./fontfiletype/eot Otf./fontfiletype/otf Cff./fontfiletype/cff Type1./fontfiletype/type1 Woff./fontfiletype/woff Woff2./fontfiletype/woff2 了解更多关于字体格式的信息，请访问herehttps//docs.fileformat.com/font/。"
type: docs
weight: 1150
url: /zh/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

定义字体文档 包含以下类型：[`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) 了解更多关于字体格式的信息，请访问[here](https://docs.fileformat.com/font/)。

```csharp
public sealed class FontFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FontFileType](fontfiletype)() | 序列化构造函数 |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | 带有 .cff 扩展名的文件是紧凑字体格式（Compact Font Format），也称为 PostScript Type 1 或 CIDFont。CFF 充当容器，将多个字体存储在一个称为 FontSet 的单元中。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/cff/)。 |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | 带有 .eot 扩展名的文件是嵌入文档中的 OpenType 字体。它们主要用于网页文件，如网页。该字体由 Microsoft 创建，并受到包括 PowerPoint 演示文稿 .pps 文件在内的 Microsoft 产品的支持。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/eot/)。 |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | 带有 .otf 扩展名的文件指的是 OpenType 字体格式。OTF 字体格式更具可伸缩性，并扩展了 TTF 格式在数字排版方面的现有特性。由 Microsoft 和 Adobe 开发，OTF 结合了 PostScript 和 TrueType 字体格式的特性。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/otf/)。 |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | 带有 .ttf 扩展名的文件是基于 TrueType 规范的字体文件。它最初由 Apple Computer, Inc 为 Mac OS 设计并推出，随后被 Microsoft 采用于 Windows OS。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/ttf/)。 |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1 字体是已废弃的 Adobe 技术，曾广泛用于桌面出版软件和能够使用 PostScript 的打印机。虽然许多现代平台、网页浏览器和移动操作系统不再支持 Type 1 字体，但在某些操作系统中仍受支持。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/type1/)。 |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | 带有 .woff 扩展名的文件是基于 Web Open Font Format（WOFF）的网络字体文件。它采用基于 TrueType（.TTF）或 OpenType（.OTT）字体类型的特定格式压缩容器。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/woff/)。 |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | 带有 .woff 扩展名的文件是基于 Web Open Font Format（WOFF）的网络字体文件。它采用基于 TrueType（.TTF）或 OpenType（.OTT）字体类型的特定格式压缩容器。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/font/woff/)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
