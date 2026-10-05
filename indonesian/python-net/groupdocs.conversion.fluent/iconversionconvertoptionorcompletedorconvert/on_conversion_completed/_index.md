---
title: "metode on_conversion_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menerima aliran dokumen yang dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Menerima aliran dokumen yang telah dikonversi. Dipanggil hanya ketika `ConvertTo(string fileName)` atau `ConvertTo(convertedStreamProvider)` telah dikonfigurasi.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Penyedia untuk aliran dokumen yang dikonversi. Penyedia menerima `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
