---
title: "on_conversion_failed metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir belge dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Bir belge dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Başarısızlığı işlemek için bir eylem, dönüşüm bağlamını ve hataya neden olan istisnayı alır. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Ayrıca Bakınız
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
