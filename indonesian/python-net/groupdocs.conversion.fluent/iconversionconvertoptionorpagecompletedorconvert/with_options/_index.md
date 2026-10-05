---
title: "metode with_options"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengatur opsi konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
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

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Mengatur opsi konversi.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Opsi konversi. `ConvertContext` diteruskan ke penyedia. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
