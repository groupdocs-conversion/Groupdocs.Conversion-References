---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "已展平的转换处理程序阶段。允许以任意顺序和任意次数设置 OnConversionCompleted 或 OnConversionFailed，然后再继续执行 Convert / Compress。在此阶段应通过 WithEvents./iconversionsettings/withevents 在早期阶段注册事件，而不是在此阶段注册。"
type: docs
weight: 1480
url: /zh/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

已展平的转换处理程序阶段。允许以任意顺序和任意次数设置 `OnConversionCompleted` 或 `OnConversionFailed`，然后再继续执行 `Convert` / `Compress`。应通过 [`WithEvents`](../iconversionsettings/withevents) 在早期阶段注册事件，而不是在此阶段注册。

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | 注册一个回调，当文档转换成功完成时调用。重新调用将替换任何先前设置的处理程序。 |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | 注册一个回调，当文档转换失败时调用。重新调用将替换任何先前设置的处理程序。 |

### 另见

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
