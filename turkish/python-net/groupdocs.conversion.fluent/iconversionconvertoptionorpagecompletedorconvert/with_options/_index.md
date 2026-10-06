---
title: "with_options yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürme seçeneklerini ayarlar."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

Dönüştürme seçeneklerini ayarlar.

```python
def with_options(self, convert_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Dönüştürme seçenekleri |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Dönüştürme seçeneklerini ayarlar.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Dönüştürme seçenekleri. `ConvertContext` sağlayıcıya geçirilir. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
