---
title: "compress yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürme sonuçlarını sıkıştırır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/
is_root: false
weight: 1010
---


## compress {#options}

Dönüştürme sonuçlarını sıkıştırır.

Giriş aşamasında sıkıştırılmış‑akış işleyicisini [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) ( `OnCompressionCompleted` ayarlanarak) kaydedin, döndürülen arabirimdeki kullanımdan kaldırılmış akıcı zincir yöntemini kullanmak yerine.

```python
def compress(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Sıkıştırma dönüştürme seçenekleri |

**Returns:** Continuation that proceeds to `Convert`.

### Ayrıca Bakınız
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
