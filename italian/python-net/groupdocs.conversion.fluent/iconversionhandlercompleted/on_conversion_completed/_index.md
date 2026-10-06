---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di documento termina con successo."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una callback da invocare quando una conversione di documento termina con successo.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Un'azione per gestire il completamento, ricevendo il contesto di conversione. |

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Vedi anche
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
