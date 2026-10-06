---
title: "Metodo on_conversion_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di documento fallisce."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registra una callback da invocare quando una conversione di documento fallisce.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable che gestisce il fallimento, ricevendo il contesto di conversione e l'eccezione che ha causato il fallimento. |

**Returns:** IConversionHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Vedi anche
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
