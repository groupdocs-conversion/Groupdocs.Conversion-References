---
title: "EBookFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义电子书文档。包括以下文件类型 Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3"
type: docs
weight: 1110
url: /zh/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

定义电子书文档。包括以下文件类型: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EBookFileType](ebookfiletype)() | 序列化构造函数 |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | AZW3，也称为 Kindle Format 8 (KF8)，是为 Amazon Kindle 设备开发的 AZW 电子书数字文件格式的改进版。该格式是对旧 AZW 文件的增强，仅在 Kindle Fire 设备上使用，并向后兼容其前身文件格式，即 MOBI 和 AZW。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | EPUB 扩展是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。该格式已如此普及，以至于被许多电子阅读器和软件应用支持。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/ebook/epub). |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | MOBI 文件格式是最广泛使用的电子书文件格式之一。该格式是对旧的 OEB（Open Ebook Format）格式的增强，并曾作为 Mobipocket Reader 的专有格式使用。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/ebook/mobi). |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
