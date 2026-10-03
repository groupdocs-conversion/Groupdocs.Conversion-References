---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 Email 文件类型的选项。"
type: docs
weight: 1800
url: /zh/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

转换为 Email 文件类型的选项。

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | 初始化 [`EmailConvertOptions`](../emailconvertoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | 用于处理电子邮件附件自定义处理的委托。该委托接受附件名称、内容类型和原始附件流作为参数，并返回修改后的附件流。 |
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
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
