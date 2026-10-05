---
title: "convert_to 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "将转换后的文档保存为文件。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionto/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

将转换后的文档保存为文件。

```python
def convert_to(self, file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `str` | 已转换的文档 |

**Returns:** Options or handler setup interface to continue conversion building

## convert_to {#converted_stream_provider}

将转换后的文档保存为流。

```python
def convert_to(self, converted_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | 已转换的文档流提供程序。保存上下文。 |

**Returns:** Options or handler setup interface to continue conversion building.

### 另见
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
