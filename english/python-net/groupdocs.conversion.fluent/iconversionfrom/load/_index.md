---
title: load method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Sets the source document file name."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Sets the source document file name.

```python
def load(self, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | Source document. |

## load {#file_name}

Sets source documents array.

```python
def load(self, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `list[str]` | Set of source documents. |

## load {#document_stream_provider}

Set source document stream.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Source document stream provider. |

| Raises | Description |
| :- | :- |
| `InvalidConverterSettingsException` | If validation of converter settings fails. |

## load {#document_stream_provider}

Sets the source document streams provider.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Source document streams provider. |

| Raises | Description |
| :- | :- |
| `InvalidConverterSettingsException` | If validation of converter settings fails. |

### See Also
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
