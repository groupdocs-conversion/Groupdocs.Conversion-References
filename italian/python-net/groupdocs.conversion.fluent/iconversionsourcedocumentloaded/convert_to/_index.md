---
title: "Metodo convert_to"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Salva il documento convertito come file."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Salva il documento convertito come file.

```python
def convert_to(self, file_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `str` | Documento convertito. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Salva il documento convertito come stream.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Provider di stream del documento convertito converted_stream_provider arg1arg1: Il contesto di salvataggio |

**Returns:** Options or handler setup interface to continue conversion building

### Vedi anche
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
