---
title: "Metodo on_conversion_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di pagina fallisce."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra una callback da invocare quando la conversione di una pagina fallisce. Richiamare nuovamente sostituisce qualsiasi handler impostato in precedenza.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable che gestisce il fallimento, ricevendo il contesto della pagina convertita e l'eccezione che ha causato il fallimento. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Vedi anche
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
