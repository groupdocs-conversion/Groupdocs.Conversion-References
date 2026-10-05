---
title: "metode load"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengatur nama file dokumen sumber."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Mengatur nama file dokumen sumber.

```python
def load(self, file_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `str` | Dokumen sumber. |

## load {#file_name}

Atur array dokumen sumber.

```python
def load(self, file_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `list[str]` | Kumpulan dokumen sumber. |

## load {#document_stream_provider}

Atur aliran dokumen sumber.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Penyedia aliran dokumen sumber |

| Menaikkan | Deskripsi |
| :- | :- |
| `InvalidConverterSettingsException` | Jika validasi pengaturan konverter gagal, pengecualian ini akan dilemparkan |

## load {#document_stream_provider}

Atur array aliran dokumen sumber.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Penyedia aliran dokumen sumber. |

| Menaikkan | Deskripsi |
| :- | :- |
| `InvalidConverterSettingsException` | Jika validasi pengaturan konverter gagal. |

### Lihat Juga
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
