---
title: "on_conversion_completed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "注册一个回调函数，在文档转换成功完成时调用。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

注册一个回调函数，在文档转换成功完成时调用。

```python
def on_conversion_completed(self, on_completed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | 一个用于处理完成的操作，接收转换上下文。 |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### 另见
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
