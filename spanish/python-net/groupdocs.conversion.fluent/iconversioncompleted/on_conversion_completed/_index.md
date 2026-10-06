---
title: "on_conversion_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recibe el flujo del documento convertido y se dispara solo si ConvertTo(string fileName) o ConvertTo(convertedStreamProvider) está configurado."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Recibe el flujo del documento convertido y se dispara solo si `ConvertTo(string fileName)` o `ConvertTo(convertedStreamProvider)` está configurado.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Proveedor de flujo de documento convertido. |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
