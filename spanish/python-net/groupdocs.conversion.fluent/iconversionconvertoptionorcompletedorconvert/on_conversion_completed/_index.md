---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recibe el flujo del documento convertido."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Recibe el flujo del documento convertido. Se invoca solo cuando `ConvertTo(string fileName)` o `ConvertTo(convertedStreamProvider)` han sido configurados.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Proveedor para el flujo del documento convertido. El proveedor recibe un `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
