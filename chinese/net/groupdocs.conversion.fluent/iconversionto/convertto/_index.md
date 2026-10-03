---
title: "ConvertTo"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "将转换后的文档保存为文件"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

将转换后的文档保存为文件

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 已转换的文档 |

### 返回值

选项或处理程序设置接口，用于继续构建转换

### 另见

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

将转换后的文档保存为流

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | 已转换文档流提供程序 保存上下文 |

### 返回值

选项或处理程序设置接口，用于继续构建转换

### 另见

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
