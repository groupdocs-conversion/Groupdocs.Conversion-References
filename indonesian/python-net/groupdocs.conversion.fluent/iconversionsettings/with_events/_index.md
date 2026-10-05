---
title: "metode with_events"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan handler peristiwa siklus hidup konversi pada tas ConversionEvents yang hidup selama masa pakai konverter dan dipicu pada setiap eksekusi konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Mendaftarkan handler peristiwa siklus hidup konversi pada kantong [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi.

Berada pada tahap masuk yang sama dengan [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Beberapa pemanggilan diakumulasi: kantong internal yang sama diteruskan ke setiap aksi `configure`, sehingga handler yang diatur pada pemanggilan sebelumnya tetap ada kecuali ditimpa oleh pemanggilan yang lebih baru.

```python
def with_events(self, configure):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Aksi yang mengubah kantong peristiwa. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Lihat Juga
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
