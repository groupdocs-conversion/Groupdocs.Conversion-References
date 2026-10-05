---
title: "on_conversion_completed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "注册一个回调函数，在页面转换成功完成时调用。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

注册一个回调函数，在页面转换成功完成时调用。

重新调用会替换任何先前设置的处理程序。

```python
def on_conversion_completed(self, on_completed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | 一个用于处理完成的操作，接收已转换的页面上下文。 |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### 另见
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
