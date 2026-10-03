---
title: "NoConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "特殊转换选项类，指示转换器在不进行任何处理的情况下复制源文档"
type: docs
weight: 2020
url: /zh/net/groupdocs.conversion.options.convert/noconvertoptions/
---
## NoConvertOptions class

特殊转换选项类，用于指示转换器在不进行任何处理的情况下复制源文档。

```csharp
public sealed class NoConvertOptions : ConvertOptions<FileType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [NoConvertOptions](noconvertoptions)() | 使用默认格式初始化 [`NoConvertOptions`](../noconvertoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
