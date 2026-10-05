---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menerima aliran halaman yang telah dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Menerima aliran halaman yang telah dikonversi. Dipicu hanya jika `ConvertTo(convertedStreamProvider)` telah diatur.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Penyedia aliran halaman yang telah dikonversi. Penyedia menerima `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
