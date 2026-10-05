---
title: "with_options 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "设置加载选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

设置加载选项。

```python
def with_options(self, load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| load_options | `LoadOptions` | 加载选项。 |

## with_options {#load_options_provider}

为当前正在加载的文档提供加载选项。

```python
def with_options(self, load_options_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | 加载选项提供程序。该提供程序接收加载选项上下文。 |

### 另见
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
