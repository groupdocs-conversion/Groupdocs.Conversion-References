---
title: "metode compress"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengompres hasil konversi; daftarkan handler aliran terkompresi pada tahap masuk melalui IConversionSettings.withevents (mengatur OnCompressionCompleted) alih-alih menggunakan fluent yang usang…"
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Mengompres hasil konversi; daftarkan handler aliran‑terkompresi pada tahap masuk melalui [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (menetapkan `OnCompressionCompleted`) alih-alih menggunakan metode rantai lancar yang usang.

```python
def compress(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opsi konversi kompresi. |

**Returns:** Continuation that proceeds to `Convert`.

### Lihat Juga
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
