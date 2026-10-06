---
title: "Metodo on_conversion_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di pagina fallisce."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra una callback da invocare quando una conversione di pagina fallisce.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Un'azione per gestire il fallimento, ricevendo il contesto della pagina convertita e l'eccezione che ha causato il fallimento. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Vedi anche
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
