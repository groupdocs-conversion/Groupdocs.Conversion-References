---
title: "on_conversion_completed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "接收转换后的文档流，仅在设置了 ConvertTo(string fileName) 或 ConvertTo(convertedStreamProvider) 时触发。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

接收已转换的文档流，仅在设置了 `ConvertTo(string fileName)` 或 `ConvertTo(convertedStreamProvider)` 时触发。

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | 已转换文档流提供程序。 |

**Returns:** Interface to continue conversion building.

### 另见
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
