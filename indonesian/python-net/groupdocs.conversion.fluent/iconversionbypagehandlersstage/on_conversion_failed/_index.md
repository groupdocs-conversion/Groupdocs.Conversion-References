---
title: "metode on_conversion_failed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi halaman gagal, menggantikan handler yang sebelumnya diatur pada pemanggilan ulang."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Mendaftarkan callback yang akan dipanggil ketika konversi halaman gagal, menggantikan handler yang sebelumnya diatur pada pemanggilan ulang.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable yang menangani kegagalan, menerima konteks halaman yang dikonversi dan pengecualian yang menyebabkan kegagalan. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Lihat Juga
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
