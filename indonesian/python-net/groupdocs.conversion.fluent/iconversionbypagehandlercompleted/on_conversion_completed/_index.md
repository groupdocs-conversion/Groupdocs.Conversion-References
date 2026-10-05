---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Aksi untuk menangani penyelesaian, menerima konteks halaman yang dikonversi. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Lihat Juga
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
