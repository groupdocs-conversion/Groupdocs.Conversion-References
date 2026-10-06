---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülmüş sayfa akışını alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Dönüştürülmüş sayfa akışını alır. Yalnızca `ConvertTo(convertedStreamProvider)` ayarlandığında tetiklenir.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Dönüştürülmüş sayfa akışı sağlayıcısı. Sağlayıcı bir `ConvertedPageContext` alır. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
