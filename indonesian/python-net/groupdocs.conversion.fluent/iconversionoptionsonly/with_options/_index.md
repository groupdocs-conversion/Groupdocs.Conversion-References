---
title: "metode with_options"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengatur opsi konversi untuk proses konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Mengatur opsi konversi untuk proses konversi.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opsi konversi. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Mengatur opsi konversi menggunakan fungsi penyedia.

```python
def with_options(self, options_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Fungsi yang menyediakan opsi konversi berdasarkan konteks konversi. |

**Returns:** Handler setup interface to continue conversion building.

### Lihat Juga
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
