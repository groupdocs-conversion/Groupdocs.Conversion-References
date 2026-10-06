---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Ricevi lo stream della pagina convertita."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Riceve lo stream della pagina convertita. Verrà attivato solo se `ConvertTo(convertedStreamProvider)` è impostato.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Provider dello stream della pagina convertita converted_page_stream arg1arg1: Il `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Vedi anche
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
