---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir sayfa dönüşümü başarıyla tamamlandığında çağrılacak bir geri aramayı kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Bir sayfa dönüşümü başarıyla tamamlandığında çağrılacak bir geri aramayı kaydeder.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Tamamlamayı ele almak için bir eylem, dönüştürülmüş sayfa bağlamını alır. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Ayrıca Bakınız
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
