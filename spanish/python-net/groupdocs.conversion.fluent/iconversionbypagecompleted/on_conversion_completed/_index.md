---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recibe el flujo de página convertido."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Recibe el flujo de página convertido. Se disparará solo si `ConvertTo(convertedStreamProvider)` está configurado.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Proveedor del flujo de página convertido. El `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
