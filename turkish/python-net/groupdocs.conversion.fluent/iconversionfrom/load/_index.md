---
title: "yükleme yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge dosya adını ayarlar."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Kaynak belge dosya adını ayarlar.

```python
def load(self, file_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | `str` | Kaynak belge. |

## load {#file_name}

Kaynak belgeler dizisini ayarlar.

```python
def load(self, file_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | `list[str]` | Kaynak belgeler kümesi. |

## load {#document_stream_provider}

Kaynak belge akışını ayarla.

```python
def load(self, document_stream_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Kaynak belge akış sağlayıcısı. |

| Kaldırır | Açıklama |
| :- | :- |
| `InvalidConverterSettingsException` | Dönüştürücü ayarlarının doğrulaması başarısız olursa. |

## load {#document_stream_provider}

Kaynak belge akışları sağlayıcısını ayarlar.

```python
def load(self, document_stream_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Kaynak belge akışları sağlayıcısı. |

| Kaldırır | Açıklama |
| :- | :- |
| `InvalidConverterSettingsException` | Dönüştürücü ayarlarının doğrulaması başarısız olursa. |

### Ayrıca Bakınız
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
