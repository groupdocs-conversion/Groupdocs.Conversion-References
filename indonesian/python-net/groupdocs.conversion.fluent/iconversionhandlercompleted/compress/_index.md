---
title: "metode compress"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengompresi hasil konversi dan mengembalikan kelanjutan yang melanjutkan ke Convert."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Mengompres hasil konversi dan mengembalikan lanjutan yang melanjutkan ke `Convert`.

Daftarkan handler aliran terkompresi pada tahap masuk melalui [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (menetapkan `OnCompressionCompleted`) alih-alih menggunakan metode rantai fluent yang usang pada antarmuka yang dikembalikan.

```python
def compress(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opsi konversi kompresi. |

**Returns:** Continuation that proceeds to `Convert`.

### Lihat Juga
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
