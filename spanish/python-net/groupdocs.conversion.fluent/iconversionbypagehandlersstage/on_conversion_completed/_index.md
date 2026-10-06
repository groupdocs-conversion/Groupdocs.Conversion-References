---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de página se complete con éxito, reemplazando cualquier controlador previamente establecido en la reinvocación."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una devolución de llamada que se invocará cuando una conversión de página se complete con éxito, reemplazando cualquier controlador previamente establecido en la reinvocación.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Una acción para manejar la finalización, recibiendo el contexto de la página convertida. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Ver también
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
