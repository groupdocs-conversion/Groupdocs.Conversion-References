---
title: "FileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "文件类型基类"
type: docs
weight: 1130
url: /zh/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

文件类型基类

```csharp
public class FileType : Enumeration
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileType](filetype)() | 序列化构造函数 |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | 获取提供的 fileExtension 的 FileType |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | 返回指定 fileName 的 FileType |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | 返回提供的文档流的 FileType |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | 实现 [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | 返回所有枚举值。 |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | 隐式转换为字符串 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | 未知文件类型 |

### 另见

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
