---
title: "convert_by_page_to método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Guardar página convertida como flujo."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionto/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Guardar página convertida como flujo.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Proveedor de flujo de página del documento convertido. converted_stream_provider arg1arg1: El contexto de guardado. |

**Returns:** Page options or handler setup interface to continue conversion building.

### Ver también
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
