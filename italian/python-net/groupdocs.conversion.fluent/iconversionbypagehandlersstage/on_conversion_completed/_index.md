---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando la conversione di una pagina termina con successo, sostituendo qualsiasi handler impostato precedentemente alla reinvocazione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una callback da invocare quando la conversione di una pagina termina con successo, sostituendo qualsiasi handler impostato precedentemente alla reinvocazione.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Un'azione per gestire il completamento, ricevendo il contesto della pagina convertita. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Vedi anche
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
