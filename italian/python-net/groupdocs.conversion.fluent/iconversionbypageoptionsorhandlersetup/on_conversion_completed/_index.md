---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra una callback da invocare quando una conversione di pagina termina con successo."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registra una callback da invocare quando una conversione di pagina termina con successo.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Un'azione per gestire il completamento, ricevendo il contesto della pagina convertita. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Vedi anche
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
