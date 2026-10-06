---
title: "load-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Configureer brondocument voor conversie."
type: docs
url: /nl/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Configureer brondocument voor conversie.

```python
def load(cls, file_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `str` | Brondocument. |

## load {#file_name}

Configureer set van brondocumenten.

```python
def load(cls, file_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `list[str]` | Array van bronbestanden. |

## load {#document_stream_provider}

Configureer brondocumentstroom.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Provider voor brondocumentstream. |

## load {#document_stream_provider}

Configureer een set van brondocumentstromen.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Set van brondocumentstreams provider. |

### Zie ook
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
