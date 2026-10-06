---
title: "on_compression_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Sıkıştırılmış belge akışını alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Sıkıştırılmış belge akışını alır.

`Compress(CompressionConvertOptions)` ayarlıysa yalnızca tetiklenir.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Sıkıştırılmış belge akışı geri çağrısı. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
