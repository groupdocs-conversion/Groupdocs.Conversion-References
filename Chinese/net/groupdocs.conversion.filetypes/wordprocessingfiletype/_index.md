---
title: WordProcessingFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义包含纯文本或富文本格式的用户信息的文字处理文件纯文本文件格式包含未格式化的文本不能应用字体或页面设置等相反富文本文件格式允许格式化选项例如设置字体类型样式粗体斜体下划线等页边距标题项目符号和数字以及其他一些格式化功能 包括以下文件类型 Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Log./wordprocessingfiletype/log . 了解有关文字处理格式的更多信息这里https//wiki.fileformat.com/wordprocessing.
type: docs
weight: 960
url: /zh/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

定义包含纯文本或富文本格式的用户信息的文字处理文件。纯文本文件格式包含未格式化的文本，不能应用字体或页面设置等。相反，富文本文件格式允许格式化选项，例如设置字体类型、样式（粗体、斜体、下划线等）、页边距、标题、项目符号和数字，以及其他一些格式化功能。 包括以下文件类型： [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`Mobi`](./mobi) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt). [`Md`](./md). [`Log`](./log) . 了解有关文字处理格式的更多信息[这里](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | 序列化构造函数 |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | AZW3，也称为 Kindle Format 8 (KF8)，是为亚马逊 Kindle 设备开发的 AZW 电子书数字文件格式的修改版本。该格式是对旧 AZW 文件的增强，仅用于 Kindle Fire 设备，向后兼容原始文件格式，即 MOBI 和 AZW。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/ebook/azw3/) |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | 带有 .doc 扩展名的文件表示由 Microsoft Word 或其他二进制文件格式的文字处理文档生成的文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/doc) |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM 文件是 Microsoft Word 2007 或更高版本生成的文档，能够运行宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docm) |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX 是一种众所周知的 Microsoft Word 文档格式。从 2007 年随着 Microsoft Office 2007 的发布引入，这种新文档格式的结构从纯二进制更改为 XML 和二进制文件的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docx) |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | 带有 .DOT 扩展名的文件是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOC 或 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dot) |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | 带有 DOTM 扩展名的文件表示使用 Microsoft Word 2007 或更高版本创建的模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotm) |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | 带有 DOTX 扩展名的文件是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotx) |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | 带有 .LOG 扩展名的文件表示包含行形式的纯文本的文本文档。 |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | 使用 Markdown 语言方言创建的文本文件以 .MD 或 .MARKDOWN 文件扩展名保存。 MD 文件以使用 Markdown 语言的纯文本格式保存，该语言还包括内联文本符号，定义如何格式化文本，例如缩进、表格格式、字体和标题。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/md) |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | MOBI 文件格式是使用最广泛的电子书文件格式之一。该格式是对旧 OEB（开放电子书格式）格式的增强，被用作 Mobipocket Reader 的专有格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/ebook/mobi) |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT 文件是使用基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/odt) |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | 带有 OTT 扩展名的文件表示由应用程序生成的符合 OASIS 的 OpenDocument 标准格式的模板文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/ott) |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | 由 Microsoft 引入和记录的富文本格式 (RTF) 代表了一种对格式化文本和图形进行编码以供在应用程序中使用的方法。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/rtf) |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | 带有 .SQL 扩展名的文件表示包含 sql 的文本文档。 |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | 带有 .TXT 扩展名的文件代表一个文本文档，其中包含行形式的纯文本。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/txt) |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
