---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri aramayı kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri arama kaydeder. Yeniden çağırma, daha önce ayarlanmış işleyiciyi değiştirir.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Tamamlamayı işleyen, dönüşüm bağlamını alan bir çağrılabilir. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Ayrıca Bakınız
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
