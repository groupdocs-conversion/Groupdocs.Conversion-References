---
title: "load-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt de bestandsnaam van het brondocument in."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
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

Stel de array met bron documenten in.

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
| document_stream_provider | `Func[io.RawIOBase]` | Bron‑document‑stream‑provider |

| Werpt | Beschrijving |
| :- | :- |
| `InvalidConverterSettingsException` | Als de validatie van de converter‑instellingen mislukt, wordt deze uitzondering gegooid |

## load {#document_stream_provider}

Stel de array met bron documentstreams in.

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
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
