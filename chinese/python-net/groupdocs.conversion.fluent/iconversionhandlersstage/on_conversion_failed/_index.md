---
title: "on_conversion_failed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "注册一个回调函数，在文档转换失败时调用。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

注册一个回调函数，在文档转换失败时调用。

```python
def on_conversion_failed(self, on_failed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | 一个操作，用于处理失败，接收转换上下文以及导致失败的异常。 |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### 另见
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
