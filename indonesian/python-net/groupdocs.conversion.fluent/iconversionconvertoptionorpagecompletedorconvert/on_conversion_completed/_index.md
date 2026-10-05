---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Terima aliran halaman yang dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Menerima aliran halaman yang dikonversi. Akan dipicu hanya jika `ConvertTo(convertedStreamProvider)` diatur.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Penyedia aliran halaman yang dikonversi converted_page_stream arg1arg1: `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Lihat Juga
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
