---
title: "with_options yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Yükleme seçeneklerini ayarlayın."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

Yükleme seçeneklerini ayarlayın.

```python
def with_options(self, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| load_options | `LoadOptions` | Yükleme seçenekleri |

## with_options {#load_options_provider}

Şu anda yüklenen belge için yükleme seçenekleri sağlar.

```python
def with_options(self, load_options_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Yükleme seçenekleri sağlayıcı. Yükleme seçenekleri bağlamı. |

### Ayrıca Bakınız
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
