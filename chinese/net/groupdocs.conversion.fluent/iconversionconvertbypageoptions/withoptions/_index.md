---
title: "WithOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "设置转换选项"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

设置转换选项

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 转换选项 |

### 返回值

用于继续构建转换的接口

### 另见

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

设置转换选项

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 转换选项 [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### 返回值

用于继续构建转换的接口

### 另见

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
