---
title: "on_conversion_failed metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir sayfa dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder, yeniden‑invocation sırasında daha önce ayarlanmış olan işleyiciyi değiştirir."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Bir sayfa dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder, yeniden‑invocation sırasında daha önce ayarlanmış olan işleyiciyi değiştirir.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Başarısızlığı ele alan bir çağrılabilir, dönüştürülmüş sayfa bağlamını ve hataya neden olan istisnayı alır. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Ayrıca Bakınız
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
