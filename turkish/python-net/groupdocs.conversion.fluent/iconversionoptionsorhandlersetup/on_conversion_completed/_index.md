---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri aramayı kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri aramayı kaydeder.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Tamamlamayı işlemek için bir eylem, dönüşüm bağlamını alır. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Ayrıca Bakınız
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
