---
title: "on_conversion_failed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de documento falle."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra una devolución de llamada que se invocará cuando una conversión de documento falle.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable que maneja el error, recibiendo el contexto de conversión y la excepción que causó el error. |

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Ver también
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
