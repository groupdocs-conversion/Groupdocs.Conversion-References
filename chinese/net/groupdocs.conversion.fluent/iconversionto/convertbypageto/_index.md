---
title: "ConvertByPageTo"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "将转换后的页面保存为流"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionto/convertbypageto/
---
## IConversionTo.ConvertByPageTo method

将转换后的页面保存为流

```csharp
public IConversionByPageOptionsOrHandlerSetup ConvertByPageTo(
    Func<SavePageContext, Stream> convertedStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | 已转换文档页面流提供程序 保存上下文 |

### 返回值

页面选项或处理程序设置接口，用于继续构建转换

### 另见

* interface [IConversionByPageOptionsOrHandlerSetup](../../iconversionbypageoptionsorhandlersetup)
* class [SavePageContext](../../../groupdocs.conversion/savepagecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
