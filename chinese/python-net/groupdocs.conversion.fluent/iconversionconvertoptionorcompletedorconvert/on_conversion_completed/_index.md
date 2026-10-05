---
title: "on_conversion_completed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "接收已转换的文档流。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

接收已转换的文档流。仅在配置了 `ConvertTo(string fileName)` 或 `ConvertTo(convertedStreamProvider)` 时调用。

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | 已转换文档流的提供程序。该提供程序接收一个 `ConvertedContext`。 |

**Returns:** Interface to continue conversion building.

### 另见
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
