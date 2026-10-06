---
title: "método load"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Configura el documento fuente para la conversión."
type: docs
url: /es/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Configura el documento fuente para la conversión.

```python
def load(cls, file_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `str` | Documento de origen. |

## load {#file_name}

Configura el conjunto de documentos fuente.

```python
def load(cls, file_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `list[str]` | Matriz de archivos fuente. |

## load {#document_stream_provider}

Configura el flujo del documento fuente.

```python
def load(cls, document_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Proveedor de flujo de documento de origen. |

## load {#document_stream_provider}

Configura un conjunto de flujos de documentos fuente.

```python
def load(cls, document_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Conjunto del proveedor de flujos de documentos fuente. |

### Ver también
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
