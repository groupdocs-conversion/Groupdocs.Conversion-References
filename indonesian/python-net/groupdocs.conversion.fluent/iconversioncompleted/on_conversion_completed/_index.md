---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menerima aliran dokumen yang telah dikonversi dan dipicu hanya jika ConvertTo(string fileName) atau ConvertTo(convertedStreamProvider) diatur."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Menerima aliran dokumen yang telah dikonversi dan dipicu hanya jika `ConvertTo(string fileName)` atau `ConvertTo(convertedStreamProvider)` telah diatur.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Penyedia aliran dokumen yang telah dikonversi. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
