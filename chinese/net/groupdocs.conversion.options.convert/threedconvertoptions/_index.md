---
title: "ThreeDConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 3D 类型的选项。"
type: docs
weight: 2250
url: /zh/net/groupdocs.conversion.options.convert/threedconvertoptions/
---
## ThreeDConvertOptions class

转换为 3D 类型的选项。

```csharp
public class ThreeDConvertOptions : ConvertOptions<ThreeDFileType>, IPagedConvertOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ThreeDConvertOptions](threedconvertoptions)() | 初始化 [`ThreeDConvertOptions`](../threedconvertoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/threedconvertoptions/pagenumber) { get; set; } | 实现 [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PagesCount](../../groupdocs.conversion.options.convert/threedconvertoptions/pagescount) { get; set; } | 实现 [`PagesCount`](../ipagedconvertoptions/pagescount) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [ThreeDFileType](../../groupdocs.conversion.filetypes/threedfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
