---
title: "compress yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm sonuçlarını sıkıştırır; giriş aşamasında IConversionSettings.withevents (OnCompressionCompleted ayarlanarak) sıkıştırılmış‑akış işleyicisini kaydedin, kullanımdan kaldırılmış akıcı zinciri kullanmak yerine…"
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Dönüşüm sonuçlarını sıkıştırır; eski akıcı zincir yöntemini kullanmak yerine giriş aşamasında [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla sıkıştırılmış akış işleyicisi kaydedin (`OnCompressionCompleted` ayarlanarak).

```python
def compress(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Sıkıştırma dönüştürme seçenekleri. |

**Returns:** Continuation that proceeds to `Convert`.

### Ayrıca Bakınız
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
