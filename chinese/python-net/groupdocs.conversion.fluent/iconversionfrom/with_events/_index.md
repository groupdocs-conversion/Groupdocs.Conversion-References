---
title: "with_events 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在 ConversionEvents 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

在一个 [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。

可以在 [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) 之前或之后调用。
多次调用会累积：相同的内部包会传递给每个 `configure` 操作，因此早期调用设置的处理程序会保留，除非被后续调用覆盖。

```python
def with_events(self, configure):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | 修改事件包的操作。 |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### 另见
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
