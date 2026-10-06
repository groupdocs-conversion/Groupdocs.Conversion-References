---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di documento termina con successo, sostituendo qualsiasi gestore precedentemente impostato alla reinvocazione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una callback da invocare quando una conversione di documento termina con successo, sostituendo qualsiasi gestore precedentemente impostato alla reinvocazione.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Un'azione per gestire il completamento, ricevendo il contesto di conversione. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### Vedi anche
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
