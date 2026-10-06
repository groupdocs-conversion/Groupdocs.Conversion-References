---
title: "on_conversion_failed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de página falle."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra una devolución de llamada que se invocará cuando una conversión de página falle.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Una acción para manejar el error, recibiendo el contexto de la página convertida y la excepción que causó el error. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Ver también
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
