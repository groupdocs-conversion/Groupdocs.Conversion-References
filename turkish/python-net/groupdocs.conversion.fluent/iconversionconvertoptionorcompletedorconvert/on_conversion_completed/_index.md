---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülmüş belge akışını alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Dönüştürülmüş belge akışını alır. Yalnızca `ConvertTo(string fileName)` veya `ConvertTo(convertedStreamProvider)` yapılandırıldığında çağrılır.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Dönüştürülmüş belge akışı için sağlayıcı. Sağlayıcı bir `ConvertedContext` alır. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
