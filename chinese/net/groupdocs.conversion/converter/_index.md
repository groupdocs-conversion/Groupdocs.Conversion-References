---
title: Converter
second_title: GroupDocs.Conversion for .NET API 参考
description: 表示控制文档转换过程的主类
type: docs
weight: 730
url: /zh/net/groupdocs.conversion/converter/
---
## Converter class

表示控制文档转换过程的主类。

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Converter](converter#constructor)() | 初始化新实例[`Converter`](../converter)流利转换设置类. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_7)(string) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 初始化新实例[`Converter`](../converter)类. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | 初始化新实例[`Converter`](../converter)类. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。逐页保存转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | 转换源文档。保存整个转换后的文档。 |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | 转换源文档。保存整个转换后的文档。 |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | 释放资源。 |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | 获取源文档信息 - 页数和特定于文件类型的其他文档属性。 |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | 获取源文档的可能转换。 |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | 配置源文件stream |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | 配置源文件集streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | 配置转换源文档 |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | 配置源文件集 |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | 配置转换设置 |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | 获取所有支持的转换 |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | 为提供的文档扩展名 获取支持的转换 |

### 也可以看看

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* 命名空间 [GroupDocs.Conversion](../../groupdocs.conversion)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
