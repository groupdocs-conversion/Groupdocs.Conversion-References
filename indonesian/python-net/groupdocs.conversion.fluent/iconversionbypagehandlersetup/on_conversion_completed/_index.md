---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_completed/
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

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Lihat Juga
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
