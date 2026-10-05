---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi dokumen selesai dengan sukses."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Mendaftarkan callback yang akan dipanggil ketika konversi dokumen selesai dengan sukses. Memanggil kembali menggantikan handler yang sebelumnya telah diatur.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Callable yang menangani penyelesaian, menerima konteks konversi. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Lihat Juga
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
