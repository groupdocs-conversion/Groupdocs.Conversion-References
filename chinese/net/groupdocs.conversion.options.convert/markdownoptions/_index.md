---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 markdown 文件类型的选项。"
type: docs
weight: 2010
url: /zh/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

转换为 markdown 文件类型的选项。

```csharp
public sealed class MarkdownOptions : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | 初始化 [`MarkdownOptions`](../markdownoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | 以 base64 导出图像。默认是 true。当设置了 [`ImageSavingCallback`](./imagesavingcallback) 时将被忽略。 |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | 在保存 Markdown 时，每个图像调用一次回调。允许调用者在外部持久化图像并替换文档中嵌入的 URI。当不为 null 时，它的优先级高于 [`ExportImagesAsBase64`](./exportimagesasbase64)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
