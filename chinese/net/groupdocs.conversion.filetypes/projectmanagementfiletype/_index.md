---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义由项目管理软件（如 Microsoft Project、Primavera P6 等）创建的项目文件格式。项目文件是任务、资源及其调度的集合，用于以产品或服务的形式获得可衡量的输出。项目管理文档。包括以下文件类型 Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx。了解更多项目管理格式，请访问 https://wiki.fileformat.com/projectmanagement。"
type: docs
weight: 1220
url: /zh/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

定义由项目管理软件（如 Microsoft Project、Primavera P6 等）创建的项目文件格式。项目文件是任务、资源及其调度的集合，用于以产品或服务的形式获得可衡量的输出。项目管理文档。包括以下文件类型：[`Mpp`](./mpp)，[`Mpt`](./mpt)，[`Mpx`](./mpx)。了解更多项目管理格式，请点击[here](https://wiki.fileformat.com/project-management)。

```csharp
public sealed class ProjectManagementFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | 序列化构造函数 |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP 是 Microsoft Project 数据文件，以集成方式存储与项目管理相关的信息。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/project-management/mpp)。 |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Microsoft Project 模板文件包含基本信息和结构以及文档设置，用于创建 .MPP 文件。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/project-management/mpt)。 |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange 文件格式是一种 ASCII 文件格式，用于在 Microsoft Project（MSP）与其他支持 MPX 文件格式的应用程序（如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。了解更多此文件格式，请点击[here](https://wiki.fileformat.com/project-management/mpx)。 |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | XER 文件格式是 Primavera P6 项目规划和管理应用程序使用的专有项目文件格式。了解更多此文件格式，请点击[here](https://docs.fileformat.com/project-management/xer)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
