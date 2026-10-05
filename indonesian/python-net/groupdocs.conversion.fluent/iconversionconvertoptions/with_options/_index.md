---
title: "metode with_options"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengatur opsi konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Mengatur opsi konversi.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opsi konversi |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Atur opsi konversi.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Penyedia opsi konversi convert_options_provider arg1arg1: `ConvertContext` |

**Returns:** Interface to continue conversion building

### Lihat Juga
* class [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/)
