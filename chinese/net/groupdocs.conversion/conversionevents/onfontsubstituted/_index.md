---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "当源文档引用的字体不可用且被替换时触发，替换方式可以是客户提供的 FontSubstitute（groupdocs.conversion.contracts/fontsubstitute）规则、配置的默认字体或转换管道的内部回退。"
type: docs
weight: 80
url: /zh/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

当源文档引用的字体不可用且被替换时触发（替换方式可以是客户提供的 [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute) 规则、配置的默认字体，或转换管道的内部回退）。

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### 备注

该事件在单次 `Converter.Convert(...)` 调用中会基于 `(SourceFileName, OriginalFontName)` 去重——订阅者每个源文档的缺失字体最多收到一次通知。事件在转换线程上同步触发。图像转换时不触发。

对于演示文稿文档，字体替换仅在 Windows 上检测，因为引擎通过特定平台的字体匹配来解析，而在其他操作系统上不可用。

### 另见

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
