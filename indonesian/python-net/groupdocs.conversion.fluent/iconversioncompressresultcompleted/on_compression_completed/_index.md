---
title: "metode on_compression_completed"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menerima aliran dokumen terkompresi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Menerima aliran dokumen terkompresi.

Dipicu hanya jika `Compress(CompressionConvertOptions)` diatur.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Callback aliran dokumen terkompresi. |

**Returns:** Interface to continue conversion building.

### Lihat Juga
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
