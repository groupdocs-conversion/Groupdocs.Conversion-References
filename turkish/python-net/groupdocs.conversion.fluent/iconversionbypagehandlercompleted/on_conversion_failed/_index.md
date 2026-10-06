---
title: "on_conversion_failed metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir sayfa dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Bir sayfa dönüşümü başarısız olduğunda çağrılacak bir geri arama kaydeder. Yeniden çağırma, daha önce ayarlanmış herhangi bir işleyiciyi değiştirir.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Başarısızlığı ele alan bir çağrılabilir, dönüştürülmüş sayfa bağlamını ve hataya neden olan istisnayı alır. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Ayrıca Bakınız
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
