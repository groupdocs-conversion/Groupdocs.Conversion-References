---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "注册一个回调，在页面转换失败时调用。重新调用会替换任何先前设置的处理程序。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

注册一个回调，当页面转换失败时调用。重新调用将替换任何先前设置的处理程序。

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| onFailed | Action`2 | 一个用于处理失败的操作，接收已转换页面的上下文和导致失败的异常。 |

### 返回值

此阶段，可链式添加额外的处理程序或 `Convert` / `Compress`。

### 另见

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
