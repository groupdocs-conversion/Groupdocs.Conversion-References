---
title: "on_conversion_failed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "注册一个回调函数，在文档转换失败时调用。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

注册一个回调函数，在文档转换失败时调用。重新注册会替换之前设置的处理程序。

```python
def on_conversion_failed(self, on_failed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – 处理失败的操作，接收转换上下文和导致失败的异常。 |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### 另见
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
