---
title: "convert_to método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Guardar documento convertido como archivo."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Guardar documento convertido como archivo.

```python
def convert_to(self, file_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `str` | Documento convertido. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Guarda el documento convertido como un flujo.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Proveedor de flujo del documento convertido. El contexto de guardado. |

**Returns:** Options or handler setup interface to continue conversion building.

### Ver también
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
