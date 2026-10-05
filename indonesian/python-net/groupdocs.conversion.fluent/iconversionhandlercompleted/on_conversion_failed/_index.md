---
title: "metode on_conversion_failed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal. Memanggil kembali menggantikan handler yang sebelumnya diatur.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – sebuah aksi untuk menangani kegagalan, menerima konteks konversi dan pengecualian yang menyebabkan kegagalan. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Lihat Juga
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
