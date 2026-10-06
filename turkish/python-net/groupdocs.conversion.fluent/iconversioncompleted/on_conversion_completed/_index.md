---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülmüş belge akışını alır ve yalnızca ConvertTo(string fileName) veya ConvertTo(convertedStreamProvider) ayarlandığında tetiklenir."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Dönüştürülmüş belge akışını alır ve yalnızca `ConvertTo(string fileName)` veya `ConvertTo(convertedStreamProvider)` ayarlandığında tetiklenir.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Dönüştürülmüş belge akışı sağlayıcısı. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
