---
title: "load-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt de bestandsnaam van het brondocument in."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Stelt de bestandsnaam van het brondocument in.

```python
def load(self, file_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `str` | Brondocument. |

## load {#file_name}

Stelt de array met brondocumenten in.

```python
def load(self, file_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `list[str]` | Set van brondocumenten. |

## load {#document_stream_provider}

Stel de brondocumentstroom in.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Provider voor brondocumentstream. |

| Werpt | Beschrijving |
| :- | :- |
| `InvalidConverterSettingsException` | Als de validatie van converterinstellingen mislukt. |

## load {#document_stream_provider}

Stelt de provider van brondocumentstromen in.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Provider voor brondocumentstreams. |

| Werpt | Beschrijving |
| :- | :- |
| `InvalidConverterSettingsException` | Als de validatie van converterinstellingen mislukt. |

### Zie ook
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
