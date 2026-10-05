---
title: "metode with_options"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Atur opsi konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Atur opsi konversi.

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
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Opsi konversi. `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
