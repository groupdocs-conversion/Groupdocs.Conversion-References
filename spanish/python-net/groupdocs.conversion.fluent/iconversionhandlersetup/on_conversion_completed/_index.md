---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Una acción para manejar la finalización, recibiendo el contexto de conversión. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Ver también
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
