---
title: "metode convert_by_page_to"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Simpan halaman yang dikonversi sebagai aliran."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Simpan halaman yang dikonversi sebagai aliran.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Penyedia aliran halaman dokumen yang dikonversi converted_stream_provider arg1arg1: Konteks penyimpanan |

**Returns:** Page options or handler setup interface to continue conversion building

### Lihat Juga
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
