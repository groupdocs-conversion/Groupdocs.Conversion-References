---
title: "load‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Konfigurera källdokument för konvertering."
type: docs
url: /sv/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Konfigurera källdokument för konvertering.

```python
def load(cls, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Källdokument. |

## load {#file_name}

Konfigurera uppsättning av källdokument.

```python
def load(cls, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `list[str]` | Array av källfiler. |

## load {#document_stream_provider}

Konfigurera ström för källdokument.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Leverantör av ström för källdokument. |

## load {#document_stream_provider}

Konfigurera en uppsättning av strömmar för källdokument.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Uppsättning av leverantör för källdokumentströmmar. |

### Se även
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
