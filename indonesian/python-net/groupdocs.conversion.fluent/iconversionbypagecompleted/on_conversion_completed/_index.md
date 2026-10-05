---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menerima aliran halaman yang telah dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Menerima aliran halaman yang telah dikonversi. Akan dipicu hanya jika `ConvertTo(convertedStreamProvider)` diatur.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Penyedia aliran halaman yang dikonversi. `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
