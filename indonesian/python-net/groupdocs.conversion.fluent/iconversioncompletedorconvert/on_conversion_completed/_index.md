---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menerima aliran dokumen yang dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Menerima aliran dokumen yang telah dikonversi. Dipicu hanya jika `ConvertTo(string fileName)` atau `ConvertTo(convertedStreamProvider)` telah disetel.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Penyedia aliran dokumen yang dikonversi (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
