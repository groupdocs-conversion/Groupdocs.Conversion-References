---
title: "Metodo on_conversion_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di pagina fallisce."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_failed/
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
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – un'azione per gestire il fallimento, ricevendo il contesto della pagina convertita e l'eccezione che ha causato il fallimento. |

**Returns:** IConversionByPageHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Vedi anche
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
