---
title: "with_events 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在入口阶段使用转换生命周期事件处理程序启动流畅链。"
type: docs
url: /zh/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

在入口阶段使用转换生命周期事件处理程序启动流畅链。

```python
def with_events(cls, configure):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | 可调用对象，用于修改 `ConversionEvents` 包。 |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### 另见
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
