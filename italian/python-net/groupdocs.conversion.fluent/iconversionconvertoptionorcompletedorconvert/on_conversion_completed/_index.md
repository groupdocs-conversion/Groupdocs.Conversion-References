---
title: "on_conversion_completed metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Riceve lo stream del documento convertito."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Riceve lo stream del documento convertito. Viene invocato solo quando `ConvertTo(string fileName)` o `ConvertTo(convertedStreamProvider)` è stato configurato.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Provider per lo stream del documento convertito. Il provider riceve un `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### Vedi anche
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
