---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "当转换无法运行是因为其依赖的程序集未在应用程序输出中出现时，GroupDocs 抛出的异常。文档本身没有错误。"
type: docs
weight: 1030
url: /zh/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

当转换无法运行是因为其依赖的程序集未包含在应用程序的输出中时抛出的 GroupDocs 异常。文档本身没有错误。

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | 默认构造函数 |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | 创建带有消息的异常实例 |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | 创建带有消息的异常实例并传播内部异常 |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | 创建指明无法加载的程序集的异常实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | 无法加载的程序集的简单名称；如果无法确定，则为 null。 |

### 另见

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
