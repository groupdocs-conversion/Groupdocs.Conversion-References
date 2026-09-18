---
title: load method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Configure source document for conversion."
type: docs
url: /python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Configure source document for conversion.

```python
def load(cls, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | Source document. |

## load {#file_name}

Configure set of source documents.

```python
def load(cls, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `list[str]` | Array of source files. |

## load {#document_stream_provider}

Configure source document stream.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Source document stream provider. |

## load {#document_stream_provider}

Configure a set of source document streams.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Set of source document streams provider. |

### See Also
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
