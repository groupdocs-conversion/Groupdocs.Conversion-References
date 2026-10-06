---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülmüş sayfa akışını al."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Dönüştürülmüş sayfa akışını al. Yalnızca `ConvertTo(convertedStreamProvider)` ayarlanmışsa tetiklenir.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Dönüştürülmüş sayfa akışı sağlayıcı converted_page_stream arg1arg1: `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Ayrıca Bakınız
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
