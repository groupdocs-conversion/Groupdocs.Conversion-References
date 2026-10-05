---
title: "μέθοδος with_options"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίζει επιλογές μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

Ορίζει επιλογές μετατροπής.

```python
def with_options(self, convert_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Επιλογές μετατροπής |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Ορίζει επιλογές μετατροπής.

```python
def with_options(self, convert_options_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Επιλογές μετατροπής. Το `ConvertContext` περνά στον πάροχο. |

**Returns:** Interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
