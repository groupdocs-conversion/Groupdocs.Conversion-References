---
title: "metodo load"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Configura il documento sorgente per la conversione."
type: docs
url: /it/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Configura il documento sorgente per la conversione.

```python
def load(cls, file_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `str` | Documento di origine. |

## load {#file_name}

Configura l'insieme di documenti sorgente.

```python
def load(cls, file_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `list[str]` | Array di file sorgente. |

## load {#document_stream_provider}

Configura lo stream del documento sorgente.

```python
def load(cls, document_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Provider di flusso del documento di origine. |

## load {#document_stream_provider}

Configura un insieme di stream di documenti sorgente.

```python
def load(cls, document_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Provider di set di flussi di documenti sorgente. |

### Vedi anche
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
