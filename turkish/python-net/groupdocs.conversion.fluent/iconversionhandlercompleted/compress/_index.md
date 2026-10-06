---
title: "compress yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürme sonuçlarını sıkıştırır ve Convert işlemine devam eden bir devam nesnesi döndürür."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Dönüştürme sonuçlarını sıkıştırır ve `Convert` işlemine devam eden bir devam nesnesi döndürür.

Giriş aşamasında bir sıkıştırılmış‑akış işleyicisini [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla (`OnCompressionCompleted` ayarlayarak) kaydedin, döndürülen arabirimdeki eski akıcı zincir yöntemini kullanmak yerine.

```python
def compress(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Sıkıştırma dönüştürme seçenekleri. |

**Returns:** Continuation that proceeds to `Convert`.

### Ayrıca Bakınız
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
