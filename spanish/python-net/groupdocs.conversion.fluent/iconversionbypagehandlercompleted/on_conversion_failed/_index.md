---
title: "on_conversion_failed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de página falle."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra un callback que se invocará cuando falle la conversión de una página. Reinvocar reemplaza cualquier controlador previamente establecido.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable que maneja el error, recibiendo el contexto de la página convertida y la excepción que causó el error. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Ver también
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
