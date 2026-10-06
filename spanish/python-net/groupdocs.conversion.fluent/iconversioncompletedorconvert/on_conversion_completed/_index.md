---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recibe el flujo del documento convertido."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Recibe el flujo del documento convertido. Se dispara solo si se establece `ConvertTo(string fileName)` o `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Proveedor del flujo del documento convertido (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
