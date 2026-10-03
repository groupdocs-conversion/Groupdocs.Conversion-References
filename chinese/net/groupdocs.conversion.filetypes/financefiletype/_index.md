---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义金融文档，包括以下类型：Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx。了解更多关于金融格式的信息 herehttps//docs.fileformat.com/finance/。"
type: docs
weight: 1140
url: /zh/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

定义金融文档 包含以下类型：[`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) 了解更多金融格式请点击[此处](https://docs.fileformat.com/finance/)。

```csharp
public sealed class FinanceFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FinanceFileType](financefiletype)() | 序列化构造函数 |

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
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | 在 iXBRL 中，XBRL 的内容被包装在使用 XML 标签的 xHTML 文件格式中。类似 XBRL，它是 iXBRL 文件的根元素。XHTML 格式将其内容表示为不同文档类型和模块的集合。所有 XHTML 文件均基于 XML 文件格式并符合 XML 文档标准。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/finance/ixbrl/)。 |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | 开放金融交换（Open Financial Exchange，OFX）是一种用于交换金融信息的数据流格式，源自微软的开放金融连接（Open Financial Connectivity，OFC）和 Intuit 的开放交换文件格式。了解更多关于此文件格式的信息，请点击[此处](https://en.wikipedia.org/wiki/Open_Financial_Exchange)。 |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL 是一种开放的国际数字商业报告标准，已在全球广泛使用。它是一种基于 XML 的语言，使用称为标签的 XBRL 元素来描述每项业务数据，以便对报告进行排序和分析。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/finance/xbrl/)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
