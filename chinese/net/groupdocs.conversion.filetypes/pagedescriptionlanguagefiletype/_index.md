---
title: "页面描述语言文件类型"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义页面描述文档。包括以下文件类型 Svg./pagedescriptionlanguagefiletype/svgSvgz./pagedescriptionlanguagefiletype/svgzEps./pagedescriptionlanguagefiletype/epsCgm./pagedescriptionlanguagefiletype/cgmXps./pagedescriptionlanguagefiletype/xpsTex./pagedescriptionlanguagefiletype/texPs./pagedescriptionlanguagefiletype/psPcl./pagedescriptionlanguagefiletype/pclOxps./pagedescriptionlanguagefiletype/oxps"
type: docs
weight: 1190
url: /zh/net/groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
## PageDescriptionLanguageFileType class

定义页面描述文档。包括以下文件类型：[`Svg`](./svg)[`Svgz`](./svgz)[`Eps`](./eps)[`Cgm`](./cgm)[`Xps`](./xps)[`Tex`](./tex)[`Ps`](./ps)[`Pcl`](./pcl)[`Oxps`](./oxps)

```csharp
public sealed class PageDescriptionLanguageFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PageDescriptionLanguageFileType](pagedescriptionlanguagefiletype)() | 序列化构造函数 |

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
| static readonly [Cgm](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/cgm) | Computer Graphics Metafile（CGM）是一种免费、跨平台、国际标准的元文件格式，用于存储和交换矢量图形（2D）、光栅图形和文本。CGM 使用面向对象的方法和许多功能来支持图像生成。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/cgm)。 |
| static readonly [Eps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/eps) | 带有 EPS 扩展名的文件本质上描述了一个封装的 PostScript 语言程序，用于描述单页的外观。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/eps)。 |
| static readonly [Oxps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/oxps) | 文件格式 OXPS 被称为 Open XML Paper Specification。它是一种页面描述语言和文档格式。Microsoft 是该格式的开发者。OXPS 文件格式与 PDF 文件非常相似。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/page-description-language/oxps)。 |
| static readonly [Pcl](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/pcl) | PCL 代表打印机命令语言（Printer Command Language），是一种由惠普（HP）推出的页面描述语言。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/pcl)。 |
| static readonly [Ps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/ps) | PostScript（PS）是一种通用的页面描述语言，广泛用于桌面和电子出版业务。PostScript（PS）的主要目标是促进二维图形设计。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/ps)。 |
| static readonly [Svg](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svg) | SVG 文件是一种可缩放矢量图形（Scalar Vector Graphics）文件，使用基于 XML 的文本格式来描述图像的外观。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/svg)。 |
| static readonly [Svgz](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svgz) | SVGZ 文件实际上是 SVG 文件的压缩版本。这使得文件在网络上的分发更加便捷。当使用 .GZIP 压缩算法对 SVG 文件进行压缩后，会得到 .svgz 文件扩展名。 |
| static readonly [Tex](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/tex) | TeX 是一种兼具编程和标记功能的语言，用于排版文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/tex)。 |
| static readonly [Xps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/xps) | XPS 文件是基于 Microsoft 创建的 XML 纸张规范（XML Paper Specifications）的页面布局文件。该格式由 Microsoft 开发，用于取代 EMF 文件格式，类似于 PDF 文件格式，但在文档的布局、外观和打印信息上使用 XML。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/xps)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
