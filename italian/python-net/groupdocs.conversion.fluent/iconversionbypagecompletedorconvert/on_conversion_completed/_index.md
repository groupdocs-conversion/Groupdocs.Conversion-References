---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Riceve lo stream della pagina convertita."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Riceve lo stream della pagina convertita. Si attiva solo se `ConvertTo(convertedStreamProvider)` è impostato.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Provider dello stream della pagina convertita. Il provider riceve un `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Vedi anche
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
