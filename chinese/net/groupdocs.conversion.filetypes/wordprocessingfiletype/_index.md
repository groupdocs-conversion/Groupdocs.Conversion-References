---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义文字处理文件，这些文件以纯文本或富文本格式包含用户信息。纯文本文件格式包含未格式化的文本，且无法应用字体或页面设置等。相反，富文本文件格式允许设置字体、类型、样式（粗体、斜体、下划线等）、页面边距、标题、项目符号和编号以及其他多种格式化功能。包括以下文件类型 Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. 了解更多关于文字处理格式的信息 herehttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /zh/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

定义文字处理文件，这些文件以纯文本或富文本格式包含用户信息。纯文本文件格式包含未格式化的文本，且无法应用字体或页面设置等。相反，富文本文件格式允许设置字体、类型、样式（粗体、斜体、下划线等）、页面边距、标题、项目符号和编号以及其他多种格式化功能。包括以下文件类型: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). 了解更多关于文字处理格式的信息[here](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | 序列化构造函数 |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | 带有 .doc 扩展名的文件表示由 Microsoft Word 或其他文字处理软件生成的二进制文件格式文档。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM 文件是 Microsoft Word 2007 或更高版本生成的文档，具备运行宏的能力。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX 是 Microsoft Word 文档的知名格式。自 2007 年 Microsoft Office 2007 发布起引入，该新文档格式的结构从纯二进制改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | 带有 .DOT 扩展名的文件是 Microsoft Word 创建的模板文件，用于预设设置以生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | 带有 DOTM 扩展名的文件是由 Microsoft Word 2007 或更高版本创建的模板文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | 带有 DOTX 扩展名的文件是 Microsoft Word 创建的模板文件，用于预设设置以生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word 是以平面 XML 文件而非 ZIP 包存储的 Office Open XML WordprocessingML。 |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | 使用 Markdown 语言方言创建的文本文件保存为 .MD 或 .MARKDOWN 文件扩展名。MD 文件以纯文本格式保存，使用 Markdown 语言，其中还包括内联文本符号，定义文本的格式方式，如缩进、表格格式、字体和标题等。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT 文件是一种基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。了解更多关于此文件格式，请访问[here](https://wiki.fileformat.com/word-processing/odt)。 |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | 带有 OTT 扩展名的文件表示符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式，请访问[here](https://wiki.fileformat.com/word-processing/ott)。 |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | 由 Microsoft 引入并记录的富文本格式（RTF）是一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式，请访问[here](https://wiki.fileformat.com/word-processing/rtf)。 |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT 扩展名的文件表示包含以行形式呈现的纯文本的文本文档。了解更多关于此文件格式，请访问[here](https://wiki.fileformat.com/word-processing/txt)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
