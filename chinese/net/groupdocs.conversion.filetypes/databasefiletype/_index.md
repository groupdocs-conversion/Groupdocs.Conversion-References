---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义数据库文档。包含以下文件类型 Nsf./databasefiletype/nsf Log./databasefiletype/log Sql./databasefiletype/sql"
type: docs
weight: 1090
url: /zh/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

定义数据库文档。包含以下文件类型：[`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | 序列化构造函数 |

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
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | 带有 .log 扩展名的文件包含带时间戳的纯文本列表。通常，软件或操作系统会记录某些活动细节，以帮助开发者或用户追踪特定时间段内发生的情况。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/database/log)。 |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | 带有 .nsf（Notes Storage Facility）扩展名的文件是 IBM Notes 软件使用的数据库文件格式，之前称为 Lotus Notes。它定义了用于存储电子邮件、约会、文档、表单和视图等各种对象的模式。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/database/nsf)。 |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | 带有 .sql 扩展名的文件是结构化查询语言（SQL）文件，包含用于关系数据库的代码。它用于编写执行 CRUD（创建、读取、更新和删除）操作的 SQL 语句。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/database/sql)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
