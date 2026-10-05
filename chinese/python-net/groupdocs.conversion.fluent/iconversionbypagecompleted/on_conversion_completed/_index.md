---
title: "on_conversion_completed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "接收已转换的页面流。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

接收已转换的页面流。仅在设置了 `ConvertTo(convertedStreamProvider)` 时触发。

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | 已转换页面流提供程序。`ConvertedPageContext`。 |

**Returns:** Interface to continue conversion building.

### 另见
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
