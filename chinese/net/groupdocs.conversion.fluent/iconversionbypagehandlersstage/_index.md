---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "已展平的按页转换处理程序阶段。每页镜像 IConversionHandlersStage./iconversionhandlersstage。"
type: docs
weight: 1320
url: /zh/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

已展平的按页转换处理程序阶段。每页镜像 [`IConversionHandlersStage`](../iconversionhandlersstage)。

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | 注册一个回调，当页面转换成功完成时调用。重新调用将替换任何先前设置的处理程序。 |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | 注册一个回调，当页面转换失败时调用。重新调用将替换任何先前设置的处理程序。 |

### 另见

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
