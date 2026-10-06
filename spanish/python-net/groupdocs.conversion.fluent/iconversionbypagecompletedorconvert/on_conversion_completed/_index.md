---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recibe el flujo de página convertido."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Recibe el flujo de la página convertida. Se dispara solo si `ConvertTo(convertedStreamProvider)` está configurado.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Proveedor de flujo de página convertido. El proveedor recibe un `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
