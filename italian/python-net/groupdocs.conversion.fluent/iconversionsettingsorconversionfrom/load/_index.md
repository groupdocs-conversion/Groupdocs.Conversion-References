---
title: "metodo load"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Imposta il nome file del documento sorgente."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Imposta il nome file del documento sorgente.

```python
def load(self, file_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `str` | Documento di origine. |

## load {#file_name}

Imposta l'array dei documenti di origine.

```python
def load(self, file_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `list[str]` | Insieme di documenti di origine. |

## load {#document_stream_provider}

Imposta lo stream del documento sorgente.

```python
def load(self, document_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Provider del flusso del documento sorgente |

| Genera | Descrizione |
| :- | :- |
| `InvalidConverterSettingsException` | Se la convalida delle impostazioni del convertitore fallisce, verrà sollevata questa eccezione |

## load {#document_stream_provider}

Imposta l'array dei flussi dei documenti di origine.

```python
def load(self, document_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Provider di flussi del documento di origine. |

| Genera | Descrizione |
| :- | :- |
| `InvalidConverterSettingsException` | Se la convalida delle impostazioni del convertitore fallisce. |

### Vedi anche
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
