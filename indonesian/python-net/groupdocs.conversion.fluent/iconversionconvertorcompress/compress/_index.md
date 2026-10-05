---
title: "metode compress"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengompresi hasil konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/compress/
is_root: false
weight: 1010
---


## compress {#options}

Mengompresi hasil konversi.

Daftarkan penangan aliran terkompresi pada tahap masuk melalui [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (mengatur `OnCompressionCompleted`) alih-alih melalui metode rantai fluent yang usang pada antarmuka yang dikembalikan.

```python
def compress(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opsi konversi kompresi |

**Returns:** Continuation that proceeds to `Convert`.

### Lihat Juga
* class [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/)
