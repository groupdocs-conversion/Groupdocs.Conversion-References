---
title: "WithOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "为转换过程设置转换选项。"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

为转换过程设置转换选项。

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 转换选项。 |

### 返回值

处理程序阶段，用于继续构建转换。

### 另见

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

使用提供程序函数设置转换选项。

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionsProvider | Func`2 | 根据转换上下文提供转换选项的函数。 |

### 返回值

处理程序阶段，用于继续构建转换。

### 另见

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
