---
title: "CompressionConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 Compression 文件类型的选项。"
type: docs
weight: 1750
url: /zh/net/groupdocs.conversion.options.convert/compressionconvertoptions/
---
## CompressionConvertOptions class

转换为 Compression 文件类型的选项。

```csharp
public class CompressionConvertOptions : ConvertOptions<CompressionFileType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CompressionConvertOptions](compressionconvertoptions)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [Password](../../groupdocs.conversion.options.convert/compressionconvertoptions/password) { get; set; } | 如果您想使用密码保护转换后的文档，请设置此属性。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CompressionFileType](../../groupdocs.conversion.filetypes/compressionfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
