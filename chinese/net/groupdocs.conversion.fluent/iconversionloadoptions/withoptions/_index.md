---
title: "WithOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "设置加载选项"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

设置加载选项

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadOptions | LoadOptions | 加载选项 |

### 另见

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

提供当前正在加载的文档的加载选项

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | 加载选项提供程序 加载选项上下文 |

### 另见

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
