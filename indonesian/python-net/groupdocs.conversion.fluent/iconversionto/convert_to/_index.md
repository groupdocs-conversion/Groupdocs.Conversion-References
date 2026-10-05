---
title: "metode convert_to"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Simpan dokumen yang dikonversi sebagai file."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionto/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Simpan dokumen yang dikonversi sebagai file.

```python
def convert_to(self, file_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `str` | Dokumen yang dikonversi |

**Returns:** Options or handler setup interface to continue conversion building

## convert_to {#converted_stream_provider}

Menyimpan dokumen yang dikonversi sebagai aliran.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Penyedia aliran dokumen yang dikonversi. Konteks penyimpanan. |

**Returns:** Options or handler setup interface to continue conversion building.

### Lihat Juga
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
