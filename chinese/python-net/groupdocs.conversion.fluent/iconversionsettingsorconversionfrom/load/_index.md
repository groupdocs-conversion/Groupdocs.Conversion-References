---
title: "load 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "设置源文档文件名。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

设置源文档文件名。

```python
def load(self, file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `str` | 源文档。 |

## load {#file_name}

设置源文档数组。

```python
def load(self, file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `list[str]` | 源文档集合。 |

## load {#document_stream_provider}

设置源文档流。

```python
def load(self, document_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | 源文档流提供程序 |

| 引发 | 描述 |
| :- | :- |
| `InvalidConverterSettingsException` | 如果转换器设置的验证失败，将抛出此异常 |

## load {#document_stream_provider}

设置源文档流数组。

```python
def load(self, document_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | 源文档流提供程序。 |

| 引发 | 描述 |
| :- | :- |
| `InvalidConverterSettingsException` | 如果转换器设置的验证失败。 |

### 另见
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
