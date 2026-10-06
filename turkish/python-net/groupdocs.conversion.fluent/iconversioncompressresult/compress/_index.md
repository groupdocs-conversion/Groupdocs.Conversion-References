---
title: "compress yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm sonuçlarını sıkıştırır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
is_root: false
weight: 1010
---


## compress {#options}

Dönüşüm sonuçlarını sıkıştırır.

Giriş aşamasında bir sıkıştırılmış akış işleyicisini [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla ( `OnCompressionCompleted` ayarlanarak) kaydedin, döndürülen arabirimdeki eski akıcı zincir yöntemi yerine.

```python
def compress(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Sıkıştırma dönüştürme seçenekleri. |

**Returns:** Continuation that proceeds to `Convert`.

### Ayrıca Bakınız
* class [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/)
