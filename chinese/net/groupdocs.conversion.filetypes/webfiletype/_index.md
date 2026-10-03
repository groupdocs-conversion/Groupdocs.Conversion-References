---
title: "Web文件类型"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义 Web 文档。包括以下文件类型 Xml./webfiletype/xmlJson./webfiletype/jsonHtml./webfiletype/htmlHtm./webfiletype/htmMht./webfiletype/mhtMhtml./webfiletype/mhtmlChm./webfiletype/chm"
type: docs
weight: 1270
url: /zh/net/groupdocs.conversion.filetypes/webfiletype/
---
## WebFileType class

定义 Web 文档。包括以下文件类型：[`Xml`](./xml)[`Json`](./json)[`Html`](./html)[`Htm`](./htm)[`Mht`](./mht)[`Mhtml`](./mhtml)[`Chm`](./chm)

```csharp
public sealed class WebFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WebFileType](webfiletype)() | 序列化构造函数 |

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
| static readonly [Chm](../../groupdocs.conversion.filetypes/webfiletype/chm) | CHM 文件格式表示 Microsoft HTML 帮助文件，它由一系列 HTML 页面组成。它提供索引以快速访问主题，并可导航到帮助文档的不同部分。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/web/chm). |
| static readonly [Htm](../../groupdocs.conversion.filetypes/webfiletype/htm) | HTM（超文本标记语言）是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/web/html). |
| static readonly [Html](../../groupdocs.conversion.filetypes/webfiletype/html) | HTML（超文本标记语言）是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.conversion.filetypes/webfiletype/json) | JSON（JavaScript 对象表示法）是一种开放标准文件格式，用于共享使用人类可读文本存储和传输数据。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/web/json). |
| static readonly [Mht](../../groupdocs.conversion.filetypes/webfiletype/mht) | 带有 MHTML 扩展名的文件表示一种网页存档格式，可由多种不同的应用程序创建。该格式被称为存档格式，因为它将网页 HTML 代码及相关资源保存到单个文件中。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/web/mhtml). |
| static readonly [Mhtml](../../groupdocs.conversion.filetypes/webfiletype/mhtml) | 带有 MHTML 扩展名的文件表示一种网页存档格式，可由多种不同的应用程序创建。该格式被称为存档格式，因为它将网页 HTML 代码及相关资源保存到单个文件中。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/web/mhtml). |
| static readonly [Xml](../../groupdocs.conversion.filetypes/webfiletype/xml) | XML 代表可扩展标记语言，它类似于 HTML，但在使用标签定义对象方面有所不同。了解更多关于此文件格式的信息 [此处](https://wiki.fileformat.com/web/xml). |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
