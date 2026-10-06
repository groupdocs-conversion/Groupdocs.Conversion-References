---
title: "on_compression_completed yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Sıkıştırılmış bir belge akışı alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

Sıkıştırılmış bir belge akışını alır. Yalnızca `Compress(CompressionConvertOptions)` ayarlanmışsa tetiklenir.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Sıkıştırılmış belge akışı geri çağrısı. |

**Returns:** Interface to continue conversion building.

### Ayrıca Bakınız
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
