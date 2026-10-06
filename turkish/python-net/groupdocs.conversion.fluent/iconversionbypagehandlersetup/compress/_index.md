---
title: "compress yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Belirtilen seçenekleri kullanarak dönüşüm sonuçlarını sıkıştırır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

Belirtilen seçenekleri kullanarak dönüşüm sonuçlarını sıkıştırır.

Bu metodu, dönüşüm sonuçlarını sıkıştırmak için çağırın. Giriş aşamasında sıkıştırılmış‑akış işleyicisini [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla ( `OnCompressionCompleted` ayarıyla) kaydedin; döndürülen arayüzdeki eski akıcı zincir metodunu kullanmak yerine.

```python
def compress(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Sıkıştırma dönüştürme seçenekleri. |

**Returns:** Continuation that proceeds to `Convert`.

### Ayrıca Bakınız
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
