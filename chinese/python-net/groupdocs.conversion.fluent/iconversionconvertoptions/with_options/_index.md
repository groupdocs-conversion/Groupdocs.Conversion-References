---
title: "with_options 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "设置转换选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

设置转换选项。

```python
def with_options(self, convert_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 转换选项 |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

设置转换选项。

```python
def with_options(self, convert_options_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | 转换选项提供程序 convert_options_provider arg1arg1：`ConvertContext` |

**Returns:** Interface to continue conversion building

### 另见
* class [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/)
