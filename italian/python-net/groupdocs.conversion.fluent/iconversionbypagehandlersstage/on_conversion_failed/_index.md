---
title: "Metodo on_conversion_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando la conversione di una pagina fallisce, sostituendo qualsiasi handler impostato precedentemente alla reinvocazione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra una callback da invocare quando la conversione di una pagina fallisce, sostituendo qualsiasi handler impostato precedentemente alla reinvocazione.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable che gestisce il fallimento, ricevendo il contesto della pagina convertita e l'eccezione che ha causato il fallimento. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Vedi anche
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
