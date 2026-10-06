---
title: "load‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ställer in källdokumentets filnamn."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Ställer in källdokumentets filnamn.

```python
def load(self, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Källdokument. |

## load {#file_name}

Ange array med källdokument.

```python
def load(self, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `list[str]` | Uppsättning av källdokument. |

## load {#document_stream_provider}

Ställ in källdokumentström.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Källdokumentströmleverantör |

| Kastar | Beskrivning |
| :- | :- |
| `InvalidConverterSettingsException` | Om validering av konverterarinställningar misslyckas kommer detta undantag att kastas |

## load {#document_stream_provider}

Ange array med källdokumentströmmar.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Leverantör av strömmar för källdokument. |

| Kastar | Beskrivning |
| :- | :- |
| `InvalidConverterSettingsException` | Om validering av konverteringsinställningar misslyckas. |

### Se även
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
