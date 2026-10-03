---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "接收已转换的页面流。仅在设置了 ConvertToconvertedStreamProvider 时触发。"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

接收已转换的页面流。仅在设置了 "ConvertTo(convertedStreamProvider)" 时触发。

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertedPageStream | Action`1 | 已转换页面流提供程序 [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### 返回值

用于继续构建转换的接口

### 另见

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
