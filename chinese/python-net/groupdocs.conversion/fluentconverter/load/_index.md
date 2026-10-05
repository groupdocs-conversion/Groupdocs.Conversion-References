---
title: "load 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "配置用于转换的源文档。"
type: docs
url: /zh/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

配置用于转换的源文档。

```python
def load(cls, file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `str` | 源文档。 |

## load {#file_name}

配置源文档集合。

```python
def load(cls, file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `list[str]` | 源文件数组。 |

## load {#document_stream_provider}

配置源文档流。

```python
def load(cls, document_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | 源文档流提供程序。 |

## load {#document_stream_provider}

配置一组源文档流。

```python
def load(cls, document_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | 源文档流提供者集合。 |

### 另见
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
