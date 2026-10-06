---
title: "método load"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Establece el nombre de archivo del documento fuente."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Establece el nombre de archivo del documento fuente.

```python
def load(self, file_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `str` | Documento de origen. |

## load {#file_name}

Establece la matriz de documentos fuente.

```python
def load(self, file_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `list[str]` | Conjunto de documentos de origen. |

## load {#document_stream_provider}

Establece el flujo del documento fuente.

```python
def load(self, document_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Proveedor de flujo de documento de origen. |

| Genera | Descripción |
| :- | :- |
| `InvalidConverterSettingsException` | Si la validación de la configuración del convertidor falla. |

## load {#document_stream_provider}

Establece el proveedor de flujos de documentos fuente.

```python
def load(self, document_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Proveedor de flujos de documentos de origen. |

| Genera | Descripción |
| :- | :- |
| `InvalidConverterSettingsException` | Si la validación de la configuración del convertidor falla. |

### Ver también
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
