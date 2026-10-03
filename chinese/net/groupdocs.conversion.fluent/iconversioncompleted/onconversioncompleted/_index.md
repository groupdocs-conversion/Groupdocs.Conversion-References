---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "接收已转换的文档流。仅在设置了 ConvertTostring fileName 或 ConvertToconvertedStreamProvider 时触发。"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

接收已转换的文档流。仅在设置了 "ConvertTo(string fileName)" 或 ConvertTo(convertedStreamProvider)" 时触发。

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertedFileStream | Action`1 | 已转换文档流提供程序 [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### 返回值

用于继续构建转换的接口

### 另见

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
