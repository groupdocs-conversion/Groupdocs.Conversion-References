---
title: "on_conversion_failed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "注册一个回调函数，在页面转换失败时调用。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

注册一个回调，以在页面转换失败时调用。重新调用将替换任何先前设置的处理程序。

```python
def on_conversion_failed(self, on_failed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | 可调用对象，用于处理失败，接收已转换的页面上下文以及导致失败的异常。 |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### 另见
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
