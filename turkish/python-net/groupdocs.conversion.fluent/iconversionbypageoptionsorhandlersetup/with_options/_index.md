---
title: "with_options yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürme seçeneklerini ayarla."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Dönüştürme seçeneklerini ayarla.

```python
def with_options(self, convert_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Dönüştürme seçenekleri |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Dönüştürme seçeneklerini ayarla.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Dönüştürme seçenekleri. `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
