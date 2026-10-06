---
title: "with_options yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm süreci için dönüşüm seçeneklerini ayarlar."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Dönüşüm süreci için dönüşüm seçeneklerini ayarlar.

```python
def with_options(self, convert_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Dönüşüm seçenekleri. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Sağlayıcı işlevi kullanarak dönüşüm seçeneklerini ayarlar.

```python
def with_options(self, options_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Dönüşüm bağlamına dayalı dönüşüm seçenekleri sağlayan bir işlev. |

**Returns:** Handler setup interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
