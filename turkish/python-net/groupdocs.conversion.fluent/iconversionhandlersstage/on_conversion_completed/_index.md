---
title: "on_conversion_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri arama kaydeder, yeniden çağırma sırasında daha önce ayarlanmış işleyiciyi değiştirir."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri arama kaydeder, yeniden çağırma sırasında daha önce ayarlanmış işleyiciyi değiştirir.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Tamamlamayı işlemek için bir eylem, dönüşüm bağlamını alır. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### Ayrıca Bakınız
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
