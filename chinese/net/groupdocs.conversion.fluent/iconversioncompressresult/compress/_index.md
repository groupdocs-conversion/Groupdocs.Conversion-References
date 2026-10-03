---
title: "Compress"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "调用此方法以压缩转换结果。通过 WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents 在入口阶段注册 compressedstream 处理程序，设置 OnCompressionCompleted。"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

调用此方法以压缩转换结果。通过 [`WithEvents`](../../iconversionsettings/withevents) 在入口阶段注册 compressed-stream 处理程序（设置 `OnCompressionCompleted`）。

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 选项 | CompressionConvertOptions | 压缩转换选项 |

### 返回值

继续执行至 `Convert`。

### 另见

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
