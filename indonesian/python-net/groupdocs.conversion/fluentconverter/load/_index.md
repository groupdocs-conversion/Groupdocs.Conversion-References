---
title: "metode load"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Konfigurasikan dokumen sumber untuk konversi."
type: docs
url: /id/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Konfigurasikan dokumen sumber untuk konversi.

```python
def load(cls, file_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `str` | Dokumen sumber. |

## load {#file_name}

Konfigurasikan kumpulan dokumen sumber.

```python
def load(cls, file_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `list[str]` | Array berkas sumber. |

## load {#document_stream_provider}

Konfigurasikan aliran dokumen sumber.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Penyedia aliran dokumen sumber. |

## load {#document_stream_provider}

Konfigurasikan sekumpulan aliran dokumen sumber.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Set penyedia aliran dokumen sumber. |

### Lihat Juga
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
