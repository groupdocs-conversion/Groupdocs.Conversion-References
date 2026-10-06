---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülmüş sayfa akışını alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Dönüştürülmüş sayfa akışını alır. Yalnızca `ConvertTo(convertedStreamProvider)` ayarlanmışsa tetiklenir.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Dönüştürülmüş sayfa akışı sağlayıcısı. `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
