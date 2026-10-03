---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Gml 文档的选项。"
type: docs
weight: 2550
url: /zh/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

加载 Gml 文档的选项。

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | 初始化 [`GmlLoadOptions`](../gmlloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | 输入文档的文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | 设置转换 GIS 文档的期望页面高度。默认值为 1000。 |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | 确定是否允许 Conversion 从互联网加载 XML 架构。如果设置为 false，则具有非 ‘file://’ 开头的绝对 URI 的架构将不会被加载。默认值为 false。 |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | 确定是否允许 Conversion 在缺少或无法加载 XML Schema 的 Gml 文件中解析属性。如果设置为 true，Conversion 读取器不需要 XML Schema 的存在。默认值为 false。 |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | 以空格分隔的 URI 对列表。每对中的第一个 URI 是命名空间的 URI，第二个 URI 是该命名空间的 XML 架构路径。如果设置为 null，Conversion 将尝试从文档根元素读取 schemaLocation。默认值为 null。 |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | 设置转换 GIS 文档的期望页面宽度。默认值为 1000。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
