---
title: "with_options 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "为转换过程设置转换选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

为转换过程设置转换选项。

```python
def with_options(self, convert_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 转换选项。 |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

使用提供程序函数设置转换选项。

```python
def with_options(self, options_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | 一个根据转换上下文提供转换选项的函数。 |

**Returns:** Handler setup interface to continue conversion building.

### 另见
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
