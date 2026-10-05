---
title: "metode on_conversion_failed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[`ConversionContext`, `Exception`], Any] – Aksi untuk menangani kegagalan, menerima konteks konversi dan pengecualian yang menyebabkan kegagalan. |

**Returns:** `IConversionHandlerOnly`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Lihat Juga
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
