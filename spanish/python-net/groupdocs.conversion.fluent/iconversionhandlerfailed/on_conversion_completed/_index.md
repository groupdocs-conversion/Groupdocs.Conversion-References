---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito. Re‑invocar reemplaza cualquier controlador previamente establecido.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Callable que maneja la finalización, recibiendo el contexto de conversión. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Ver también
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
