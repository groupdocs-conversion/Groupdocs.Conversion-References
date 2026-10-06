---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito, reemplazando cualquier controlador previamente establecido al re‑invocar."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito, reemplazando cualquier controlador previamente establecido al re‑invocar.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Una acción para manejar la finalización, recibiendo el contexto de conversión. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### Ver también
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
