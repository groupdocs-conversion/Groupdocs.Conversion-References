---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di documento termina con successo."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una callback da invocare quando una conversione di documento termina con successo. La reinvocazione sostituisce qualsiasi gestore precedentemente impostato.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Callable che gestisce il completamento, ricevendo il contesto di conversione. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Vedi anche
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
