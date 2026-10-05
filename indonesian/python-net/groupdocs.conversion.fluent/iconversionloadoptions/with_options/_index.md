---
title: "metode with_options"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Atur opsi pemuatan."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

Atur opsi pemuatan.

```python
def with_options(self, load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| load_options | `LoadOptions` | Opsi pemuatan. |

## with_options {#load_options_provider}

Menyediakan opsi pemuatan untuk dokumen yang sedang dimuat.

```python
def with_options(self, load_options_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Penyedia opsi pemuatan. Penyedia menerima konteks opsi pemuatan. |

### Lihat Juga
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
