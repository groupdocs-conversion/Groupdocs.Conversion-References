---
title: "convert_to metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülmüş belgeyi dosya olarak kaydedin."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Dönüştürülmüş belgeyi dosya olarak kaydedin.

```python
def convert_to(self, file_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | `str` | Dönüştürülmüş belge. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Dönüştürülmüş belgeyi akış olarak kaydeder.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Dönüştürülmüş belge akış sağlayıcısı. Kaydetme bağlamı. |

**Returns:** Options or handler setup interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
