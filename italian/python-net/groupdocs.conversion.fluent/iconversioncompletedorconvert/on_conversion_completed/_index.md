---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Riceve lo stream del documento convertito."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Riceve lo stream del documento convertito. Si attiva solo se `ConvertTo(string fileName)` o `ConvertTo(convertedStreamProvider)` è impostato.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Provider dello stream del documento convertito (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### Vedi anche
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
