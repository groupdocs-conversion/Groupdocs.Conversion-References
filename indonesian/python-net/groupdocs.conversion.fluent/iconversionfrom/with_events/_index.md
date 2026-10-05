---
title: "metode with_events"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Daftarkan penangan peristiwa siklus hidup konversi pada tas ConversionEvents yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Daftarkan penangan peristiwa siklus hidup konversi pada kantong [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi.

Dapat dipanggil sebelum atau sesudah [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
Beberapa pemanggilan akan terakumulasi: tas internal yang sama diteruskan ke setiap aksi `configure`, sehingga penangan yang ditetapkan pada pemanggilan sebelumnya tetap ada kecuali ditimpa oleh pemanggilan berikutnya.

```python
def with_events(self, configure):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Aksi yang mengubah kantong peristiwa. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Lihat Juga
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
